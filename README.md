# Flash-Chat
<img width="459" alt="Screenshot 2024-09-16 at 7 32 35 PM" src="https://github.com/user-attachments/assets/2f0d4d17-4417-4be1-9b86-b024e3c939aa">

<img width="454" alt="Screenshot 2024-09-16 at 7 33 06 PM" src="https://github.com/user-attachments/assets/9c9de7cc-691c-4c10-a7eb-fbb1444e3cd7">
<img width="456" alt="Screenshot 2024-09-16 at 7 33 39 PM" src="https://github.com/user-attachments/assets/def2228d-1db8-4433-8aed-a80673d3b0f3">




## Our Goal

One of the most fundamental component of modern iOS apps is the Table View. Table Views are used everywhere from the Mail app to the Messages app. It’s a crucial part of every iOS developer’s tool belt. In this tutorial we’ll be getting to grips with Table Views, creating custom cells, and making our own cloud-based backend database. It’s going to be epic, so buckle up.

## What you will create

Flash Chat is an internet based messaging app similar to WhatsApp, the popular messaging app that was bought by Facebook for $22 billion. We will be using a service called Firebase Firestore as a backend database to store and retrieve our messages from the cloud. 

## What you will learn

* How to integrate third party libraries in your app using Cocoapods and Swift Package Manager.
* How to store data in the cloud using Firebase Firestore.
* How to query and sort the Firebase database.
* How to use Firebase for user authentication, registration and login.
* How to work with UITableViews and how to set their data sources and delegates.
* How to create custom views using .xib files to modify native design components.
* How to embed View Controllers in a Navigation Controller and understand the navigation stack.
* How to create a constants file and use static properties to store Strings and other constants.
* Learn about Swift loops and create animations using loops.
* Learn about the App Lifecycle and how to use viewWillAppear or viewWillDisappear.
* How to create direct Segues for navigation.


# Constants
```
struct K {
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"
    
    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }
    
    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}

