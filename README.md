# SplitIt

Add a tip to any bill and split it between the party.

<img width="537" alt="Screenshot 2022-06-10 at 15 23 56" src="https://user-images.githubusercontent.com/91250039/173074474-f15e79f7-53a6-44d9-9b93-0ccfd34ff796.png">

SKILLS LEARNT:

 - IBOutlet: Created IBOutlets to access the properties of the tip % buttons, text field and the slit between number.
 - IBAction: Created a collection of IBAction for all the tip % buttons, to execute code when either of them are tapped and a action for the UIStepper for    when the split number changes.
 - Cocoa Touch Class: Made a new view controller that is a subclass of UIViewController, by using Cocoa Touch Class and linked it to the new view              controller on storyboards.
 - .isSelected: To highlight which ever button is last selected.
 - .dropLast: To get rid of the last character(%), therefore turning the button title into a number to be used on the culculation.
 - Converting Data Type: Used the Double() initializer to turn String into Double for the calculation.
 - String formatter: "%.0f" format for the split label when the stepper is adjusted.
 - Present Modally: Created a segue between the Calculator View Controller and the Result View Controller to be triggered when the Calculate button is        tapped, and passed the result of the calculation to the Result View Controller to display. 
 - Dismiss View Controller: .dismiss when Recalculate is tapped to dismiss the view controller and return to the previous view controller.
