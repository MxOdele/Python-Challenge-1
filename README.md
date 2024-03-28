# Python-Challenge-1

<div align='center'>
    <img src='https://images.pexels.com/photos/1766682/pexels-photo-1766682.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1' height='200' title='A food truck (image courtesy of Pexels)' alt='an image of a food truck at night, illuminated by neon lights around the side of the truck and painted with caricatures of food items'/>

*Variety Food Truck Menu*[^1]

## READ ME
</div>

## Table of Contents

* [Overview](#Overview)
* [Usage](#Usage)
* [Additional Information](#Additional-Information)

---

## Overview

### *The assigment*

For our Week 2 Challenge, we were tasked with completing the provided **menu.py** file to create a functional order system for a Variety Food Truck. The steps we were charged with completing were:

1. Creating an empty list to store the customer's order
2. Prompting the customer for input to select one of four menus
    * Validate the customer's input at this step, and multiple others
3. Prompting the customer for input to select an item from their selected menu
4. Storing the item name, price, and quantity based on the customer's selection
5. Confirming if the customer would like to order more items
6. Looping through the order list with the customer's selections
7. Creating unique variables for the items, prices, and quantities in the order list
8. Calculating how much space is needed to print the order list in a uniform presentation
9. Creating strings to enable that uniform presentation
10. Printing a receipt using the order list
11. Calculating the total costs for the items in the order list, and the grand total

### *Written in*

Python v3.10.13

### *Accessing the order system*

To access the, simply download the **menu.py** file in this repository and load it through your terminal. A detailed walkthrough of how to operate the order system is provided below.

---

## Usage

### *Walkthroguh*

Upon loading the order system, the customer will be presented a menu with four (4) options;

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/01-Main-Menu.png' title='Main menu' alt='A display of the main menu prompting the customer to select from Snacks (1), Meals (2), Drinks (3), or Dessert (4).'/>

*Main Menu*
</div

Once a secletion is made, the customer will be presented with one of four (4) menus corresponding to their choice;

<div class='image-grid'>
    <img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/02-Snacks-Menu.png' style='width: 45%; margin: 5px;' title='Snacks menu' alt='A display of the snacks menu prompting the customer to select from the snack options and offering the prices.'/>
    <img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/03-Meals-Menu.png' style='width: 45%; margin: 5px;' title='Meals menu' alt='A display of the meals menu prompting the customer to select from the meal options and offering the prices.'/>
    <img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/04-Drinks-Menu.png' style='width: 45%; margin: 5px;' title='Drinks menu' alt='A display of the drinks menu prompting the customer to select from the drink options and offering the prices.'/>
    <img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/05-Desserts-Menu.png' style='width: 45%; margin: 5px;' title='Dessert menu' alt='A display of the dessert menu prompting the customer to select from the dessert options and offering the prices.'/>
</div>

<style>
.image-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
}

.image-grid img {
    max-width: 100%;
    max-height: 300px;
}
</style>




Main Menu
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/01-Main-Menu.png' title='' alt=''/>

*Main Menu*
</div>



Snacks Menu
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/02-Snacks-Menu.png' style='width: 45%; margin: 5px;' title='Snacks menu' alt='A display of the snacks menu prompting the customer to select from the snack options and offering the prices.'/>

*Snacks Menu*
</div>



Meals Menu
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/03-Meals-Menu.png' style='width: 45%; margin: 5px;' title='Meals menu' alt='A display of the meals menu prompting the customer to select from the meal options and offering the prices.'/>

*Meals Menu*
</div>



Drinks Menu
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/04-Drinks-Menu.png' style='width: 45%; margin: 5px;' title='Drinks menu' alt='A display of the drinks menu prompting the customer to select from the drink options and offering the prices.'/>

*Drinks Menu*
</div>



Desserts Menu
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/05-Desserts-Menu.png' style='width: 45%; margin: 5px;' title='Dessert menu' alt='A display of the dessert menu prompting the customer to select from the dessert options and offering the prices.'/>

*Desserts Menu*
</div>



Walkthrough A
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-A.png' title='' alt=''/>

*Walkthrough A*
</div>



Walkthrough B
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-B.png' title='' alt=''/>

*Walkthrough B*
</div>



Walkthrough C
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-C.png' title='' alt=''/>

*Walkthrough C*
</div>



Walkthrough D
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-D.png' title='' alt=''/>

*Walkthrough D*
</div>



Walkthrough E
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-E.png' title='' alt=''/>

*Walkthrough E*
</div>



Walkthrough F
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-F.png' title='' alt=''/>

*Walkthrough F*
</div>



Walkthrough G
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-G.png' title='' alt=''/>

*Walkthrough G*
</div>



Walkthrough H
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-H.png' title='' alt=''/>

*Walkthrough H*
</div>



Walkthrough I
<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-I.png' title='' alt=''/>

*Walkthrough I*
</div>

---

## Additional Information

### *Text*

Text

[^1]: Image courtesy of free source image site, <a href='https://www.pexels.com/photo/food-truck-1766682/' title='Link to Pexels listing for image'>Pexels</a>