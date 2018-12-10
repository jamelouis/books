# iOS Programming - the big nerd ranch

## Chapter 1 - A Simple iOS Application

* Interface Builder: document outline & canvas - open *.storyboard* file
* Interface Builder is an object editor that can create instances of objects and manipulate their properties.
* A .storyboard file is an archive of object instances to be loaded into memory when necessary.
* The *object library* contains the objects that you can add to a storyboard file to compose your interface.
* Auto Layout works by specifying position and size constrains for each view object in a scene.
* A *connection* lets one object know where another object is in memory so that the two objects can communicate.
* two kinds of connections: *outlets* and *actions*
* An *outlet* is a reference to an object.
* An *action* is a method that gets triggered by a button or some other view that the user can interact with, like a slider or a picker.
* View objects make up the UI, so developer typically create,configure,and connect view objects using *Interface Builder*.
* A *constant* is denoted with **let** keyword;its value cannot change.
* A *variable* is denoted with **var** keyword;its value is allowed to change.
* An *application icon* is a simple image that represents the application on th iOS Home screen.
* In general,there are two kinds of files in an application: code and resources.
* In *Asset Catalog*, you can manage all of the images that your application will need.
* An easy way to accomplish this is to allow Xcode to generate the possible launch screen images for you using a *launch screen file*.
* The *object library* contains the objects that you can add to a storyboard file to compose your interface.


## Chapter 2 - The Swift Language

* three basic type groups: structure,classes,and enumerations.
* "primitive" types such as Int,Float and Bool are all structures.
* An *optional* allows you to store either a value of a particular type or no value at all.
* A *playground* lets you write code and see the results without the overhead of manually running an application and checking the output.
* *type inference* is that the compiler infers theirs types from the initial values.
* Swift  provides three types with different levels of precision: Float for 32bit numbers, Double for 64-bit numbers,and Float80 for 80-bit numbers.
* three collections: *array*,*dictionaries*,and *sets*.
* swift types can be *optional*,which is indicated by appending ? to a type name.
* control flow statements: *if-else*,*while*,*for*,*for-in*,*repeat-while*,and *switch*.
* swift's *enumerated()* function returns a sequence of integers and values from its argument.
* swift switch cases do not fall through.
* swift enums can have raw values associated with their cases.

## Chapter 3 - View and View Hierarchy

* Every application has a single instance of *UIWindow* that serves as the contianer for all the views in the application.
* The Auto Layout system is based on the *alignment rectangle*.
* A *constraint* defines a specific relationship in a view hierarchy that can be used to determine a layout attribute for one or more views.
* The *nearest neighbor* is the closest sibling view in the specified direction.

## Chapter 4 - Text Input and Delegation

* *property observer* is a chunk of code that gets called whenever a property's value changes.
* Delegation is an object-oriented approach to **callback**.

## Chapter 5 - Tab bar items

* Each tab on the tab bar can display a title and an image, and each view controller maintains a tarBarItem property for this purpose.
* An *asset* is a set of files from which a single file will be selected at runtime based on the user's device configuration.
