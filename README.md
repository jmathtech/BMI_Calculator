# BMI_Calculator

A Python script that defines a class called BMIIndex that inherits from the customtkinter.CTk class. This class has several attributes and methods that are used to create a Body Mass Index (BMI) calculator.

The init method sets several instance variables and creates a Tkinter window with several frames and labels. The frames are used to organize the layout of the window and the labels are used to display text on the window.

The bmi_calculate method calculates the BMI by converting the user's height and weight from inches and pounds to meters and kilograms. The method also includes a try-except block to handle any ValueError that may occur when trying to convert the input to floats.

The display_bmi method is called when the user clicks the "Calculate" button. This method retrieves the user's height and weight from the entry widgets and calls the bmi_calculate method to compute the BMI. It also sets the text of label_right_03 to the calculated BMI.

The get_status method takes the BMI and returns a string describing the user's weight status based on their BMI.

The issue is that label_right_05 is not defined anywhere in the class, thus when the script is trying to reference it in the display_bmi method, it raises an attribute error.

## [ Video Demo ]
https://user-images.githubusercontent.com/36749450/214368450-0d30ab8d-46bc-436f-b3d4-8580cee71b3e.mp4

