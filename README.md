# 207-Image-Manager

For any future CSC207 students looking for some quick code off the web, don't do it. 

## Summary

A group project for course CSC207 Software Design (Fall 2017) at University of Toronto, St. George campus.

This is an Image tagging software written in Java using the Model-View-Controller design pattern.

This is the end result of the phase 2 deliverable.

## Functions

Users can:

<ul>
	<li>Select a root directory, and view an image from it, along with its absolute path
	<li>Add, view, edit and delete tag(s) on an image</li>
	<li>Manage the set of all tags, and any files affected by the change of tags</li>
	<li>Change image file name and move its location</li>
	<li>View and revert to older image file names for a current image</li>
	<li>Display a log of all actions made since first launch</li>
</ul>

All changes, tags and history persist through a quit and restart.

## Built With

* [IntelliJ](https://www.jetbrains.com/idea/) - The editor used
* [JavaFX Scene Builder](https://www.oracle.com/technetwork/java/javase/downloads/javafxscenebuilder-info-2157684.html) - Front end layout

## Versioning

We use Git for versioning with University of Toronto's MarkUs repository for the course.

## Authors

Xingyu Wang (wangx482):
<ul>
    <li>Back-end for Model package.
    <li>Implemented moving and tagging system.
    <li>Collaborated with Qiqi writing JavaDocs and UML diagram.
	<li>Bug fixing in various methods in Model package
	<li>Writing ImageManagerTest and TagManagerTest and their JavaDocs
	<li>Created .gitignore file
</ul>

Xueqing Yang (yangxu19):
<ul>
    <li>Front-end for Controller package.
    <li>Classes: Controller.java, sample.fxml, RenameController.java, Rename.fxml
    <li>Some methods in ImageViewController.java and ImageView.fxml
    <li>Bug fixing in all classes in Controller package
</ul>

Wen Li (liwen21):
<ul>
    <li>Front-end for Controller package.
    <li>Classes: TagsView.java, TagsView.fxml
    <li>Some methods in ImageViewController.java and ImageView.fxml
    <li>Bug fixing in all classes in Controller package
</ul>

Qiqi Xu(xuqiqi);
<ul>
    <li>Back-end for Model and Utility package.
    <li>Explored design patterns. Implemented TagManager, FileManager and ImageManager
    <li>Implemented renaming and logging system.
    <li>Collaborated with Xingyu writing JavaDocs and UML diagram.
    <li>Fixed bugs in all classes in Model and Utility.
</ul>

