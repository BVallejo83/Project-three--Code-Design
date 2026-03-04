# Project-three--Code-Design
# Inventory Tracker (Android)



**Course:** CS-360 Mobile Architecture & Programming  

**Student:** Benjamin Vallejo  

**Project:** Inventory Tracker Application  



## Overview

Inventory Tracker is an Android mobile application that allows users to securely register, log in, and manage inventory items. The app uses a local **SQLite** database for persistent storage and follows Android best practices for activity navigation, data handling, and input validation.



## Features

- User registration with username/password validation  

- User login authentication  

- Local data storage using SQLite  

- Add, edit, and delete inventory items  

- Inventory list displayed using RecyclerView  

- Input validation and basic error handling  

- Clean, modular Java code structure  



## Tech Stack

- Android Studio  

- Java  

- Android SDK  

- SQLite  

- Android Emulator (for testing)  



## Security Notes

- User credentials are stored locally using SQLite.

- Input validation helps prevent empty or duplicate usernames.

- Future improvements could include credential encryption and/or remote authentication.



## How to Run

1. Clone or download this repository.

2. Open the project in **Android Studio**.

3. Let Gradle sync/finish.

4. Run the app on an **Android Emulator** or a physical Android device.



## Future Enhancements

- Encrypt stored credentials (or use Android Keystore + hashing)

- Add cloud sync / remote authentication

- Improve UI/UX (sorting, search, categories)

- Add export/import for inventory data



## Conclusion

This project implements authentication
