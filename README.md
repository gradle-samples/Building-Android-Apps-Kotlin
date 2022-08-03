# Building-Android-Apps-Sample
This sample shows how a simple Android application written in Java can be built with Gradle. The application was created following the Build your first app guide.

NOTE: You can open this sample inside a Android Studio IDE using the https://developer.android.com/studio/projects/create-project#ImportAProject[project importer].

This sample shows how a simple Android application written in Java can be built with Gradle.
The application was created following the https://developer.android.com/training/basics/firstapp[Build your first app guide].

====
include::sample[dir="groovy",files="app/build.gradle[]"]
include::sample[dir="kotlin",files="app/build.gradle.kts[]"]
====

To build the application:

[listing.terminal]
----
$ ./gradlew build
----

For more information, we suggest reading link:[Getting Started with Gradle](https://docs.gradle.org/current/userguide/getting_started.html).

You can also find https://developer.android.com/guide[Android development related information inside the guides provided by the Android team].
