# Department Store Management System(DSMS) using C++

A Department Store Management System (DSMS) in C++ is a software tool used to manage the inventory and sales of items in a department store. In this article, we will be discussing the implementation of a DSMS on a command-line user interface using C++. The system allows various features to admin such as add, view, update, and delete items in the store.

Add: In this function, it prompts the user for the Item Code, Item name, Company Name, and No. of item. After that, the program asks ‘Do you want to Add Another Item(y/n)’ to which the user has to reply yes or no.

View: Displays information for all items in the store.

Update: The program asks to enter the Item code and it identifies the product after that we can change the details such as  Item Code, Item name, Company Name, and No. of items in the store.

Delete: The program asks to enter the Item code and then it deletes the item. If the user enters an invalid command, an error message is displayed. 

## Approach:

The approach taken in the above code for the Department Store Management System (DSMS) is as follows:

The class dept contains the main function to perform add, update, view, and delete operations

The control panel function is called which displays the options available to the user

Functions have been created for performing various operations like adding a new item, displaying items, checking specific items, updating items, and deleting items.

Each operation is performed by reading and writing data to a file named ‘book.txt’.

The function for updating items is implemented by first checking for the item to be updated and then updating the values in the file.

The function for deleting an item is implemented by first checking for the item to be deleted and then deleting the item from the file.

The program exits when the user selects the Exit option on the control panel.

## Step 1: Create a folder named DSMS.

```
DSMS
```
## Step 2: Go to the created folder and create a c++ file named ‘DSMS’.

```
echo.> DSMS.cpp
```

## Step 3: Paste the code given below in the DSMS.cpp


## Output: 

To get the output we need to follow some steps given below.

Run the command given below in the terminal:

```
g++ DSMS.cpp -o DSMS.exe
```
Here ‘DSMS’ is the file name and after that, a file named ‘DSMS.exe’ is created and now we need to execute it.
```
.\DSMS.exe
```

