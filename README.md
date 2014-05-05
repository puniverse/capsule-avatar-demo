# Avatar-Node.js Capsule Demo

A simple demo of using [Capsule](https://github.com/puniverse/capsule) to package an [Avatar](https://avatar.java.net/) Node.js application.

There are two build files. `build1.gradle` creates a capsule with embedded dependencies, while `build2.gradle` creates a capsule that downloads dependencies at runtime.

To build:

    gradle -b build1.gradle capsule

or:

    gradle -b build2.gradle capsule

To run:

    java -jar build/lib/hello-nodejs.jar

## License

Released to the [public domain](http://creativecommons.org/publicdomain/zero/1.0/)
