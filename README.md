# Awesome FTC Android

**Beware!:** These are *very* opinionated curated selections! If you have a suggestion, send a pull request!
I've left out most of what lists like this usually talk about, since it's usually geared towards building
regular Android apps.

- [Tutorials and Documentation](#tutorials-and-documentation)
  - [Setup](#setup)
  - [Programming](#programming)
- [Apps](#apps)
- [Libraries](#libraries)
  - [Data Structures](#data-structures)
  - [Databases](#databases)
  - [Dependency Injection](#dependency-injection)
  - [Vision and Camera](#vision-libraries)
  - [Crashes and Logging](#crashes-and-logging)
  - [Utilities](#utilities)
- [A Nice Starting Point](#a-nice-starting-point)

## Tutorials and Documentation

### Setup

### Programming
- [FTC SDK Training manual](https://github.com/ftctechnh/ftc_app/blob/master/doc/tutorial/FTCTraining%20Manual%20v0_93.pdf)
- [Javadoc for SDK](http://htmlpreview.github.io/?https://github.com/ftctechnh/ftc_app/blob/master/doc/javadoc/index.html)

## Apps
- [Driver Station](https://play.google.com/store/apps/details?id=com.qualcomm.ftcdriverstation&hl=en)
- [Controller](https://play.google.com/store/apps/details?id=com.qualcomm.ftcrobotcontroller&hl=en)

## Libraries

### Data structures
Stuff for storing data :)
- [Tape](http://square.github.io/tape/): Fast FIFO queues

### Databases
Databases let you persist your robot's state over multiple runs, and store data persistently.
- [Realm](https://github.com/realm/realm-java): An popular, easy-to-use Android database
- [Sugar ORM](http://satyan.github.io/sugar/index.html): An easy way of using the built-in SQLite database in Android

### Dependency Injection
Dependency Injection makes it easier to write Java without "FactoryFactory" classes,
and makes reusing code easier.
- [Dagger 1](http://square.github.io/dagger/)
- [Dagger 2](http://google.github.io/dagger/)

### Vision Libraries
It's *really* nice that we have a camera this year.
Vision libraries let you do object tracking and cool stuff like that.
- [FastCV](https://developer.qualcomm.com/software/fast-cv-sdk): Qualcomm's Snapdragon-tailored vision SDK
- [OpenCV(4Android)](http://opencv.org/platforms/android.html): OpenCV for Android

### Crashes and Logging
Every app *will* end up crashing, it's just a matter of *when* :)
- [LeakCanary](https://github.com/square/leakcanary): Detect memory leaks when they happen, and report them (memory leaks are **A Bad Thing**)
- [Hugo](https://github.com/JakeWharton/hugo): Easier logging

### Utilities
- [Apache Commons](https://commons.apache.org/): A collection of useful Java utils
- [Guava](https://github.com/google/guava): Google's collection of useful Java utils
- [Retrolambda](https://github.com/orfjackal/retrolambda): Use cool new Java 8 features on Java 7 and below (because we're using Java 7 phones)

## A nice starting point
If you want some additional utils in your app, I'd start out with these libraries:
- Dagger 2
- Guava
- Commons Math
- (and maybe Realm)

## Further reading
- [Awesome Android](https://github.com/JStumpp/awesome-android)
- [Android Arsenal](http://android-arsenal.com/)
