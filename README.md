# XYZ Reader
[Udacity Grow with Google](https://www.udacity.com/grow-with-google) [Android Developer Nanodegree Program](https://www.udacity.com/course/android-developer-nanodegree-by-google--nd801)

## Overview
The task was to redesign an XYZ Reader app taking into account users feedback along with following
the Material Design guidelines and translating a set of static design mocks to a living and breathing app.
The starter code was taken from [here](https://github.com/udacity/xyz-reader-starter-code).

## Screenshots
<p align="center">
    <img src="screenshots/Screenshot_1.png?raw=true" width=275 />
    <img src="screenshots/Screenshot_2.png?raw=true" width=275 />
    <img src="screenshots/Screenshot_3.png?raw=true" width=275 />
</p>
<p align="center">
    <img src="screenshots/Screenshot_4.png?raw=true" width=275 />
    <img src="screenshots/Screenshot_5.png?raw=true" width=275 />
    <img src="screenshots/Screenshot_6.png?raw=true" width=275 />
</p>

## How to work with the project
Just clone this repository or download as an archive and import in Android Studio.

## Project Requirements

### Required Behavior
- [x] App uses the Design Support library and its provided widget types (`FloatingActionButton`, `AppBarLayout`, `SnackBar`, etc)
- [x] App uses `CoordinatorLayout` for the main Activity
- [x] App theme extends from `AppCompat`
- [x] App uses an `AppBar` and associated `Toolbar`s
- [x] App provides a Floating Action Button for the most common action(s)
- [x] App properly specifies elevations for app bars, FABs, and other elements specified in the [Material Design specification](http://www.google.com/design/spec/material-design/introduction.html)
- [x] App has a consistent color theme defined in `styles.xml`. Color theme does not impact usability of the app
- [x] App provides sufficient space between text and surrounding elements
- [x] App uses images that are high quality, specific, and full bleed
- [x] App uses fonts that are either the Android defaults, are complementary, and aren't otherwise distracting
- [x] App conforms to common standards found in the [Android Nanodegree General Project Guidelines](http://udacity.github.io/android-nanodegree-guidelines/core.html)
- [x] App utilizes stable release versions of all libraries, Gradle, and Android Studio

## What have I learnt?
* Applying Material Design guidelines to a mobile application
* Separating an interface into surfaces
* Effectively using motion and transitions with shared elements
* Using CoordinatorLayout and CollapsingToolbarLayout
* Sharing FloatingActionButton across different Fragments

## Libraries
* [AndroidX](https://developer.android.com/jetpack/androidx/) previously known as *'Android support Library'*
    * [ConstraintLayout](https://developer.android.com/training/constraint-layout) allows to create large and complex layouts
    * [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview) is a more advanced and flexible version of *ListView*
    * [CardView](https://developer.android.com/guide/topics/ui/layout/cardview)
* [Retrofit 2](https://github.com/square/retrofit) type-safe HTTP client by Square, Inc.
* [OkHttp](https://square.github.io/okhttp/) an efficient HTTP client by Square, Inc.
* [Gson](https://github.com/google/gson) helps with serialization/deserialization of Java Objects into JSON and back
* [Picasso](https://square.github.io/picasso/) allows for hassle-free image loading

## License
    Copyright 2020 demur

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.