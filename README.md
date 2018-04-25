# Angular-seed — the seed for this apps

This project is an application skeleton for a typical [AngularJS][angularjs] web app. You can use it
to quickly bootstrap your angular webapp projects and dev environment for these projects.

The seed contains a sample AngularJS application and is preconfigured to install the Angular
framework and a bunch of development and testing tools for instant web development gratification.

## Getting Started

To get you started you can simply clone the `DragAndDrop` repository and install the dependencies:


### Clone `DragAndDrop`

Clone the `DragAndDrop` repository using git:

```
git clone https://github.com/metko21neon/DragAndDrop.git
cd DragAndDrop
```

### Install Dependencies

To install dependencies simply do:

```
npm install
```

### Run the Application

We have preconfigured the project with a simple development web server. The simplest way to start
this server is:

```
npm start
```

Now browse to the app at [`localhost:8000/index.html`][local-app-url].

### What this program implement???

#### Part 1.

The program implement the dragndrop of items from one field to another and add the ability to return 
them back to the initial list. All items presented in the first field and they grouped in a multilevel
tree. 

Actions:
When user does dragndrop of an item from the initial list to basket: item deleted from the list 
	and appear in basket
User remove items from the basket and return back to the initial list
	
#### Part 2.

Capacity to submit the basket to the server side API. Also current basket content “valiidated” by API.

The server response for validation of the basket content can be positive or negative response to 
validation request:
If answer is positive, “Submit” becomes available.
If answer is negative, “Submit” remains unavailable.