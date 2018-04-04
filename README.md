# drawify
The drawify app is a simple drawing app. The user moves his/her fingers to draw anything on the screen.

# Main.storyboard
The storyboard is a plain black screen with a white "clear" button at the the bottom of the screen.
The button when pressed clears the user's work and get the user back to the black screen.

# ViewController.swift
UIKit is used to make connections with the button and to load the black screen initially in this section
of the app.

# CanvasView.swift
This section of the app focuses on implementing the major functionalities of the app such as drawing on 
the canvas using the touchesBegan and touchesMoved function, the drawing layer function and a function
to clear the canvas when the clear button is pressed.
