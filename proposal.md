# Wandering Merchant

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Learning opportunity costs and bargaining/ buying and selling.
Learning the idea of a basic business model : "Buy low, sell high"

Our program would be a simple game where you can purchase items from traveling merchants. Your goal is to maintain a basis of wealth by buying and selling products. Items and Item prices will vary from merchant to merchant. Your job to decide when to purchase items and when to sell those items.

To test, we would use JUnit to inventory creation, purchasing and selling to merchants (Updating both inventories, items and quantities, money), testing that the merchant's data/items change with a merchant refresh.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Wandering Merchant

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Name, price, rarity, quantity of item

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

Item to purchase
quantity of purchase
Buy or sell
refresh merchant

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

Simple graphical ui, buttons for purchasing and selling. Icons for items.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Main:
*Main method
*Hashtable - list of all items
*Shopkeeper - Current Shopkeeper
*Inventory - Player's inventory

Shopkeeper:
*Inventory - Inventory
*Double - Cost modifier

Inventory:
*list - Items
*list - Quantity
*Double - Money

Items:
*String - Name
*Image - Icon
*Double - Average Price
*Double - Rarity


Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

