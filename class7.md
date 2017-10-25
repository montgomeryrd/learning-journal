Today I practiced creating object constructor functions and learned how to append data into a table using script. That--I'll definitely need to learn better. What else did we cover today. That seems to be the main thing we did. Time flies while coding. I hate that.

Here's an object constructor function for Subway sandwiches. I'm hungry.

var sandwiches = [];

function Subway(bread, meat, cheese, veggies, condiments, sides){
  this.bread = bread;
  this.meat = meat;
  this.cheese = cheese;
  this.veggies = veggies;
  this.condiments = condiments;
  this.sides = sides;
}

var club = new Subway('flat', [ham, turkey], 'cheddar', [onions, lettuce, tomatos], 'mayo', 'cookies');
var meatball = new Subway('oat', 'meatball', 'american', 'None', 'marinara', 'Doritos');
var chicken = new Subway('herb', 'chicken', 'cheddar', [lettuce, onions, tomatos, pepperchini], 'mayo', 'BBQ Lays');
var turkey = new Subway('cheesy', 'turkey', 'pepperjack', [lettuce, onions, tomatos, jalapenos], [guacamole, mayo], 'cookies');
var italian = new Subway('italian', [turkey, ham, pepperoni, pastrami], 'american', [lettuce, onions, tomatos], 'mayo', 'Ruffles');

sandwiches.push(club);
sandwiches.push(meatball);
sandwiches.push(chicken);
sandwiches.push(turkey);
sandwiches.push(italian);