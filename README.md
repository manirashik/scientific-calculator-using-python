# scientific-calculator-using-python
n this project, we build up the scientific calculator using the tkinter library of Python. It is the standard GUI library for Python. With its help, we prepared the GUI for the project, and to add the functionalities of the scientific calculator, we used a math module. 
The first step is importing all the necessary libraries using the “import” keyword. For the latest version, the tkinter module comes under the future module. So first, we have to install the future module with the help of the command “pip install <module-name>”. The future module is a built-in module in Python that inherits new features which is available in the latest Python versions. With “future. moves” we will import the tkinter module.

In the next step, to create an object of the tkinter frame will use “.Tk()”.With this, we will also set the title and geometry of our tkinter application. To set the background color for the project we will use “.config(bg=<color name>)”. And so, with that, we have set black as the background color for this project.

We will also add an image by the corner to give it a creative aspect. With the help of “.PhotoImage(file=<filename>)”, we will load the picture, by using the “.Label()” we will make the label widget for this, and “.grid(row=,column= )” will help to get it placed well on the window.

While working on this project, we need to fulfill three aspects.

Space for the calculation
Buttons for the calculation
Adding the functionalities
Talking about the first aspect, we will create an entry widget by “.Entry()”. Under this, we have provided the parameter such as

root – window object

font – The font style in which we want the information to get entered

bg – Stating the background color for the space

fg – Stating the color of the text appeared

bd – Border of the entry widget

width – width of the entry widget

Finally, with the help of “.grid()” we will set the position for the entry widget.
