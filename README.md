# Utilize the Array Find Methods for JavaScript

Array Iterator, also known as "iterators" and "iterator methods," allows us to iterate through arrays to manipulate elements and return some values. In this case, we will focus on the Array Find Method, which utilizes find() to isolate precise outcomes. 

find() executes the callback function for each element in the array until the callback returns a truthy value, which instantly returns the elements and stops searching.

Method Name: find 
Returns: Value of first circumstance of the element
         Element doesn't exist, not a truthy value/Boolean context: undefined

## Installation

None.

## Usage

Using Arrow Function with find() to destruct 

// Small Meal Kit Delivery Food Company Inventory 

const inventory = [ </br>
  {name: 'Salmon', quantity: 100}, </br>
  {name: 'Ground Beef', quantity: 95}, </br>
  {name: 'Pork Chops', quantity: 120}, </br>
  {name: 'Chicken Breast', quantity: 200}, </br>
  {name: 'Steak', quantity: 150}, </br>
  {name: 'Beyond Meat Burger', quantity: 250} </br>

]; </br>

const result = inventory.find(({name}) => name === 'Chicken Breast'); </br>
console.log(result) // {name: 'Chicken Breast', quantity: 200} </br>

## 

You have learned how a small fraction of how to use the find() method in JavaScript array to search for the first occurrence of an element that helps a test.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
