# Virtual-News-Paper

# About 

Virtual News Paper is an iOS mobile application integrated with Augmented Reality technology. This mobile application converts a two-dimensional static newspaper into three-dimensional virtual paper with ultimate visualisation in AR.

## Clips 
<img src="https://github.com/Kedar-Pandya/Pairing/assets/64677824/21420cf1-5253-4f45-89c9-a539e15b2a45" height ="448" width = "207">


## Demonstration of an AR Feature

https://github.com/Kedar-Pandya/Virtual-News-Paper/assets/64677824/0c073aec-9a62-4e4e-88fd-9ef876cdc9c6

https://github.com/Kedar-Pandya/Virtual-News-Paper/assets/64677824/89aa49ad-3df3-4152-9319-4c5ec9c8a9df

## Design Pattern

An architectural pattern is a reusable solution that will reuse many times to manage a single operation in a project. Design pattern makes the code in structure and organized format. All the development types contain complexity in their development, and to manage that complexity developers follow the design pattern. Which makes the project a proper structure and reduces the level of code complexity.

In this project I used the most fundamental design pattern MVC, MVC stands for the model-view-controller. MVC design pattern is split into three major components model, view, and controller. While these three components work together the MVC design pattern generates. In the MVC design pattern, a model is responsible to handle all the data and logical part of the code, view is accountable for all user interaction and deal with user interfaces. In the end, the controller works as a mediator between the view and the model.

![MVC](https://github.com/Kedar-Pandya/Virtual-News-Paper/assets/64677824/2df8f3ef-8dcf-4fdf-a77d-1795f25cd399)


Simply explain this process. View handles all the user interaction in software, when the user interacts with the system it generates requests and send them to the controller. The controller interprets the view’s request and make a new request to the model. The model processes the request and applies the logic, after processing the request model prepared data, and sends it to the controller. The controller interprets the data output and modifies it according to the request of view. After modification, data send to the view and the view performs appropriate UI changes.

In the MVC the model and view never interact with each other, they make interaction with the help of the controller. In this mobile application, the utilities, and constant Swift files work as a model. The utility class handles the entire navigation process of the application. On the other hand, constants check the text fields with given formats, design the text fields, handle the keyboard appearance in a signup screen, and manage a custom toast message feature in forgot password screen. The view component of this project is in the main storyboard, and view controllers work as controller components of MVC.

