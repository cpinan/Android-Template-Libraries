# Android-Template-Librariers
Helpful gradle file with versions and libraries.

You can check the file <b>buildsystem/configurations.gradle</b> to see in brief versions and libraries.

Also you can take a look at the templates inside that folder, with basic structure for new projects.

Here is the list of libraries in buildsystem folder:

        org.jetbrains.kotlin:kotlin-stdlib-jdk7
        org.jetbrains.kotlin:kotlin-stdlib-jdk8
        org.jetbrains.kotlin:kotlin-gradle-plugin

        com.google.gms:google-services

        androidx.appcompat:appcompat
        androidx.annotation:annotation
        androidx.legacy:legacy-support-v4
        androidx.recyclerview:recyclerview
        androidx.cardview:cardview
        androidx.preference:preference
        androidx.browser:browser
        com.google.android.material:material

        androidx.fragment:fragment-ktx
        androidx.core:core-ktx

        androidx.constraintlayout:constraintlayout
        androidx.paging:paging-runtime

        androidx.lifecycle:lifecycle-extensions
        androidx.lifecycle:lifecycle-livedata-ktx
        androidx.lifecycle:lifecycle-viewmodel-ktx
        androidx.lifecycle:lifecycle-runtime
        androidx.lifecycle:lifecycle-compiler
        androidx.lifecycle:lifecycle-common-java8

        android.arch.navigation:navigation-fragment-ktx
        android.arch.navigation:navigation-ui-ktx

        com.squareup.retrofit2:retrofit
        com.squareup.retrofit2:converter-scalars
        com.squareup.retrofit2:converter-moshi
        com.jakewharton.retrofit:retrofit2-kotlin-coroutines-adapter

        com.squareup.moshi:moshi
        com.squareup.moshi:moshi-kotlin

        com.github.bumptech.glide:glide
        com.github.bumptech.glide:compiler

        org.jetbrains.kotlinx:kotlinx-coroutines-core
        org.jetbrains.kotlinx:kotlinx-coroutines-android

        androidx.room:room-runtime:${versions.room}",
        androidx.room:room-compiler:${versions.room}",

        androidx.work:work-runtime-ktx

        com.google.firebase:firebase-analytics
        com.google.firebase:firebase-auth

        com.google.firebase:firebase-ml-vision
        com.google.firebase:firebase-ml-vision-image-label-model
        com.google.firebase:firebase-ml-vision-face-model
        com.google.firebase:firebase-ml-vision-object-detection-model
