# CS-360-Portfolio
# Weight Tracking App

## **Requirements & User Needs**
The goal of this app was to provide an easy way for users to track their weight progress. The app needed to:
- Allow users to create an account and log in.
- Store weight entries in a database.
- Let users set and update their goal weight.
- Display weight data in a clear, user-friendly UI.
- Send an SMS notification when the user reaches their goal weight.

## **UI Design & User-Centered Features**
The app includes the following screens:
- Login Screen – Users can create an account and log in.
- Weight Tracking Screen – Shows weight entries, allows adding new ones, and setting goals.
- SMS Permission Screen – Lets users enable SMS notifications and input their phone number.

The UI was designed to be simple and functional, making sure users could easily enter their weight and see progress. The goal weight is always visible, so users know what they’re working toward.

## **Approach to Coding**
I broke the development process into small, testable steps. First, I set up the database to handle user accounts and weight entries. Then, I built out the UI and user interactions, making sure the app could store and retrieve data properly. Finally, I added the SMS feature, ensuring users got notified when they reached their goal.

## **Testing & Debugging**
I tested the app using the Android Emulator and manually tried different scenarios:
- Creating and switching between users.
- Adding weight entries and making sure they saved correctly.
- Checking that the goal weight notification triggered properly.
- Ensuring the app didn’t break if SMS permissions were denied.

## **Challenges & Innovations**
One tricky part was making sure each user’s data was separate, especially the goal weight and SMS permissions. Originally, the app was applying the same goal weight to all users, so I had to store user-specific goal weights in SharedPreferences with a unique key.

## **Biggest Success**
I think the goal weight tracking and SMS notification system was the best part. It works smoothly, and users can easily set a goal and be reminded when they hit it. It took some extra effort to get it working per user, but I got it working in the end.
