## Vispy GUI
This is a GUI created using PyQT5 and Vispy to visulaize and handle the file managements of all the files related to the vispy project.The whole is to embed the vispy canvas in the left frame of the PyQT5 GUI and add buttons to handle files and other works.
## Basic Layout



## Functionality 

* ADD button is a simply brows button(to search for files in your comp.) that adds the files in the
“models” folder of the project
* SELECT button opens the “models” folder in window 2 and each file inside the folder will be represented
by a radio button (so you can only click one).
* VIEW button will open the selected radio button file(from the SELECT btn) to view the vispy interface )
in window 1, such that it doesn’t create a new window. In window 2 we show the numbers for that file
as they appear in the console .
* VIEW btn should have a check button and when it is pressed the button will to the same as the
description above but with the: python run.py debug_full name.obj example
* RUN button will runs all the files inside the “models” folder and will output the results in the “result”
folder as it dose now (run.py file function calculate_all). In window 1 we see which files are finished as
we see now in the console by running python run.py
* STOP button will stop any process and will return everything in the initial state


## Work Screenshots 
