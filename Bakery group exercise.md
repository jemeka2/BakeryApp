**BakeryApp**

[**(Links to an external site.)](https://github.com/jbcsep19/BakeryApp#your-favorite-bakery-needs-to-create-a-database-of-its-fresh-goods)**Your favorite bakery needs to create a database of its fresh goods!**

You're in a team of 2 (or 3).

Create at least 15 baked goods and save it into a collection of data. Each baked good has a name, price, an expiration date, one or more diet restrictions (ie. gluten allergies), and quantity in stock. The program should allow the user to search by diet restrictions and print all matching results. For a list of example products, see [https://sensitivesweets.com/collections/breads (Links to an external site.)](https://sensitivesweets.com/collections/breads)

All processes must happen in Classes, not in the main method of a Main class.

Pseudocode: Project: BakeryApp BakeryApp.java

Import Scanner

Welcome message

Create baked good 1-15

Create an array list of baked goods Add baked 15 good into array list

Prompt the user to enter a dietary restriction Take the restriction and search it from

BakedGood.class

Attributes

*String* Name

*Double* Price

*String* Expiration date

String Dietary restrictions int Stock

Constructor (name, price, exp date, dietary restrictions, stock)

Generates a new baked good with these attributes

Getters/Setters

Read or change attributes

displayBakedGood method

Print all attributes of the baked good

switch(userInput)

Case 1:

array.get(1) Break

Case 2

Job 2: create the bakedgood class(khulan)

Job 1: create the bakedgoods instances in main(Jabir)d Job 3: the rest of main app (nick)

![](Aspose.Words.42e5a470-f005-4f4a-83af-fd9abf7507f4.001.png)

BakedGood bakedGood1 = new BakedGood("banana bread", 5.95, "8/3/2021", "gluten-free", 10 ); BakedGood bakedGood2 = new BakedGood("muffins", 17.50, "8/6/2021", "gluten-free", 6 ); BakedGood bakedGood3 = new BakedGood("cinnamon swirl bread", 11.95, "8/1/2021", "gluten-free", "soy-free", 5 );

BakedGood bakedGood4 = new BakedGood("cinnamon bread", 11.95, "7/21/2021", "diary-free", 15 ); BakedGood bakedGood5 = new BakedGood("Multi-grain white bread", 11.95, "8/9/2021", "diary-free", 2 );

BakedGood bakedGood6 = new BakedGood("Cinnamon Raisin Bread", 11.95, "8/3/2021", "diary-free", "soy-free", 6 );

BakedGood bakedGood7 = new BakedGood("Lemon Blueberry Bread", 11.95, "8/3/2021", "diary-free", "nut-free", 16 );

BakedGood bakedGood8 = new BakedGood("soft pizza crust", 7.95, "7/18/2021", "nut-free", 12 ); BakedGood bakedGood9 = new BakedGood("Savory Rolls", 3.00, "8/3/2021", "nut-free", 17 ); BakedGood bakedGood10 = new BakedGood("dinner rolls", 3.00, "8/10/2021", "gluten-free", "diary-free", 20 );

BakedGood bakedGood11 = new BakedGood("Large Hamburger Buns", 5.00, "8/3/2021", "nut-free", "soy-free", 12 );

BakedGood bakedGood12 = new BakedGood("Savory Empanadas", 42.00, "8/3/2021", "nut-free", "soy-free", 24 );

BakedGood bakedGood13 = new BakedGood("Mint and Chocolate Sandwich Cookies", 19.95, "8/3/2021", "soy-free", 13 );

BakedGood bakedGood14 = new BakedGood("Remedy Cookie Brownie Bar", 4.95, "8/3/2021", "soy-free", 4);

BakedGood bakedGood15 = new BakedGood("Spring Cupcake Cups", 28.95, "8/3/2021", "soy-free", 12 );

public class BakedGood {

//attributes

private String name; private double price; private String expDate; private String restriction; private int stock;

//constructors public BakedGood(){

}

public BakedGood(String name, double price, String expDate, String restriction, int stock){

this.name = name;

this.price = price;

this.expDate = expDate;

this.restriction = restriction;

this.stock = stock;

}

//getters and setters

public void setName(String name) {

this.name = name;

}

public String getName(){

return this.name;

}

public void setPrice(double price){

this.price = price;

}

public double getPrice(){

return this.price;

}

public void setExpDate(String expDate){

this.expDate = expDate;

}

public String getExpDate(){

return this.expDate;

}

public void setRestriction(String restriction){

this.restriction = restriction;

}

public String getRestriction(){

return this.restriction;

}

public void setStock(int stock){

this.stock = stock;

}

public int getStock(){

return this.stock;

}

//display baked good

public void displayBakedGood(){

System.*out*.printf("Name: %s, Price: $%.2f, Exp Date: %s, Dietary restrictions: %s, In Stock: %d", this.name, this.price, this.expDate, this.restriction, this.stock);

}

}![](Aspose.Words.42e5a470-f005-4f4a-83af-fd9abf7507f4.002.png)

import java.util.Scanner; import java.util.ArrayList;

public class BakeryApp {

public static void main(String[] args) {

Scanner keyboard = new Scanner(System.in); // create scanner

System.out.println("Welcome to our bakery!"); // Welcome Message System.out.println("Select a dietary restriction to show products:"+

"\n1: Gluten Free, 2: Dairy Free, 3: Soy Free, 4: Peanut Free, 5: Show All"); int answer = keyboard.nextInt();

if (answer == 1){

//show the goods that BakedGood.getDietaryRestriction == gluten

}

else if (answer == 2){

//show BakedGood.get

}

else if (answer == 3){

}

else if (answer == 4){

}

else if (answer == 5){

}

else {

System.out.println("Please enter a number between 1 - 5"); }

}

}![](Aspose.Words.42e5a470-f005-4f4a-83af-fd9abf7507f4.003.png)

1. Make arraylist for goods
1. Put goods in arraylist
1. Modify bakedgood

Gluten free: 1, 2, 3, 10

Dairy free: 4, 5, 6, 7, 10

Nut free: 7, 8, 9, 11, 12

Soy free: 15, 14, 13, 12, 11, 6, 3

if (answer == 1) {

bakedGood1.displayBakedGood(); bakedGood2.displayBakedGood(); bakedGood3.displayBakedGood(); bakedGood10.displayBakedGood();

} else if (answer == 2) {

bakedGood4.displayBakedGood(); bakedGood5.displayBakedGood(); bakedGood6.displayBakedGood(); bakedGood7.displayBakedGood(); bakedGood10.displayBakedGood();

} else if (answer == 3) {

bakedGood7.displayBakedGood(); bakedGood8.displayBakedGood(); bakedGood9.displayBakedGood(); bakedGood11.displayBakedGood(); bakedGood12.displayBakedGood();

} else if (answer == 4) {

bakedGood15.displayBakedGood(); bakedGood14.displayBakedGood(); bakedGood13.displayBakedGood(); bakedGood12.displayBakedGood();

bakedGood11.displayBakedGood(); bakedGood6.displayBakedGood(); bakedGood3.displayBakedGood();

} else if (answer == 5) {

bakedGood1.displayBakedGood(); bakedGood2.displayBakedGood(); bakedGood3.displayBakedGood(); bakedGood4.displayBakedGood(); bakedGood5.displayBakedGood(); bakedGood6.displayBakedGood(); bakedGood7.displayBakedGood(); bakedGood8.displayBakedGood(); bakedGood9.displayBakedGood(); bakedGood10.displayBakedGood(); bakedGood11.displayBakedGood(); bakedGood12.displayBakedGood(); bakedGood13.displayBakedGood(); bakedGood14.displayBakedGood(); bakedGood15.displayBakedGood();

} else {

System.*out*.println("Please enter a number between 1 - 5"); }![](Aspose.Words.42e5a470-f005-4f4a-83af-fd9abf7507f4.004.png)

import java.util.Scanner;

import java.util.ArrayList;

public class BakeryApp {

public static void main(String[] args) {

Scanner keyboard = new Scanner(System.*in*); // create scanner

BakedGood bakedGood1 = new BakedGood("banana bread", 5.95, "8/3/2021", "gluten-free", 10 );

BakedGood bakedGood2 = new BakedGood("muffins", 17.50, "8/6/2021", "gluten-free", 6 );

BakedGood bakedGood3 = new BakedGood("cinnamon swirl bread", 11.95, "8/1/2021", "gluten-free", "soy-free", 5 );

BakedGood bakedGood4 = new BakedGood("cinnamon bread", 11.95, "7/21/2021", "diary-free", 15 );

BakedGood bakedGood5 = new BakedGood("Multi-grain white bread", 11.95, "8/9/2021", "diary-free", 2 );

BakedGood bakedGood6 = new BakedGood("Cinnamon Raisin Bread", 11.95, "8/3/2021", "diary-free", "soy-free", 6 );

BakedGood bakedGood7 = new BakedGood("Lemon Blueberry Bread", 11.95, "8/3/2021", "diary-free", "nut-free", 16 );

BakedGood bakedGood8 = new BakedGood("soft pizza crust", 7.95, "7/18/2021", "nut-free", 12 );

BakedGood bakedGood9 = new BakedGood("Savory Rolls", 3.00, "8/3/2021", "nut-free", 17 );

BakedGood bakedGood10 = new BakedGood("dinner rolls", 3.00, "8/10/2021", "gluten-free", "diary-free", 20 );

BakedGood bakedGood11 = new BakedGood("Large Hamburger Buns", 5.00, "8/3/2021", "nut-free", "soy-free", 12 );

BakedGood bakedGood12 = new BakedGood("Savory Empanadas", 42.00, "8/3/2021", "nut-free", "soy-free", 24 );

BakedGood bakedGood13 = new BakedGood("Mint and Chocolate Sandwich Cookies", 19.95, "8/3/2021", "soy-free", 13 );

BakedGood bakedGood14 = new BakedGood("Remedy Cookie Brownie Bar", 4.95, "8/3/2021", "soy-free", 4);

BakedGood bakedGood15 = new BakedGood("Spring Cupcake Cups", 28.95, "8/3/2021", "soy-free", 12 );

ArrayList<BakedGood> bakery = new ArrayList<>(); bakery.add(bakedGood1);

bakery.add(bakedGood2);

bakery.add(bakedGood3);

bakery.add(bakedGood4);

bakery.add(bakedGood5);

bakery.add(bakedGood6);

bakery.add(bakedGood7);

bakery.add(bakedGood8);

bakery.add(bakedGood9); bakery.add(bakedGood10); bakery.add(bakedGood11); bakery.add(bakedGood12);

bakery.add(bakedGood13); bakery.add(bakedGood14); bakery.add(bakedGood15);

System.*out*.println("Welcome to our bakery!"); // Welcome Message System.*out*.println("Select a dietary restriction to show products:"+

"\n1: Gluten Free, 2: Dairy Free, 3: Nut Free, 4: Soy Free, 5: Show All");

int answer = keyboard.nextInt();

if (answer == 1){

for (int i = 0; i < bakery.size(); i++){

if (bakery.get(i).getRestriction() == "gluten-free" || bakery.get(i).getRestriction2() == "gluten=free" ){

bakery.get(i).displayBakedGood();

}

else { }

}

}

else if (answer == 2){

bakedGood4.displayBakedGood(); bakedGood5.displayBakedGood(); bakedGood6.displayBakedGood(); bakedGood7.displayBakedGood(); bakedGood10.displayBakedGood(); //show BakedGood.get

}

else if (answer == 3){

bakedGood7.displayBakedGood(); bakedGood8.displayBakedGood(); bakedGood9.displayBakedGood(); bakedGood11.displayBakedGood(); bakedGood12.displayBakedGood();

}

else if (answer == 4){

bakedGood15.displayBakedGood(); bakedGood14.displayBakedGood(); bakedGood13.displayBakedGood(); bakedGood12.displayBakedGood(); bakedGood11.displayBakedGood(); bakedGood6.displayBakedGood(); bakedGood3.displayBakedGood();

}

else if (answer == 5){

for (int i = 0; i < bakery.size(); i++){

bakery.get(i).displayBakedGood();

}

}

else {

System.*out*.println("Please enter a number between 1 - 5");

}

}

}

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

while(userInput.equals("y")){

System.*out*.println("Welcome to our bakery!"); // Welcome Message System.*out*.println("Select a dietary restriction to show products:"+

"\n1: Gluten Free, 2: Dairy Free, 3: Nut Free, 4: Soy Free, 5: Show All");

int answer = keyboard.nextInt();

if (answer == 1){

for (int i = 0; i < bakery.size(); i++){

if (bakery.get(i).getRestriction() == "gluten-free" || bakery.get(i).getRestriction2() == "gluten-free" ){

bakery.get(i).displayBakedGood();

}

}

}

else if (answer == 2){

for (int i = 0; i < bakery.size(); i++){

if (bakery.get(i).getRestriction() == "diary-free" || bakery.get(i).getRestriction2() == "diary-free" ){

bakery.get(i).displayBakedGood();

}

}

}

else if (answer == 3){

for (int i = 0; i < bakery.size(); i++){

if (bakery.get(i).getRestriction() == "nut-free" || bakery.get(i).getRestriction2() == "nut-free" ){

bakery.get(i).displayBakedGood();

}

}

}

else if (answer == 4){

for (int i = 0; i < bakery.size(); i++){

if (bakery.get(i).getRestriction() == "soy-free" || bakery.get(i).getRestriction2() == "soy-free" ){

bakery.get(i).displayBakedGood();

}

}

}

else if (answer == 5){

for (int i = 0; i < bakery.size(); i++){

bakery.get(i).displayBakedGood();

}

}

else {

System.*out*.println("Please enter a number between 1 - 5");

}

System.*out*.println("Try Again? (y/n): "); userInput = keyboard.next(); userInput.toLowerCase();

}
