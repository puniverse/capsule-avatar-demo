# Avatar-Node.js Capsule Demo

A simple demo of using [Capsule](https://github.com/puniverse/capsule) to package an [Avatar](https://avatar.java.net/) Node.js application.

There are two build files. `build1.gradle` creates a capsule with embedded dependencies, while `build2.gradle` creates a capsule that downloads dependencies at runtime.

To build:

    ./gradlew capsule

To run:

    java -jar build/lib/hello-nodejs.jar

This demo application is based on [this blog post](http://blog.jonasbandi.net/2014/03/running-nodejs-applications-on-jvm-with.html) by Jonas Bandi.

## License

Released to the [public domain](http://creativecommons.org/publicdomain/zero/1.0/)
