# Grocery-App-Documentation V2
Grocery App an online grocery shop CMS. Grocery smart grocery shopping List is a free app that improves the quality of your grocery shopping by making it easier, faster, and most importantly smarter. It is all you would want out of a shopping list and more.  

## Required Software

1. Install Node.js https://nodejs.org
2. Xcode (If You Want Build iOS)
3. Android Studio and SDK ( For Android )
4. VS Code Editor
5. Xammp

## What Included 

1. Documentation
2. Client App
3. Delivery Boy App
3. Store Manager App
4. Backend

# Setup Backend

1. Extract Backend to C->Xammp->htdocs
2. Open PhpMyAdmin, Create New Database
3. Click on Import Tab and Import database File
4. Open htdocs Folder 
5. Go-to Admin->Included->config.php
6. Add Database Credential Which You Created Previous
7. Save

8. Goto Htdocs app->Config.php
9. Add Database Credential Which You Created Previous
10. Save

## Setup Client APP 

1. Extract Client App To Some Folder
2. Make Sure Node.js Install
3. Open CMD and Navigate to Client App Directory
4. Type 'npm install'
5. After Completion 'npm install @ionic/app-scripts@latest --save-dev'
6. Next 'Ionic Serve'

7. Open Client App files into Any Editor
8. Goto src->providers->hkproviders.ts
9. Setup Api End Connection Here and Also Setup Token etc.

Like 'localhost/grocery'

10. Save and Check in Browser.

## Setup Delivery Boy APP 

1. Extract Delivery Boy App To Some Folder
2. Make Sure Node.js Install
3. Open CMD and Navigate to Delivery boy App Directory
4. Type 'npm install'
5. After Completion 'npm install @ionic/app-scripts@latest --save-dev'
6. Next 'Ionic Serve'

7. Open Client App files into Any Editor
8. Goto src->providers->auth.ts
9. Setup Api End Connection Here.

Like 'localhost/grocery/app'

10. Save and Check in Browser.

## Setup Store Manager APP 

1. Extract Store ManagerApp To Some Folder
2. Make Sure Node.js Install
3. Open CMD and Navigate to Store Mangaer App Directory
4. Type 'npm install'
5. After Completion 'npm install @ionic/app-scripts@latest --save-dev'
6. Next 'Ionic Serve'

7. Open Client App files into Any Editor
8. Goto src->providers->auth.ts
9. Setup Api End Connection Here.

Like 'localhost/grocery/app'

10. Save and Check in Browser.

## Build Apk For Android

1. Make Sure Enviornment Setup Properly

https://medium.com/@hubfly/how-to-build-ionic-app-in-android-step-by-step-31068d885d24

2. Navigate To App Directory using CMD
3. Type 'ionic cordova platform add android'
4. Type 'ionic cordova build android or ionic cordova run android'
5. navigate to build directory and check apk.

## Build for iOS

1. Make Sure You have iOS Enviorment (Macbook)
2. Install Xcode from App Store
3. Install Node.js also on Mac.
4. Navigate to Project Directory using Terminal.
5. Type 'npm Install'
6. Type 'sudo ionic cordova platform add ios'
7. Type 'sudo ionic cordova build ios'
8. Open platform/ios folder.
9. There is One Xode Project File.
10. Open Using Xcode.
11. Just Build and Run.
12. App Open In Iphone Simulator.


## Where to Change Logo

1. Navigate to www/assets/imgs for app
2. Replace Logo File (256px x 256px)

## Change App Name

1. Go To www/assets/i18n for app
2. Replace String 'appname' to Your Name



