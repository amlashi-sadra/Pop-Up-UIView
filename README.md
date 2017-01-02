# Pop-Up-UIView
This is an example to a create Pop Up UIView in with Swift language

## 1st
Create a new view file (`.xib`), this is the PopUp View.

## 2nd 
Import the `popUpViewController.swift` from this repo into your project

## 3d
Assign the popUpView to your popUpView Controller:
- in the .xib file select the <b>File's Owner</b> (from righte side). then, in Custom Class of <I>Identity Inspector</I> tab, write popUpViewController.
- then from Outlets in <I>Connection Inspector</I>, Connect `view` to UIView of your .xib file 

## 4th
Now, you should make and instance of controller and handle the popUp after click or sth
- In your main ViewController (that controller you want to show popUpUIView), create an Instance of Controller:
```swift
    let popUpController = popUpViewController()
```

