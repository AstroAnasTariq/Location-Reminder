# Location Reminder
A to-do list app with location reminders that remind the user to do something when the user is at a specific location. The app will require the user to create an account and login to set and access reminders.

## Features ##
* Create a Todo backed by selecting a point of interest on the map.
* Get a notification when you move close to that point of interest.
* Fully unit tested with instrumented tests for fragments and activities.

## Technical Details ##
* MVVM (repository pattern) + ViewModel + Repository + Data Binding + LiveData
* Google Maps SDK Android - Display Google Map, click on Point of Interest.
* Custom Google Map Style
* Get the device location, and move the camera to the current user location.
* Location permissions
* Geofencing API - Provide contextual reminders when users enter or leave an area of interest.
* Unit Test, Instrumented Test using Mockito and Espresso.
* Koin - A pragmatic lightweight dependency injection framework for Kotlin.
* Room Database
* RecyclerView
* Retrofit
* Kotlin Coroutines
* WorkManager
* Single activity
* Localized for multiple languages
* Navigation component
