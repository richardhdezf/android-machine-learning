Android machine learning sample
=================

An application focused on the implementation of machine learning features.


Introduction
------------

This sample demonstrates the use of machine learning algorithms, it uses tensorflow library and
ecosystem. The showcases the image classification problem. It uses a pretrained model from
tensorflow hub.

Getting Started
---------------

Clone or download the project, then run it.

Screenshots
-----------

![machine_larning app video_1](screenshots/video1.gif "Machine learning app")

Libraries Used
--------------

* [tesorflow][101] - Platform for machine learning development.
    * [tensorflow hub][102] - Lets you search and discover hundreds of trained, ready-to-deploy
      machine learning models.
    * [mnasnet_1.3_224][103] - Image classification model created using Cloud AutoML.
* [Foundation][0] - Components for core system capabilities and support for multidex and automated
  testing.
    * [AppCompat][1] - Degrade gracefully on older versions of Android.
    * [Android KTX][2] - Write more concise, idiomatic Kotlin code.
    * [Test][4] - An Android testing framework for unit and runtime UI tests.
    * [CameraX][5] - .
* [Architecture][10] - A collection of libraries that help you design robust, testable, and
  maintainable apps. Start with classes for managing your UI component lifecycle and handling data
  persistence.
    * [Lifecycles][12] - Create a UI that automatically responds to lifecycle events.
    * [LiveData][13] - Build data objects that notify views when the underlying database changes.
    * [dataBinding][18] - .
    * [Navigation][14] - Handle everything needed for in-app navigation.
    * [ViewModel][17] - Store UI-related data that isn't destroyed on app rotations. Easily schedule
      asynchronous tasks for optimal execution.
* [UI][30] - Details on why and how to use UI Components in your apps - together or separate
    * [Material design][32] - for an expressive and adaptable design system.
    * [Fragment][34] - A basic unit of composable UI.
    * [Layout][35] - Lay out widgets using different algorithms.

[0]: https://developer.android.com/jetpack/components

[1]: https://developer.android.com/topic/libraries/support-library/packages#v7-appcompat

[2]: https://developer.android.com/kotlin/ktx

[4]: https://developer.android.com/training/testing/

[10]: https://developer.android.com/jetpack/arch/

[12]: https://developer.android.com/topic/libraries/architecture/lifecycle

[13]: https://developer.android.com/topic/libraries/architecture/livedata

[14]: https://developer.android.com/topic/libraries/architecture/navigation/

[17]: https://developer.android.com/topic/libraries/architecture/viewmodel

[18]: https://developer.android.com/topic/libraries/data-binding

[30]: https://developer.android.com/guide/topics/ui

[32]: https://material.io/develop/android

[34]: https://developer.android.com/guide/components/fragments

[35]: https://developer.android.com/guide/topics/ui/declaring-layout

[101]:  https://www.tensorflow.org/

[102]: https://tfhub.dev/

[103]: https://tfhub.dev/tensorflow/lite-model/mnasnet_1.3_224/1/metadata/1


Upcoming features
-----------------
Updates will include incorporating additional machine learning features.

License
-------

Copyright 2018 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor license agreements.
See the NOTICE file distributed with this work for additional information regarding copyright
ownership. The ASF licenses this file to you under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License. You may obtain a copy of the
License at

https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
implied. See the License for the specific language governing permissions and limitations under the
License.