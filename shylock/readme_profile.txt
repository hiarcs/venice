This profile has created a multi-project build where the "server" module contains the Grails application and the "client" module contains the Angular 2 application.

To start the Grails application separately, execute `./gradlew server:bootRun`
To start the client side application separately, execute `./gradlew client:bootRun`
To start both the client and server applications simultaneously, execute `./gradlew bootRun --parallel`

Run the front-end unit tests and grails unit tests simultaneously with `./gradlew test`
Run the front-end e2e and grails integration tests simultaneously with `./gradlew integrationTest`

No need to install Node, though we would recommend doing so if you'll be working with the front-end directly often!
