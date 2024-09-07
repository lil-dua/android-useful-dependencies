# android-useful-dependencies

 
    # Kotlin Coroutine
    implementation( "org.jetbrains.kotlinx:kotlinx-coroutines-core:1.7.1")
    implementation( "org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.1")

    # Lifecycle
    implementation("androidx.lifecycle:lifecycle-livedata-ktx:2.7.0")
    implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.7.0")

    # RoomDatabase
    val roomVersion = "2.4.0"
    implementation("androidx.room:room-runtime:$roomVersion")
    annotationProcessor("androidx.room:room-compiler:$roomVersion")
    kapt("androidx.room:room-compiler:$roomVersion") // To use Kotlin annotation processing tool (kapt)
    implementation("androidx.room:room-ktx:$roomVersion") // optional - Kotlin Extensions and Coroutines support for Room
    implementation("androidx.room:room-guava:$roomVersion") // optional - Guava support for Room, including Optional and ListenableFuture
    implementation("androidx.room:room-paging:$roomVersion") // optional - Paging 3 Integration


    # Firebase
    implementation(platform("com.google.firebase:firebase-bom:32.5.0"))
    implementation("com.google.firebase:firebase-analytics")
    implementation("com.google.firebase:firebase-database")
    implementation("com.google.firebase:firebase-firestore")
    implementation("com.google.firebase:firebase-messaging")
    implementation("com.google.firebase:firebase-storage")

    # Retrofit2
    implementation("com.squareup.retrofit2:retrofit:2.7.2")
    implementation("com.squareup.retrofit2:converter-gson:2.7.2")
    implementation("com.squareup.retrofit2:converter-scalars:2.3.0")
    implementation("com.squareup.okhttp3:okhttp:4.10.0")
    implementation("com.squareup.okhttp3:logging-interceptor:3.4.1")

    # Dagger-Hilt
    implementation("com.google.dagger:hilt-android:2.48")
    kapt("com.google.dagger:hilt-android-compiler:2.48")
    kapt("org.jetbrains.kotlinx:kotlinx-metadata-jvm:0.3.0")

    # ImageView
    implementation("com.makeramen:roundedimageview:2.3.0")

    # Others
    implementation("androidx.core:core-splashscreen:1.0.1")
    implementation("com.google.android.material:material:1.12.0-rc01")
