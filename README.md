# How Automated work.

- Action:
    - Dockerfile: Build an application to contains on Docker container image.
    - Jenkinsfile: The condition when has any commits on `master` branch, It will trigger to to jenkins server for `Build`, `Push`, `Deploy`.
    - Jenkinsfile.config: This is an example to know about `Stages` of jenkins automated working.

# NodeJS-MongoDB-Demo

This is an example NodeJS application that works with MongoDB on Clever Cloud.

The application is a very simple list where you can add or delete values.

To install it, simply fork this repository and create an application from your GitHub repo.
Then create a MongoDB add-on and link it to your application, either via the <a href="https://www.clever-cloud.com/doc/clever-tools/getting_started/" target="_blank">Clever Tools CLI</a> or via the <a href="https://console.clever-cloud.com/" target="_blank">Clever Cloud console</a>.

That's it, the application will use the environnement variables to connect to MongoDB....
