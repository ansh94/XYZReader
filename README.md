# XYZ Reader

* [About](#about)
* [What did I learn](#what-did-i-learn)
* [Rubric check list](#rubric-check-list)
* [Implementation](#implementation)


## About

This project is part of the Udacity Android Developer Nanodegree under the name - Project P5: Make Your App Material.

### Project Overview:
In this project, I redesigned an app to follow the [Material Design guidelines](https://material.io/guidelines/material-design/introduction.html) and translate a set of static design mocks to a living and breathing app.

### Why this Project?
This project gave me the opportunity to improve an app’s design, a vital skill for building apps users would love. It also would replicate a common developer task of updating and changing an app's design as new standards are released.

## What did I learn?

Through this project, I did:

* Understood the fundamentals of Android design.
* Applied Material Design guidelines to an mobile application.
* Separated an interface into surfaces.
* Effectively used transitions and motion.

## Rubric Check list

- [x] App uses the Design Support library and its provided widget types (```FloatingActionButton```, ```AppBarLayout```, ```SnackBar```, etc).
- [x] App uses ```CoordinatorLayout``` for the main Activity.
- [x] App theme extends from ```AppCompat```.
- [x] App uses an ```AppBar``` and associated ```Toolbars```.
- [x] App provides a Floating Action Button for the most common action(s).
- [x] App properly specifies elevations for app bars, FABs, and other elements specified in the [Material Design specification](https://material.io/guidelines/material-design/introduction.html).
- [x] App has a consistent color theme defined in ```styles.xml```. Color theme does not impact usability of the app.
- [x] App provides sufficient space between text and surrounding elements.
- [x] App uses images that are high quality, specific, and full bleed.
- [x] App uses fonts that are either the Android defaults, are complementary, and aren't otherwise distracting.
- [x] App conforms to common standards found in the Android Nanodegree General Project Guidelines.

## Implementation

### Gradle Configuration

* Module build.gradle

```Gradle
android {
    compileSdkVersion 25
    buildToolsVersion "25.0.2"

    defaultConfig {
        minSdkVersion 21
        targetSdkVersion 25
    }
}
````

```Gradle
dependencies {

    compile 'com.android.support:support-v4:25.3.1'
    compile 'com.android.support:support-v13:25.3.1'
    compile 'com.android.support:appcompat-v7:25.3.1'
    compile 'com.android.support:palette-v7:25.3.1'
    compile 'com.android.support:recyclerview-v7:25.3.1'
    compile 'com.android.support:cardview-v7:25.3.1'
    compile 'com.android.support:design:25.3.1'
    compile 'com.squareup.okhttp3:okhttp:3.1.2'
    compile files('libs/volley.jar')
}
````


