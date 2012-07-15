#Sample Code#

##PrintWebView##

PrintWebView demonstrates how to print the content displayed by a UIWebView object using the UIViewPrintFormatter class. This sample application is a primitive web browser with printing capability.

[URL](https://developer.apple.com/library/ios/samplecode/PrintWebView/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010311) 

Updated: 2012-06-04

##CoreBluetooth Temperature Sensor##

A simple iOS iPhone application that demonstrates how to use the CoreBluetooth Framework to connect to a Bluetooth LE peripheral and read, write and be notified of changes to the characteristics of the peripheral.

The sample follows setting up the Central Manager, scanning for peripherals that show particular services, connecting to found peripherals, reading values from characteristics, registering for notifications from characteristics and writing to characteristics.

The service presented is a Temperature sensor that sends alert notifications when the temperature crosses a high or low threshold that can be set by the user.

[URL](https://developer.apple.com/library/ios/samplecode/TemperatureSensor/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012194)

Updated: 2012-04-11

##ViewTransitions##

The ViewTransitions sample application demonstrates how to perform transitions between two views using UIView's transitionFromView API.

[URL](https://developer.apple.com/library/ios/samplecode/ViewTransitions/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007411)

Updated: 2012-03-27

##UICatalog##
This sample is a catalog exhibiting many views and controls in the UIKit framework, along with their various properties and styles.

If you need code to create specific UI controls or views, refer to this sample and it should give you a good head start in building your user interface. In most cases you can simply copy and paste the code snippets you need.

When images or custom views are used, accessibility code has been added. Using the iPhone Accessibility API enhances the user experience of VoiceOver users.

[URL](https://developer.apple.com/library/ios/#samplecode/UICatalog/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007710)

Updated: 2011-10-12

##SimpleDrillDown##

This application shows how to create a basic drill down interface.

The first scene shows a list of plays. When the user selects a play, the application displays a second scene that shows a list of the main characters and other data about the play. Both screens use a table view. The first list is in the "plain" style to show a standard list; the second is in the grouped style that you can use to lay out detail information.

The transition from the first scene to the second is defined by a segue associated with the prototype table view cell in the table view controller's table view. In the storyboard, the segue is named, "ShowSelectedPlay". The name is used as the idetifier in RootViewController's prepareForSegue:sender: method.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleDrillDown/Introduction/Intro.html#//apple_ref/doc/uid/DTS40007416)

Updated: 2012-02-28

##Tabster##

An eclectic-style application designed to show how to build a tab-bar based iPhone application.

An iPhone sample app that takes the "Tab Bar Application" Xcode template a few steps further by going over useful topics in implementing a UITabBarController in your application.

[URL](https://developer.apple.com/library/ios/#samplecode/Tabster/Introduction/Intro.html#//apple_ref/doc/uid/DTS40011213)

Updated: 2012-03-09

##SimpleTextInput##

SimpleTextInput is a simple text-editing application that demonstrates customized text display and text input handling using Core Text and UIKit Text Input protocols.

[URL](https://developer.apple.com/library/ios/#samplecode/SimpleTextInput/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010633)

Updated: 2011-01-19

##DocInteraction##

Demonstrates how to use UIDocumentInteractionController to obtain information about documents and how to preview them. There are two ways to preview documents: one is to use UIDocumentInteractionController's preview API, the other is directly use QLPreviewController. This sample also demonstrates the use of UIFileSharingEnabled feature so you can upload documents to the application using iTunes and then to preview them. With the help of "kqueue" kernel event notifications, the sample monitors the contents of the Documents folder.

[URL](https://developer.apple.com/library/ios/#samplecode/DocInteraction/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010052)

Updated: 2012-02-13

##International Mountains##

Drawing from the existing Cocoa Internationalization Mountains sample, this sample shows how to integrate, design and programmatically access localized resources and data in an iPhone application. This sample uses multiple localized views, localized formatted strings, localized application data, localized info.plist strings, and a localized application preferences settings bundle. The sample is localized in three languages: English, French, and Traditional Chinese.

[URL](https://developer.apple.com/library/ios/#samplecode/InternationalMountains/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008756)

Updated: 2010-06-17

##CoreDataBooks##

This sample illustrates a number of aspects of working with the Core Data framework with an iPhone application:

* Use of an instance of NSFetchedResultsController object to manage a collection of objects to be displayed in a table view. 
* Undo and redo.
* Database initialization. 
* Use of a second (child) managed object context to isolate changes during an add operation.

[URL](http://developer.apple.com/library/prerelease/ios/#samplecode/CoreDataBooks/Introduction/Intro.html#//apple_ref/doc/uid/DTS40008405)

Updated: 2012-04-04

##Core Data Utility##

This sample contains the complete source code to the Core Data Utility Tutorial.

The sample illustrates how you can create a command-line utility that uses Core Data. It shows how to perform basic tasks required in a Core Data application: 

* Creation of a Core Data stack -- a persistent store, a persistent store coordinator (including the managed object model), and a managed object context. 
* Creation and initialization of a managed object. 
* Committing changes to the store by saving a context. 
* Creating a fetch request and retrieving managed objects.

[URL](http://developer.apple.com/library/prerelease/ios/#samplecode/CoreDataUtility/Introduction/Intro.html#//apple_ref/doc/uid/DTS40012164)

Updated: 2012-04-04

#PhotosByLocation#

Demonstrates how to use the AssetsLibrary APIs to provide a custom image picking UI. The user experience is centered around the idea of using the assets location and time metadata as a basis for certain features.

[URL](https://developer.apple.com/library/ios/#samplecode/PhotosByLocation/Introduction/Intro.html#//apple_ref/doc/uid/DTS40010136)

Updated: 2012-07-10

#QuickContacts#

QuickContacts demonstrates how to use the Address Book UI controllers and various properties such as displayedProperties, allowsAddingToAddressBook, and displayPerson. It shows how to browse a list of Address Book contacts, display and edit a contact record, create a new contact record, and update a partial contact record.

[URL](https://developer.apple.com/library/ios/#samplecode/QuickContacts/Introduction/Intro.html#//apple_ref/doc/uid/DTS40009475)

Updated: 2010-06-25