# Week 1

## When you run into the exception `... this class is not key value coding-compliant for the key …` 
## what is the first thing to check?

### Check your oulet connections from storyboard to viewcontrollers. The error means that you have your storyboard is set up to expect an outlet called X but the actual outlet name is Y.
### If you delete the connection in the storyboard and reconnect to the right variable name, it should fix the problem.


## What is an outlet and when is it used?
### An outlet is a property of an object that references another object. The reference is archived through Interface Builder.
### It is used to create a reference to an UIElement.

## What is target-action and when is it used?
### Target-action is a design pattern in which an object holds the information necessary to send a message to another object
### when an event occurs. 
### The stored information consists of two items of data: an action selector, which identifies the method to be invoked, 
### and a target, which is the object to receive the message.
### The message sent when the event occurs is called an action message.
### `IBaction` is an implementation of it.

## What is cell recycling and why is it important?

## What is UITableViewDataSource and when do you use it?
