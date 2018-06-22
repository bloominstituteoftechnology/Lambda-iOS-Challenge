# Lambda iOS Challenge

If you have not yet filled out the form at https://lambdaschool.com/ios-challenge/ please do that before submitting your pull request.

In order to remove even more barriers for those that want to participate in Lambda School, we've created the Lambda Challenge. Based on our data, we are confident that if you can complete the Lambda Challenge, we can help you learn to code, and get a job as an iOS developer. This test enables you to bypass the regular precourse work. 

If the questions in here are too difficult then you can begin working through our regular precourse work which covers the fundamentals [here](https://lambdaschool.com/courses/cs/ios/101/).

You should also complete an application for our iOS course if you have not already done so. Apply [here](https://lambdaschool.com/courses/cs/ios/full-time/apply/).

## Prerequisites

You will need to have a Mac with at least the following minimum specs:

- SSD (or Fusion Drive) 
- 8 GB of RAM
- macOS High Sierra 10.13.

These computers should basically qualify:
MacBook (Air, Pro, or standard) 2012 or later with SSD and 8 GB of RAM or higher.
iMac or Mac mini with Fusion Drive or SSD.

You need to download Xcode from the Mac App Store.

In order to complete this challenge you will need a basic understanding of the following concepts:

```
Swift
  constants and variables
  types such as String, Int, Bool, etc.
  conditionals
  optionals
  loops
  functions
  collections

Xcode
  Familiar with navigating through Xcode
  Interface Builder
  IBActions/IBOutlets
  UITableView
  Segues
```

## Overview

This challenge is broken down into two parts:

- First, there is a Classroom on repl.it that you will need to join. This Classroom has "assignments" for you to complete. repl.it is like an online Swift Playground. There are instructions given for each assignment on the website.
- Second, you will make an Xcode project that will demonstrate your understanding of Xcode, Interface Builder, and implementing a basic `UITableView`.

## Part 1 - Classroom Assignments

Join the iOS 101 Assessment Classroom [here](https://repl.it/classroom/invite/V4Um9xs). If you have never used repl.it before, you will need to sign up for a free account.

You will then see a list of assignments. Please complete them in order (1.1, 1.2, 1.3, 2.1, etc.). As stated before, repl.it works like an online Swift Playground. You are able to write and run code on there directly. It will also test your code to make sure it works. The tests can be somewhat finnicky, so the instructions may tell you to do something like print a variable or function in order for the tests to test your code correctly. **Please be sure to read all of the instructions.**

Once you have finished all the assignments in the Classroom, refer yourself back to this as the following section will have the instructions for the Xcode project.

## Part 2 - Xcode Project

The Xcode project portion of the challenge is to make a very simple app that shows a list of places you have visited and when you last visited them. It should look close to this (don't worry about making it look exactly like the following screenshots):

![Challenge Example](https://user-images.githubusercontent.com/16965587/41250991-c4be95e2-6d75-11e8-8456-5a8ef24f1047.gif)

This project should meet the following requirements:
- Use Interface Builder to create a master-detail interface with a `UITableViewController` as the master view controller and a normal `UIViewController` as the detail view controller. There should also be a way to go back to the master list view from the detail view controller.
- A data source for your table view. This should be an array of dictionaries. Each dictionary should have a single key-value pair. The key should be the name of the place you visited, and the value should be the time you visited (e.g. "2018", "June 2015", etc.)
- When tapping on a cell that represents a place you have gone, it should segue to the detail view controller. 
- The detail view controller's title should be the name of the place you are viewing.
- The detail view controller should have a label that shows the last time you visited that place. By default, this label should be hidden. 
- The detail view controller should also have a button that allows for the label to hide/unhide when it is tapped.

## Finishing Up

Once you have completed both parts of the challenge please zip (compress) your project up. If you need help zipping your project, read the article linked in the Resources section below.

If you have gone through the iOS 101 course, send it to your Project Manager through Slack. If you are testing out of the iOS 101 course, send it to Andrew Madsen through Slack. Simply open a direct message chat with the correct person, then drag the zipped project up, and click the "Upload" button.

Once we have verified that your repl.it assignments and the Xcode project you send meet the requirements outlined above, we will send you an email to schedule an interview.

## Resources

[The Swift Programming Language Guide](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html) - Has many pages on specific topics such as Strings, collections, functions, etc. The menu on the left will help you navigate to what you might need.

[Interface Builder - Xcode Help](https://help.apple.com/xcode/mac/8.0/#/dev31645f17f) - Everything within the section titled "Lay out user interfaces" on the left menu

[How to Zip Files](http://osxdaily.com/2012/01/10/how-to-zip-files-in-mac-os-x/) - You should zip the very topmost folder of your Xcode project. (Zip the folder that contains the .xcodeproj file)
