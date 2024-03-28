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

| Line(s) | Notes[^6] |
| ---: | :--- |
| 2-51 | Declaring the dictionary `menu` |
| **55** | **Declaring an empty list `order` to store the customer's order** |
| 58 | Print statement welcoming the customer to the food truck |
| 62 | Declaring `place_order = True` to enable while loop |
| *63-196* | *While loop to process the customer's order* |
| 65 | Print statement prompting the customer to select a menu option |
| 68 | Declaring a variable `i` for menu item numbers |
| 70 | Declaring an empty dictionary `menu_items` to store menu items (which will be reused for the main menu as well as the four (4) food and drink menus) |
| 74-79 | For loop to populate the `menu_items` table with the main menu options and item numbers |
| 82 | Entering customer input as `menu_category` to select one of the four (4) food and drink menus |
| *85-168* | *If/Else statement to verify if `menu_category` is a digit, and to inform the customer of an invalid selection if not (as well as display their selected menu and process their choice(s))* |
| *87-164* | *If/Else statement to very if the digit entered for `menu_category` is a valid selection from the `menu_items` being displayed, and to inform the customer of an invalid selection if not (as well as process their choice(s))* |
| 89 | Declaring `menu_category_name` based on an integer casted `menu_category` entered by the customer |
| 91 | Print statment to display the `menu_category_name` selected by the customer |
| 94 | Print statement prompting the customer to select an item from the menu's options |
| 95 | Declaring a variable `i` for menu item numbers |
| 97-98 | Print statements to display the menu headers |
| 99-119 | For loop to print out the menu's options |
| 101-119 | If/Else statement to format the print statements based on whether or not the menu selectied from the `menu` dictionary |
| **121** | **Entering customer input as `menu_selection` to select on of the options in the current menu** |
| **124-161** | **If/Else statement to verify if `menu_selection` is a digit, and to inform the customer of an invalid selection if not (as well as verify if `menu_selection` is a valid selection from the `menu_items` being displayed, prompt the customer for the quantity of their selected item, store the variables `selection_name`, `selection_quantity`, and `selection_price` based on the custoemr's selection, and append those variable to the `order` list as a dictionary)** |
| **127** | **Converting `menu_selection` to an integer** |
| **130-157** | **If/Else statement to verify if `menu_selection` is a valid selection from the `menu_items` being displayed (as well as prompt the customer for the quantity of their selected item, store the variables `selection_name`, `selection_quantity`, and `selection_price` based on the custoemr's selection, and append those variable to the `order` list as a dictionary)** |
| **133** | **Declaring `selection_name` based on the `menu_selection` ebtered by the customer** |
| **136** | **Entering customer input as `selection_quantity` to select the amount of their choice to add to their order** |
| **139-142** | **If/Else statement to verify if `selection_quantity` is a digit, convert it to an integer if it is, and to default to a value of "1" if not** |
| **145** | **Converting `selection_price` (based on `menu_selection`) to a float (this step may be superfluous, but I figured it was better to be safe than sorry)** |
| **147-151** | **Declaring the dictionary `selection_add` and populating it with the values of `slection_name` for key `"Item name"`, `selection_price` for the key `"Price"` and `selection_quantity` for the key `"Quantity"`** |
| **153** | **Appending dictionary `order` with `selection_add`** |
| *170-196* | *While loop to prompt the customer for whether or not they wish to continue ordering after making a selection* |
| 172 | Entering customer input as `keep_ordering` to select whether or not to conitnue ordering |
| **175-196** | **Match-case statement to check the customer's input for `keep_ordering` (and converted to lower case for ease of writing cases)** |
| **176-181** | **Case `"y"`, sets `place_order` as "True" to enable cotinuing the order and then breaks out of the current while loop (line 170) to return to the main menu (line 63)** |
| **183-192** | **Case `"n"`, sets `palce_order` as "False" to complete order and then breaks from the current while loop (line 170) to progress to the confirmation of the customer's order (line 200)** |
| **194-196** | **Case `"_"`, print statement to inform the customer of an invalid selection and to repeat the while loop (line 170)** |
| 200 | Print statement preceding the customer's initial receipt |
| 202-203 | Print statements to display the receipt's headers |
| **206-222** | **For loop to print out the items in `order` list (as well as format spacing to maintain a uniform table)** |
| **209** | **Declaring `item_name` based on the `"Item name"` key from items in `order`** |
| **210** | **Declaring `price` based on the `"Price"` key from items in `order`** |
| **211** | **Declaring `quantity` based on the `"Quantity"` key from items in `order`** |
| **214** | **Calculating `num_selection_spaces` based on a static number and the length of `item_name` (this will be used on line 218)** |
| **215** | **Calculating `num_price_spaces` based on a static number and the length of `price` (this will be used on line 219)** |
| **218** | **Calculating `selection_spaces` based on `num_selection_spaces` (this will be used on line 222)** |
| **219** | **Calculating `price_spaces` based on `num_price_spaces` (this will be used on line 222)** |
| **222** | **Print statement using an f-string to display `item_name`, `price`, and `quantity`, and using `slection_spaces` and `price_spaces` to format spacing to maintain a uniform table** |
| **230** | **Calculating `line_totals` using list comprehension to multiply `item_price` by `quantity` for each item in `order`** |
| **233** | **Calculating `total_price` using a sum function on `line_totals` (this will be used on line 269)** |
| **236** | **Print statement to create a linebreak for customer readability** |
| **237** | **Print statement preceding the customer's itemized receipt (inlcuding another line break for readability)** |
| **239-240**[^5] | **Print statements to display the itemized receipt's headers** |
| **242-265** | **For loop to print out the items in `order` list (as well as format spacing to maintain a uniform table)** |
| **245-247** | **As lines 209-211** |
| **248** | **Declaring `line_totals` based on the values for the `"Price"` multiplied by the `"Quantity"` keys from items in `order`** |
| **251-252** | **As lines 214-215 (to be used on lines 256-257)** |
| **253** | **Calculating `num_quantity_spaces` based on a static number and the length of `quantity` (this will be used on line 258)** |
| **256-257** | **As lines 218-219 (to be used on lines 262-263)** |
| **258** | **Calculating `quantity_spaces` based on `num_quantity_spaces` (this will be used on line 264)** |
| **262-265** | **Print statement (broken up over miltiple lines for readablity) using an f-string to display `item_name`, `price`, `quantity`, and `line_totals` and using `slection_spaces`, `price_spaces`, and `quantity_spaces` to format spacing to maintain a uniform table** |
| **268** | **Print statement to break from the items in the itemized receipt (starting on line 242) from the grand total line** |
| **269** | **Print statement using strings and f-strings to display the `total_price` in line with the "Total" column of the itemized receipt table** |
| **270** | **Print statement thanking the cutomer for their order, again, because it seemed like a nice thing to do** |

### *Answering some questions*

* Why did you opt for in-line notation on lines 145, 189, 268, and 270?

Well... Because it seemed like it made more sense to tuck them away there than to break a whole new line for each of them. Each note pertains to the justification of their included lines, so I thought the simplest solution would be to keep them together.

* Why did you reprint the receipt section *just* to add a "Total" column?

That is a very fair question. The assignment wording was a little unclear as to whether or not we were meant to *use* the `line_totals` that we calculated through list comprehension. That said, I wanted to both use the list comprehension specifically to calculate the `total_price` ***and*** to include a more detailed itemized receipt. Blame my years in retail, but I prefer to know how much the items are individually, how much I'm paying for each of them, and how much I'm paying for everything in the order. So? I made sure to cover my bases and kept both versions on the receipt in place. For small orders it's no problem at all. I imagine it will eat up extra screen space if there's a particularly large order, though... Something to refactor in the next version, I suppose.

* Okay, but why indent "Grand Total" by a single space? That seems like an odd choice if you worked so hard to creat uniform tables twice.

Yes! It does! *And* it draws the eye to the line naturally. A subtle little way to make sure the customer sees that final line on the receipt and knows exactly how much they've been charged.

### *Final thoughts*

This was a fun assignment! I think it was a really good way to drill some of the more complext methods we've covered in the second week, and helps put into perspective the importance of what we've been learning in the third. Also, it feels really good when you see your code starting to work like you want it to. Building it up around the provided framework was a very rewarding exercise!

[^1]: Image courtesy of free source image site, <a href='https://www.pexels.com/photo/food-truck-1766682/' title='Link to Pexels listing for image'>Pexels</a>

[^2]: Any non-numeric value entered, or any numeric value entered that is not represented in the "Item #" column, will cause an invalid selection prompt to display, and the customer will be asked again to make a selection.

[^3]: Any non-numeric value entered for quantity will default to a vlaue of one (1).

[^4]: Any valueother than "Y", "y", "N", or "n" entered will cause an invalid selection prompt to display, and the customer will be asked again if they would like to keep ordering. However, the case of the customer's entry does not matter as the order system will convert it to lower case.

[^5]: See: [Answering some questions](#answering-some-questions) for a more detailed explanation of the itemized receipt.

[^6]: Code added provided for the assignment will be formatted normally, code added for the assignment will be bolded, and blocks containing both provided and added code will be italicized.