# Movie World (Compose Multiplatform)
Movie World app using [The Movie DB](https://www.themoviedb.org) built with Compose Multiplatform and MVVM architecture.<br>

# Platform
- iOS
- Android



https://user-images.githubusercontent.com/34370836/234033163-257dd925-343c-42af-b470-9160bf225ede.mp4


https://user-images.githubusercontent.com/34370836/234032166-47213190-cfc0-4f3a-b6a8-d000102c5de6.mp4




# Main Features
- Movie List
- Movie Detail
- Navigation
- Bottom Navigation

## Architecture
- MVVM Architecture (Model - ComposableView - ViewModel)

## Built With 🛠
- [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform) - Compose Multiplatform, a modern UI framework for Kotlin that makes building performant and beautiful user interfaces.
- [PreCompose](https://github.com/Tlaster/PreCompose) - Compose Multiplatform Navigation && State Management
- [Ktor Client](https://ktor.io/docs/welcome.html) - Ktor includes a multiplatform asynchronous HTTP client, which allows you to make requests and handle responses.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous and more.
- [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/-flow/) - A cold asynchronous data stream that sequentially emits values and completes normally or with an exception.
- [Image Loader](https://github.com/qdsfdhvh/compose-imageloader) - Compose Image library for Kotlin Multiplatform.
- [Android Studio](https://developer.android.com/studio/intro) - Android Studio is the official Integrated Development Environment (IDE) for Android app development.
- [XCode](https://developer.apple.com/xcode/) - Xcode 14 includes everything you need to develop, test, and distribute apps across all Apple platforms.

## Project structure

This Compose Multiplatform project includes three modules:

### [`shared`](/shared)
This is a Kotlin module that contains the logic common for both Android and iOS applications, the code you share between platforms.

https://user-images.githubusercontent.com/34370836/234032913-0bff8126-6d56-408a-a4af-dd4fd2ad8715.mp4


This shared module is also where you write your Compose Multiplatform code. In `shared/src/commonMain/kotlin/App.kt`, you can find the shared root `@Composable` function for your app.
It uses Gradle as the build system. You can add dependencies and change settings in `shared/build.gradle.kts`. The shared module builds into an Android library and an iOS framework.

### [`androidApp`](/androidApp)
This is a Kotlin module that builds into an Android application. It uses Gradle as the build system. The `androidApp` module depends on and uses the shared module as a regular Android library.

### [`iosApp`](/iosApp)
This is an Xcode project that builds into an iOS application. It depends on and uses the shared module as a CocoaPods dependency.

## 👨 Developed By

I hope you understand my effort. Please feel free to reach out to me for any questions.

Email Id: ganeshajdivekar@gmail.com 
Mobile: +91 8459684546

**Ganesh Divekar**

[![Medium](https://img.shields.io/badge/-medium-grey?logo=medium)](https://ganeshajdivekar.medium.com/)
[![Linkedin](https://img.shields.io/badge/-linkedin-grey?logo=linkedin)](https://www.linkedin.com/in/ganesh-divekar-96a72bb7/)
