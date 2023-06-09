# Swift Resources!
Compiled list of resources to help familiarize users with IOS Development

- [Table of Contents](#table-of-contents)
	- [Learning Resources](#Learning-Resources)
	- [Tools](#Tools)
	- [Frameworks](#Frameworks)
 	- [News](#News)
 	- [FAQ](#FAQ)
  

Add a list with below format.
* **[]()**
  
### **Learning Resources**

**SwiftUI 2.0 Cheat Sheet**
* **[https://github.com/SimpleBoilerplates/SwiftUI-Cheat-Sheet](https://github.com/SimpleBoilerplates/SwiftUI-Cheat-Sheet)**

**Hacking with Swift**
* **[https://www.hackingwithswift.com/100/swiftui](https://www.hackingwithswift.com/100/swiftui)**
* **[https://www.hackingwithswift.com/articles/242/learn-essential-swift-in-one-hour
](https://www.hackingwithswift.com/articles/242/learn-essential-swift-in-one-hour)**

**NavigationPath Swift**
* **[https://developer.apple.com/documentation/swiftui/navigationpath](https://developer.apple.com/documentation/swiftui/navigationpath)**

**Swift On Tap**
* **[https://swiftontap.com/](https://swiftontap.com/)**

**Combine vs Async/Await**
* **[https://peterfriese.dev/posts/combine-vs-async/](https://peterfriese.dev/posts/combine-vs-async/)**

**Deep Linking**
* **[https://jacobzivandesign.com/technology/deep-linking-in-swift-ui/](https://jacobzivandesign.com/technology/deep-linking-in-swift-ui/)**
* **[https://blogs.halodoc.io/deep-linking-using-url-scheme-in-ios/](https://blogs.halodoc.io/deep-linking-using-url-scheme-in-ios/)**


**Tools for accelerating iOS development**
* **[https://blog.bredvid.no/tools-for-accelerating-ios-development-c3c87087e9f6](https://blog.bredvid.no/tools-for-accelerating-ios-development-c3c87087e9f6)**


**Swift UI Introduction by Apple**
* **[https://developer.apple.com/tutorials/swiftui](https://developer.apple.com/tutorials/swiftui)**


### **Tools**

**Symbols library for icons for apple platform**
* **[https://developer.apple.com/sf-symbols/](https://developer.apple.com/sf-symbols/)**

**Vapor Database built for swift **
* **[https://vapor.codes/](https://vapor.codes/)**

**Highcharts that dynamically change **
* **[https://github.com/highcharts/highcharts](https://github.com/highcharts/highcharts)**

**Realm Database thats super fast on mobile **
* **[https://realm.io/](https://realm.io/)**

**CryptoSwift is a growing collection of standard and secure cryptographic algorithms implemented in Swift**
* **[https://cryptoswift.io/](https://cryptoswift.io/)**



### **Frameworks**

### **News**

### **FAQ**
Where can I see my project directory in Xcode?

To see your project directory in Xcode, you can follow these steps:

Open Xcode and open your project.
Use the "Show in Finder" option to open the project directory in Finder. 
-To do this, right-click on your project's name in the Project navigator and select "Show in Finder" from the contextual menu.
-Select get info to see full directory path under "where"

------------------
what is *.pbxproj merge = union
Tells Git that whenever there is a merge conflict Git should merge automatically and take both sides of the conflict. 

------------------
What is a podfile.lock

Podfile. lock is used to make sure that every members of the team has the same versions of pods installed on the project. This file is generated after you run the command: pod install. It gets updated when you run pod install or pod update. lock file should not be deleted if we work on team. And so Podfile. lock file should be checked while using source control. Everyone should take care while hitting command pod install and pod update.

------------------

What is a .xcodeproj vs .xcodeworkspace

In Xcode, a .xcodeproj file is a project file that contains all the settings, resources, and source code for a single project. It's used to organize your project and contains all the information needed to build the project, including build settings, targets, and files.

On the other hand, a .xcworkspace file is a workspace file that can contain one or more .xcodeproj files, as well as other files and resources. It's used to manage multiple projects that work together, such as a project that includes multiple dependencies or sub-projects. The workspace provides a way to build and test all the projects together, as well as manage their dependencies.

When you open a .xcodeproj file in Xcode, you're working with a single project. When you open a .xcworkspace file, you have access to all the projects included in the workspace. You can switch between projects, view all their files in a single window, and build and test them together.

------------------



