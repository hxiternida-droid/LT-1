# LT-1

# How to Run
1. Open the program file
2. Run the program
3. Enter the value for number of notebooks.
# Input
number of notebooks
how many fit in one box
# Output
number of boxes filled
number of loose notebooks
# Author
Hailey Xhian I. Ternida 
8-Sampaguita

[Ternida_Hailey_LT1.py](https://github.com/user-attachments/files/31128089/Ternida_Hailey_LT1.py)
#Ask for the total number of notebooks and how many fit in one box.

notebook_w = input(str("What is the total number of notebooks? "))
box_w = input(str("How many notebooks can fit in one box? "))

notebook_w = round(notebook_w, 0)
box_w = round(box_w, 0)



#Display the number of full boxes and the number of loose notebooks left over.

full_box = int(notebook_w // box_w)
loose_nb = int(notebook_w % box_w)

if notebook >= box:
    print (f"The number of full boxes are {full_box}.")
    print (f"The number of loose notebooks left over are {loose_nb}.")
else:
    print ("No full box was filled.")
