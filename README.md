
# mim-OE-SE-Android

**mim OE (mim Operating Environment)**, mim-OE-Client Standard Edition for Android.

## Before You Start

- [Explore developer resources & documentation](https://developer.mimik.com)
- [Sign up and create a mimik developer console account](https://developer.mimik.com/console/create_account)
- [Follow the Integrating the mimik Client Library into Android project guide](https://devdocs.mimik.com/tutorials/01-submenu/03-submenu/02-index).
- [Learn the basics of Working with mimOE in an Android project](https://devdocs.mimik.com/key-concepts/11-index).


## Installation Guide

To get started, add the mim OE Maven repository to your project-level `build.gradle`:


```gradle
dependencyResolutionManagement {
    repositories {
        maven {
            url "https://s3-us-west-2.amazonaws.com/mimik-android-repo"
        }
    }
}
```

Then add the library dependency to your app-level `build.gradle`

```gradle
dependencies {
    implementation 'com.mimik.mim-oe-sdk-android:mim-oe-client-developer:3.14.0.1'
}
```

<!-- ## Documentation -->

<!-- `EdgeCore/EdgeClient` API reference documentation can be found  [here](https://mimikgit.github.io/cocoapod-EdgeCore/documentation/edgecore/edgeclient).

`EdgeEngineClient` platform protocol API reference documentation is [here](https://mimikgit.github.io/cocoapod-EdgeCore/documentation/edgecore/edgeengineclient).

`EdgeService` API references are available [here](https://mimikgit.github.io/cocoapod-EdgeService/documentation/edgeservice/). -->

## Tutorials

After installation, try the following tutorials:

- [Understanding the mimik Client Library for Android](https://devdocs.mimik.com/key-concepts/11-index).
- [Creating a Simple Android Application that Uses a mim OE Microservice](https://devdocs.mimik.com/tutorials/01-submenu/03-submenu/01-index).
- [Integrating the mimik Client Library into an Android project](https://devdocs.mimik.com/tutorials/01-submenu/03-submenu/02-index).
- [Working with mimOE in an Android project](https://devdocs.mimik.com/tutorials/01-submenu/03-submenu/03-index).
- [Working with edge microservices in an Android project](https://devdocs.mimik.com/tutorials/01-submenu/03-submenu/04-index).
