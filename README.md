# CEG4110-HW1

## Description
This is an application built in android studio. It contains one UI that takes user input text and the text color is randomly changed with the press of a button. The red, green, and blues values for the random color are displayed as well as the html value for the specific color. The application also contains a second UI that is a simple painting canvas. The user can draw on the screen in any color selected from a color picker. The image can be saved in png or jpeg.

## Operation
The opening UI shows an application with two tabs. The app will already be on the first tab which contains the input text randomizer. The user can type a short message into the text field and then press the "change color" button to randomize its text color. 

![](tylerpalcic/CEG4110-HW1/hw1_part1_scrsht.png)

Selecting tab 2 at the top of the screen will move the user to a new screen containing the painting canvas. The user can then draw on the screen in black or select the color button to create any color from the entire color spectrum. The drawing can be erased to start over if the user doesn't like their drawing by tapping the "clear canvas" button or they can save the drawing by tapping the "save" button.

## External Libraries
A color picker library is used for the drawing canvas in tab 2 which can be found here:

https://github.com/Pes8/android-material-color-picker-dialog?utm_source=android-arsenal.com&utm_medium=referral&utm_campaign=5609

You may have to add some packaging options to the build.gradle inorder for the project to build once this color picker has been implemented. The ones that I added are here:

 packagingOptions {
        pickFirst 'lib/armeabi-v7a/libassmidi.so'
        pickFirst 'lib/x86/libassmidi.so'
    }
    
    
