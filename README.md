# AeroGear Android Auth [![Build Status](https://travis-ci.org/aerogear/aerogear-android-auth.png)](https://travis-ci.org/aerogear/aerogear-android-auth)

AeroGear's Android libraries are built as jar, apklib and aar using [Maven](http://maven.apache.org/) and the [android-maven-plugin](https://github.com/jayway/maven-android-plugin). The project follows the standard Android project layout as opposed to the standard Maven layout so sources will be in /src instead of /src/main/java and can be imported directly into IDE as an Android project.

## Auth

AeroGear Android Auth will give developers the ability to integrate their Android application with RESTful services.

## Building

Until the 2.0 modules are stable and in Maven Central, we will need to build the projects first.  Please take a look of the [step by step on our website](http://aerogear.org/docs/guides/aerogear-android/HowToBuildAeroGearAndroidLibrary/)

## Usage

There are two supported ways of developing apps using AeroGear for Android. Development may be done with Maven and Android Studio. Maven and Android Studio feature good dependency and library management and are far easier to get set up and developing.

### Android Studio

Add to your application's `build.gradle` file

```
dependencies {
  compile 'org.jboss.aerogear:aerogear-android-auth:2.0.0-SNAPSHOT@aar'
}
```

### Maven

Include the following dependencies in your project's `pom.xml`


```
<dependency>
  <groupId>org.jboss.aerogear</groupId>
  <artifactId>aerogear-android-auth</artifactId>
  <version>2.0.0-SNAPSHOT</version>
  <scope>provided</scope>
  <type>jar</type>
</dependency>

<dependency>
  <groupId>org.jboss.aerogear</groupId>
  <artifactId>aerogear-android-auth</artifactId>
  <version>2.0.0-SNAPSHOT</version>
  <type>apklib</type>
</dependency>
```

## Documentation

For more details about the current release, please consult [our documentation](http://aerogear.org/docs/guides/aerogear-android/).

## Development

If you would like to help develop AeroGear you can join our [dev list](https://lists.jboss.org/mailman/listinfo/aerogear-dev), join #aerogear on Freenode, or shout at us on Twitter @aerogears.

Also takes some time and skim the [contributor guide](http://aerogear.org/docs/guides/Contributing/)

## Questions?

Join our [user list](https://lists.jboss.org/mailman/listinfo/aerogear-user) for any questions and help! We really hope you enjoy app development with AeroGear!

