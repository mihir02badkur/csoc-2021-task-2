
# Introduction

Android uses a file system that's similar to disk-based file systems on other platforms. The system provides several options for you to save your app data:

- **App-specific storage:** Store files that are meant for your app's use only, either in dedicated directories within an internal storage volume or different dedicated directories within external storage. Use the directories within internal storage to save sensitive information that other apps shouldn't access.
- **Shared storage:** Store files that your app intends to share with other apps, including media, documents, and other files.
- **Preferences:** Store private, primitive data in key-value pairs.
- **Databases:** Store structured data in a private database using the Room persistence library.

    [Android tutorial on data storage](https://developer.android.com/training/data-storage)

# Storing data locally

## Using Shared Preferences

Shared Preferences is the way to go if you’re saving primitive data as key-value pairs. It requires a key, which is a String, and the corresponding value for the said key. The value can be any of the following: a boolean, float, int, long, or another string.

[](https://developer.android.com/reference/android/content/SharedPreferences](https://developer.android.com/reference/android/content/SharedPreferences))

[Shared Preferences in Android with Example](https://www.geeksforgeeks.org/shared-preferences-in-android-with-examples/)

[Shared Preferences tutorial](https://www.youtube.com/watch?v=fJEFZ6EOM9o)

## Using Internal storage

It is specifically for when you need to store data on the file system, but you don’t want other apps or users to have access. This data storage is so private, in fact, that it’s deleted from the device as soon as you uninstall your app.

[Internal Storage in Android with Example](https://www.geeksforgeeks.org/internal-storage-in-android-with-example/)

[Simple tutorial on how to use Internal storage ](https://www.youtube.com/channel/UC_Fh8kvtkVPkeihBs42jGcA)

## External Storage

To give users better control over their files and cut down on clutter, apps now have scoped access to external storage by default. This means that they can tap into the specific directory on external storage and the media that the app creates.

 [Android External Storage with Examples ](https://www.tutlane.com/tutorial/android/android-external-storage-with-examples#:~:text=In)

 [Tutorial](https://www.youtube.com/watch?v=7CEcevGbIZU)

## SQLite database

Android provides support for apps to use SQLite databases for data storage. The databases you create remain specific to your app and can only be accessed inside your app. Of course, you should have at least some knowledge of SQL before you attempt to store data with an SQLite database.

[Simple example of using SQlite database](https://developer.android.com/jetpack/androidx/releases/sqlite?gclid=CjwKCAjwn6GGBhADEiwAruUcKm3bIpx8ec_3s6U7EnBthTh-jqwdp-3SJpnLMGXx-1erwDR6Gc9EvhoCgcgQAvD_BwE&gclsrc=aw.ds](https://developer.android.com/jetpack/androidx/releases/sqlite?gclid=CjwKCAjwn6GGBhADEiwAruUcKm3bIpx8ec_3s6U7EnBthTh-jqwdp-3SJpnLMGXx-1erwDR6Gc9EvhoCgcgQAvD_BwE&gclsrc=aw.ds))

We recommend using android library "Room" to make task easier.

### Room database Library

The Room persistence library provides an abstraction layer over SQLite to allow fluent database access while harnessing the full power of SQLite. In particular, Room provides the following benefits:

- Compile-time verification of SQL queries.
- Convenience annotations that minimize repetitive and error-prone boilerplate code.
- Streamlined database migration paths.

Because of these considerations, we highly recommend that you use Room instead of [using the SQLite APIs directly](https://developer.android.com/training/data-storage/sqlite).

[Room- data storage - tutorial](https://developer.android.com/training/data-storage/room)

[Room-data storage - tutorial II](https://www.youtube.com/watch?v=ONb_MuPBBlg)

## NOTE:

Don't forget to give permissions to your app for accessing your device local storage . 

# Challenge and submission

Let's dig in to the challenges of this week . 

[COPS-IITBHU/csoc-2021-task-2](https://github.com/COPS-IITBHU/csoc-2021-task-2)

All details have been provided in the README.md file.


- Mihir Kumar Badkur - [To_Do_Application](https://github.com/mihir02badkur/To_Do_Application) [APK](https://github.com/mihir02badkur/To_Do_Application/blob/master/To-Do-List.apk)
- Ayushi Gupta - [To_.-Do_.-List04](https://github.com/ayushigupta931/To_.-Do_.-List04) [APK](https://github.com/ayushigupta931/To_.-Do_.-List04/blob/master/todo.apk)
- Raina Jain - [ToDo](https://github.com/RainaJain5/ToDo) [APK](https://github.com/RainaJain5/ToDo/blob/master/ToDo.apk)
- Puranjay Khanijo - [ToDoApp](https://github.com/puranjayK/ToDoApp) [APK](https://github.com/puranjayK/ToDoApp/blob/main/APK/ToDo.apk)
