
IN TERMINAL: copy paste


#Step 1: 
python3 -m venv myenv

#Step 2: 
source myenv/bin/activate

#Step 3: 
pip install spyder

#Step 4: 
pip install tk

#Step 5: 
spyder


After these steps there will be a app Spyder will be opened automatically

Step 6: RUN THIS IN THAT SPYDER , BY CREATING A NEW FILE TO CHECK THE TKINTER IS WORKING OR NOT.
''''

import tkinter as tk

def on_button_click():
    label.config(text="Button Clicked!")

root = tk.Tk()

root.title("Simple Tkinter Example")

label = tk.Label(root, text="Hello, Tkinter!")

label.pack(pady=10)

button = tk.Button(root, text="Click Me", command=on_button_click)

button.pack(pady=10)

root.mainloop()

AFTER RUNNING THIS A POP UP SCREEN WILL BE THERE {ONLY IF SUCCESSFUL}

IF SUCCESSFUL RUN  YOUR RESPECTIVE PROJECT TO CHECK WETHER IT IS WORKING PROPERLY


''''
Run this code in the spyder opening to check wether tkinter is working or not....

and mainly dont close the terminal window ,if closed it will not be working....
