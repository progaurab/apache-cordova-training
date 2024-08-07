## [Learn Apache Cordova - Build Mobile Apps for Android & iOS](https://www.udemy.com/course/apache-cordova-bootcamp/?referralCode=2F36C29350E4E5A09405)
This is the repository for the course "Learn Apache Cordova - Build Mobile Apps for Android & iOS" available on Instill Learning and Udemy. 

The full course is available from 
- [Udemy](https://www.udemy.com/course/apache-cordova-bootcamp/?referralCode=2F36C29350E4E5A09405) - Video Course
(https://www.udemy.com/course/draft/6068183/?referralCode=2F36C29350E4E5A09405)
- [Instill Learning](https://www.instilllearning.com/courses/apache-cordova) - Live Training + Video Course + Hands-on Real World Projects (https://www.instilllearning.com/courses/apache-cordova)
![Apache Cordova](images/instilllearning-apachecordova.png)

## What is Apache Cordova? 
[Apache Cordova](https://www.instilllearning.com/courses/apache-cordova) is an open-source mobile development framework. It allows you to use standard web technologies such as HTML5, CSS3, and JavaScript for cross-platform development, avoiding each mobile platform's native development language. Applications execute within wrappers targeted to each platform, and rely on standards-compliant API bindings to access each device's sensors, data, and network status."

## Learning Objectives
* How to create and build (compile and package) a Cordova project using the CLI (Command Line Interface).
* How to use several Cordova APIs such as Geolocation, Contacts, and Camera.
* How to handle specific mobile challenges such as touch events, scrolling, styling, page transitions, etc.
* To publish the app on Google Play Store & App Store

## Software - version[ Last Updated on August 2024]:
* [Node - v22.5.0](https://nodejs.org/en/download/package-manager) 
* npm - 10.8.2 
* [JDK - Microsoft Build of OpenJDK 11.0.23 LTS](https://learn.microsoft.com/en-in/java/openjdk/download#openjdk-11)
* Apache cordova - 11.0.0
* cordova-android - 10.1.1
* cordova-ios - 6.2.0
* Gradle - 7.4

## Instructions
This repository has only master branch containing all examples. You can fork, star and clone the repository and go to individual example's root folder and run it.

#### Step 1: Go to https://github.com and login with your email.
#### Step 2: Go to the Apache Cordova Repository: https://github.com/progaurab/apache-cordova-training-instilllearning
#### Step 3: Click on 1) Watch - All Activity 2) Star 3) Fork  the repository (See instruction below)
![Fork the Repo](images/fork-repo.png)

#### Step 4: 
```javascript
$ git clone https://github.com/progaurab/apache-cordova-training-instilllearning.git
$ cd apache-cordova-training-instilllearning
$ cd ex01-cordova-calculator
```
#### Step 5: To install Cordova (ignore if installed already)
```javascript
$ npm install -g cordova
```
#### Step 6:
```javascript
$ cordova platform add browser
$ cordova run browser
```
#### Open Android App in Android Studio and Run
![ex01-cordova-calculator](images/ex01-cordova-calculator.png)
## Other usefull commands
#### Create new cordova application
```
$ cordova create ex01-cordova-calculator com.instilllearning.ex01 ILCalculator 
$ cd ex01-cordova-calculator
```
##### Add other platform
```
$ cordova platform add android
$ cordova platform add ios
```
##### Modify Code and Distribute to all platform
```
$ cordova prepare
```

##### Check the cordova requirements
``` 
$ cordova requirements
```

##### Ganerate Android APK
```
$ cordova build android
```

##### xcode - Installing the Requirements (for Mac)
```
$ xcode-select --install
```

##### Deployment Tools allow you to launch iOS apps on an iOS Device from the command-line.
```
$ brew install ios-deploy
```

##### CocoaPods tools is needed to build iOS apps.
```
$ sudo gem install cocoapods
```

##### Deploying to Simulator - Open ios project in XCode
open ./platforms/ios/ProjectName.xcworkspace/
for example,
```
$ open ./platforms/ios/Ex1-Cordova-Question-Answer.xcworkspace 
```
Create a new cordova app
cordova create [project_name] [package_name] [app_name]
[project_name]:     ex1-cordova-question-answer
[package_name]:     dev.instilllearning.ex1
[App Name]:         Ex1-Cordova-Question-Answer

```
$ cordova create ex1-cordova-question-answer dev.instilllearning.ex1 Ex1-Cordova-Question-Answer
```

## Instructor
[Gaurab Kumar](https://www.linkedin.com/in/progaurab)

## Course Offer
Use this link to get upto 95% discount on my courses on [Udemy](https://www.udemy.com/course/apache-cordova-bootcamp/?referralCode=2F36C29350E4E5A09405):
***Purchases any two courses and get other courses free***, To get free courses coupon write mail to [courses@instilllearning.com](courses@instilllearning.com)
* [Learn Apache Cordova - Build Mobile Apps for Android & iOS](https://www.udemy.com/course/apache-cordova-bootcamp/?referralCode=2F36C29350E4E5A09405)


