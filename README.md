# Python-Challenge-1

<div align='center'>
    <img src='https://images.pexels.com/photos/1766682/pexels-photo-1766682.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1' height='300' title='A food truck (image courtesy of Pexels)' alt='an image of a food truck at night, illuminated by neon lights around the side of the truck and painted with caricatures of food items'/>

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

Let's tak a moment to walk through the order system and familiarize ourselves with its operation. For this example, assume you are the customer of the variety food truck.

Upon loading the order system, you will be presented a menu with four (4) options;

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/01-Main-Menu.png' title='Main menu' alt='A display of the main menu prompting the customer to select from Snacks (1), Meals (2), Drinks (3), or Dessert (4).'/>

*Main Menu*
</div

Once your secletion is made, you will be presented with one of four (4) menus corresponding to your choice;

<div style='disply: flex; flex-wrap: wrap;'>
    <img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/02-Snacks-Menu.png' style='width: 45%; margin: 5px;' title='Snacks menu' alt='A display of the snacks menu prompting the customer to select from the snack options and offering the prices.'/>
    <img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/03-Meals-Menu.png' style='width: 45%; margin: 5px;' title='Meals menu' alt='A display of the meals menu prompting the customer to select from the meal options and offering the prices.'/>
    <img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/04-Drinks-Menu.png' style='width: 45%; margin: 5px;' title='Drinks menu' alt='A display of the drinks menu prompting the customer to select from the drink options and offering the prices.'/>
    <img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/05-Desserts-Menu.png' style='width: 45%; margin: 5px;' title='Dessert menu' alt='A display of the dessert menu prompting the customer to select from the dessert options and offering the prices.'/>
</div>
<div align='center'>

*The four (4) menu options*
</div>

For argument's sake let's assume you are in the mood for a small, sweet snack and a coffee. To start, you will enter a "1" in the main menu to select "Snacks";

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-A.png' title='Enter a "1" in the main menu' alt='A display of the main menu with a numeric one entered into the prompt.'/>

*Selecting the snacks menu*
</div>

After being presented your options, you decide that a cookie, or two, would hit the spot. In the snacks meny, you will enter a "1", again, to select "Cookie";

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-B.png' title='Enter a "1" in the snacks menu' alt='A display of the snacks menu with a numeric one entered into the prompt.'/>

*Selecting "Cookie"*[^2]
</div>

Of course, the cookies look so delicious that you decide you need two (2) of them. When prompted for a quantity, you will enter a "2" to select two (2) cookies;

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-C.png' title='Enter a "2" in the quantity prompt' alt='A display of the snacks menu with a numeric one entered into the prompt for selection and a numeric two entered into the prompt for quantity.'/>

*Selecting two (2) cookies*[^3]
</div>

Excellent. But! You still need that coffee. After your cookies are entered, you will be prompted to decide whether or not you would like to continue ordering. You will enter a "Y" to continue;

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-D.png' title='Enter a "Y" or "y" in the continuation prompt' alt='A display of the snacks menu with a numeric one entered into the prompt for selection, a numeric two entered into the prompt for quantity, and a "Y" entered into the continuation prompt.'/>

*Continuing to order*[^4]
</div>

This will bring you back to the main menu. From here, you will enter a "3" to select "Drinks";

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-E.png' title='Enter a "3" in the main menu' alt='A display of the main menu with a numeric three entered into the prompt.'/>

*Selecting the drinks menu*
</div>

So many options... We did say you wanted a coffee, though. And it *is* a little warm, today. Go ahead and enter a "9" to select "Coffee - Iced";

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-F.png' title='Enter a "9" in the drinks menu' alt='A display of the drinks menu with a numeric nine entered into the prompt.'/>

*Selecting iced coffee*[^2]
</div>

Two (2) cookies and one coffee sounds right, so we only want the one (1). You will enter a "1" to select one (1) when prompted for quantity;

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-G.png' title='Enter a "1" in the quantity prompt' alt='A display of the drinks menu with a numeric nine entered into the prompt and a numeric one entered into the prompt for quantity.'/>

*Selecting one (1) iced coffee*[^3]
</div>

And you're done! You don't need any other food or drinks, so when you are prompted to continue ordering, you will enter a "N" to complete your order; 

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-H.png' title='Enter a "N" or "N" in the continuation prompt' alt='A display of the drinks menu with a numeric nine entered into the prompt, a numeric one entered into the prompt for quantity, and a "N" entered into the continuation prompt.'/>

*Completing your order*
</div>

The order system will then thank you for your order and present you with two (2) receipts[^5], one detailing the order being prepared and one itemized receipt to break down the individual and total costs of your order;

<div align='center'>
<img src='https://github.com/MxOdele/Python-Challenge-1/blob/c8ab265fb8983afef499c393ff33414b3369f1c0/Screenshots/06-Walkthrough-I.png' title='No futher entry needed' alt='A display thanking the customer for their order, a receipt detailing what has been ordered, and an itemized receipt detailing the individual and total costs of the oder.'/>

*Your order details and receipts*
</div>

**Note:** The above is just an example order. Using the same concepts, a customer could order any combination of food and drink available in the four (4) menus.

---

## Additional Information

### *Breaking down the code*

Here is a detailed explanation of the code being used to operate this order system;

| Lines | Notes |
| ---: | :--- |
| 1-51 | Notes |

Text

[^1]: Image courtesy of free source image site, <a href='https://www.pexels.com/photo/food-truck-1766682/' title='Link to Pexels listing for image'>Pexels</a>

[^2]: **Any non-numeric value entered, or any numeric value entered that is not represented in the "Item #" column, will cause an invalid selection prompt to display, and the customer will be asked again to make a selection.**

[^3]: **Any non-numeric value entered for quantity will default to a vlaue of one (1).**

[^4]: **Any valueother than "Y", "y", "N", or "n" entered will cause an invalid selection prompt to display, and the customer will be asked again if they would like to keep ordering. However, the case of the customer's entry does not matter as the order system will convert it to lower case.**

[^5]: **See: [Additional Information](#Additional-Information) for a more detailed explanation of the itemized receipt.**