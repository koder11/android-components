Android Components 
=================

This repor contains multiple android projects illustrating android development best practices using Jetpack component
It explains the usage of new Jetpack component with very simple and basic examples

Introduction
------------

Jetpack is a suite of libraries to help developers follow best practices, reduce boilerplate code, and write code that works consistently across Android versions and devices so that developers can focus on the code they care about.
AndroidX is a new support library that is a part of Jetpack. It has Better package management. With androidX, you get standardized and independent versioning, as well as better standardized naming and more frequent releases. Jetpack is the external branding for libraries within androidx.

![Android Jetpack](Screenshots/android_jetpack.png "Android Jetpack")

Not Drunk (NOD)
---------------

NOD is a fun quiz game where you have to answer all the questions in given limited time.

![NOD Splash screen](Screenshots/NOD_splash_screen.png "Splash screen")

Libraries Used
--------------
* [Foundation][0] - Components for core system capabilities, Kotlin extensions and support for
  multidex and automated testing.
  * [AppCompat][1] - Degrade gracefully on older versions of Android.
  * [Android KTX][2] - Write more concise, idiomatic Kotlin code.
* [Architecture][10] - A collection of libraries that help you design robust, testable, and
  maintainable apps. Start with classes for managing your UI component lifecycle and handling data
  persistence.
  * [Data Binding][11] - Declaratively bind observable data to UI elements.
  * [Lifecycles][12] - Create a UI that automatically responds to lifecycle events.
  * [LiveData][13] - Build data objects that notify views when the underlying database changes.
  * [Navigation][14] - Handle everything needed for in-app navigation
  * [ViewModel][17] - Store UI-related data that isn't destroyed on app rotations. Easily schedule
     asynchronous tasks for optimal execution.
     
[0]: https://developer.android.com/jetpack/components
[1]: https://developer.android.com/topic/libraries/support-library/packages#v7-appcompat
[2]: https://developer.android.com/kotlin/ktx
[10]: https://developer.android.com/jetpack/arch/
[11]: https://developer.android.com/topic/libraries/data-binding/
[12]: https://developer.android.com/topic/libraries/architecture/lifecycle
[13]: https://developer.android.com/topic/libraries/architecture/livedata
[14]: https://developer.android.com/topic/libraries/architecture/navigation/
[17]: https://developer.android.com/topic/libraries/architecture/viewmodel
