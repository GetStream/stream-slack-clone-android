> **This sample is out of date.** It uses Stream Chat Android 6, one major version behind the current SDK. For current samples, see [Android-Samples](https://github.com/GetStream/Android-Samples).

![cover](https://user-images.githubusercontent.com/24237865/171068407-e3a634ba-14c5-41dc-931d-660892897313.png)

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>
  <a href="https://android-arsenal.com/api?level=21"><img alt="API" src="https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat"/></a>
  <a href="https://github.com/GetStream/stream-slack-clone-android/actions/workflows/android.yml"><img alt="Build Status" src="https://github.com/GetStream/stream-slack-clone-android/actions/workflows/android.yml/badge.svg"/></a>
</p>

This is a [Slack](https://slack.com/) clone app built with Jetpack Compose and [Stream Chat SDK for Compose](https://getstream.io/chat/sdk/compose?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_May2022_SlackAndroidClone&utm_term=DevRelOss) following clean architecture principles.

This repository serves as a demonstration for the following:

- Building the entire UI using Jetpack Compose.
- Implementing Android architecture components with Jetpack libraries such as Hilt for dependency injection.
- Managing background tasks using Kotlin Coroutines.
- Integrating real-time chat functionality and authentication using the Stream Chat SDK for seamless event handling. 

## :bulb: Additional Repositories

If you're interested in additional repositories that were built with Jetpack Compose and Stream SDK, check out the repositories below:

- [Chat GPT Android](https://github.com/skydoves/chatgpt-android): 📲 ChatGPT Android demonstrates a Chatbot application using OpenAI's chat API on Android with Stream Chat SDK for Compose.
- [Gemini Android](https://github.com/skydoves/gemini-android): ✨ Gemini Android demonstrates Google's Generative AI on Android with Stream Chat SDK for Compose.
- [WhatsApp Clone Compose](https://github.com/getStream/whatsApp-clone-compose): 📱 WhatsApp clone project demonstrates modern Android development built with Jetpack Compose and Stream Chat SDK for Compose.
- [Stream Draw Android](https://github.com/getStream/stream-draw-android): 🛥 Stream Draw is a real-time multiplayer drawing & chat game app built entirely with Jetpack Compose.
- [Facebook Messenger Clone](https://github.com/MathRoda/Messenger-clone): Facebook Messenger clone using Stream SDK & Jetpack Compose.

## 📲 Download
Go to the [Releases](https://github.com/GetStream/stream-slack-clone-android/releases) to download the latest APK.

<a href="https://getstream.io/chat/sdk/compose?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_May2022_SlackAndroidClone&utm_term=DevRelOss">
<img src="https://user-images.githubusercontent.com/24237865/138428440-b92e5fb7-89f8-41aa-96b1-71a5486c5849.png" align="right" width="12%"/>
</a>

## 🛥 Stream Chat SDK
Stream Slack Android clone was built with __[Stream Chat SDK for Compose](https://getstream.io/chat/sdk/compose?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_May2022_SlackAndroidClone&utm_term=DevRelOss)__ to implement messaging systems.
If you’re interested in adding powerful In-App Messaging to your app, check out the __[Android Chat Messaging Tutorial](https://getstream.io/tutorials/android-chat?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_May2022_SlackAndroidClone&utm_term=DevRelOss)__!

- [Stream Chat SDK for Android on GitHub](https://github.com/getStream/stream-chat-android)
- [Android Samples for Stream Chat SDK on GitHub](https://github.com/getStream/android-samples)
- [Stream Chat Compose UI Componenets Guidelines](https://getstream.io/chat/docs/sdk/android/compose/overview/)

## 📷 Previews

<p align="center">
<img src="art/art0.gif" alt="drawing" width="270" />
<img src="art/art1.png" alt="drawing" width="270" />
<img src="art/art2.png" alt="drawing" width="270" />
<img src="art/art3.png" alt="drawing" width="270" />
<img src="art/art4.png" alt="drawing" width="270" />
<img src="art/art5.png" alt="drawing" width="270" />
<img src="art/art6.png" alt="drawing" width="270" />
<img src="art/art7.png" alt="drawing" width="270" />
<img src="art/art8.png" alt="drawing" width="270" />
</p>

## 🏛️ Architecture

Stream Slack Clone Android follows the principles of Clean Architecture with Android Architecture Components.

### Architecture's layers & boundaries:

<img src="art/architecture.png" />

- **User Interface Layer**: The responsibility of the UI layer is to render the application data on the screen. UI elements must be updated whenever the application data changes from user interaction or external communication with the network and database.
- **Presentation Layer**: The responsibility of the Presentation layer is to interact and notify data changes between UI layers and Domain layers. It also holds and restores data in configuration changes.
- **Domain Layer**: The domain layer is responsible for abstracting complex business logic and improving its reusability. This layer transforms the complex application data into suitable types for Presentation layers and groups similar business logic as a single feature.
- **Data Layer**: The responsibility of the data layer is to deliver the result of business logic executions, such as CRUD operations (Create, Retrieve, Update, Delete – all system events). This layer can be designed with various strategies, like Repository or DataSource, for dividing the responsibility of executions.

For more information, check out the [The 2022 Android Developer Roadmap: Part 3, Architecture Components](https://getstream.io/blog/android-developer-roadmap-part-3/#architecture-components).

## 💡 The Android Developer Roadmap

For more Android-specific knowledge, be sure to check out the [Android Developer Roadmap](https://github.com/skydoves/android-developer-roadmap), which outlines essential topics, skills, and resources for Android development.

- **[The Android Platform: The 2022 Android Developer Roadmap – Part 1](https://getstream.io/blog/android-developer-roadmap?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_Dec2024_AndroidDeveloperRoadmap&utm_term=DevRelOss)**
- **[App Components: The Android Developer Roadmap – Part 2](https://getstream.io/blog/android-developer-roadmap-part-2?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_Dec2024_AndroidDeveloperRoadmap&utm_term=DevRelOss)**
- **[App Navigation and Jetpack: The Android Developer Roadmap – Part 3](https://getstream.io/blog/android-developer-roadmap-part-3?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_Dec2024_AndroidDeveloperRoadmap&utm_term=DevRelOss)**
- **[Design Patterns and Architecture: The Android Developer Roadmap – Part 4](https://getstream.io/blog/design-patterns-and-architecture-the-android-developer-roadmap-part-4?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_Dec2024_AndroidDeveloperRoadmap&utm_term=DevRelOss)**
- **[Jetpack Compose: The Android Developer Roadmap – Part 5](https://getstream.io/blog/android-developer-roadmap-part-5?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_Dec2024_AndroidDeveloperRoadmap&utm_term=DevRelOss)**

## 🛠 Tech Stack & Open Source Libraries
- Minimum SDK level 21.
- 100% [Jetpack Compose](https://developer.android.com/jetpack/compose) based + [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) + [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/) for asynchronous.
- [Compose Chat SDK for Messaging](https://getstream.io/chat/sdk/compose?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_May2022_SlackAndroidClone&utm_term=DevRelOss): The Jetpack Compose Chat Messaging SDK is built on a low-level chat client and provides modular, customizable Compose UI components that you can easily drop into your app.
- Jetpack
  - Compose: Android’s modern toolkit for building native UI.
  - Lifecycle: Observe lifecycle changes.
  - ViewModel: UI related data holder and lifecycle aware.
  - Room Persistence: Constructs Database by providing an abstraction layer over SQLite to allow fluent database access.
  - Paging3: Loads and displays pages of data from a larger dataset from local storage or over network.
  - App Startup: Provides a straightforward, performant way to initialize components at application startup.
- [Hilt](https://dagger.dev/hilt/): Dependency Injection.
- [Landscapist-Glide](https://github.com/skydoves/landscapist#glide): Jetpack Compose image loading library that fetches and displays network images with Glide, Coil, and Fresco.
- [Retrofit2 & OkHttp3](https://github.com/square/retrofit): Construct the REST APIs and paging network data.
- [Timber](https://github.com/JakeWharton/timber): A logger with a small, extensible API which provides utility.

## Copyrights & Credits

All copyrights of the resources, logo, branding, content, concepts, and phrases that are used in this open-source project belong to [Slack](https://slack.com/). Also, 
this project was forked from [SlackAndroidClone](https://github.com/Anmol92verma/SlackAndroidClone) and the original credit goes to [Anmol92verma](https://github.com/Anmol92verma).

 <a href="https://getstream.io/chat/sdk/compose?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_May2022_SlackAndroidClone&utm_term=DevRelOss">
<img src="https://user-images.githubusercontent.com/24237865/138428440-b92e5fb7-89f8-41aa-96b1-71a5486c5849.png" align="right" width="12%"/></a>

## Find this repository useful? 💙
Support it by joining __[stargazers](https://github.com/GetStream/stream-slack-clone-android/stargazers)__ for this repository. :star: <br>
Also, follow __[maintainers](https://github.com/skydoves)__ on GitHub for our next creations! 🤩

# License
```xml
Copyright 2022 Stream.IO, Inc. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
