
## View Binding 🌅	  

```
// To add viewBinding in project : include this in build.gradle (:app) level file
android {
    ... ...
    ... ...
    buildFeatures {
        viewBinding true
    }
    ... ... 
    ... ...
}
```

## Navigation Architecture Component Library 🗺️

```
def nav_version = "2.3.5"

implementation "androidx.navigation:navigation-fragment-ktx:$nav_version"
implementation "androidx.navigation:navigation-ui-ktx:$nav_version"
```



## Coroutines 🧵	

```
implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.6.2'
implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-play-services:1.6.2'
```

## ViewModel & LiveData 🚀	

```
def lifecycle_version = "2.5.0-rc02"

implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:lifecycle_version"
implementation "androidx.lifecycle:lifecycle-livedata-ktx:lifecycle_version"
```

## Room Database Library 📁

```
def room_version = '2.4.2'
implementation "androidx.room:room-runtime:2.4.2"
kapt("androidx.room:room-compiler:$room_version")
implementation "androidx.room:room-ktx:$room_version"

// Add kapt at top of declaration in build.gradle (:app) file
apply plugin: 'kotlin-kapt'

```

## Paging3 📚	

```
implementation 'androidx.paging:paging-runtime-ktx:3.0.0'
```

## WorkManager 👷‍♂️

```
implementation "androidx.work:work-runtime-ktx:2.7.1"

```

## Retrofit 🪐

```
def retrofit_version = "2.9.0"
def logging_version = "4.3.1"

implementation "com.squareup.retrofit2:retrofit:$retrofit_version"
implementation "com.squareup.retrofit2:converter-gson:$retrofit_version"
implementation "com.squareup.okhttp3:okhttp:4.9.3"
implementation "com.squareup.okhttp3:logging-interceptor:$logging_version"
```

## SSP & SDP ⭐

```
implementation 'com.intuit.sdp:sdp-android:1.0.6'
implementation 'com.intuit.ssp:ssp-android:1.0.6'
```

## Coil - Kotlin Image Loading Library 	🖼️

```
implementation 'io.coil-kt:coil:0.9.1'
```


## Firebase Crashlytics & Performance libraries 🔥

```
//Recommended: Add the Firebase SDK for Google Analytics.
implementation 'com.google.firebase:firebase-analytics:20.0.0'

//Add the Firebase Crashlytics SDK.
implementation 'com.google.firebase:firebase-crashlytics:18.2.4'

//Performance
implementation 'com.google.firebase:firebase-perf:20.0.3'
implementation "androidx.core:core-ktx:1.7.0"
implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.4.0"
implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.4.0"
```
