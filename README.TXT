Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.


Value is always resetting the balance back to 0.

When you put too much it still puts the balance back to 0 it doesnt carry over the values.

When you put to little the Void Print Ticket method still works

The cents text inputs the value orginally entered into the called method.

public TicketMachine(int cost) (Constructor for the class)
GetPrice(method)
GetBalance(method)
InsertMoney(method)
printTicket(method)
price(field)
balance(field)
total(field)

yes the ordering of a field matters

The student class

2 constructors title and price 
public int title;
public int author;
pubic int price;

 public Date(String month, int day, int year)
 
 23. The name of the return field used in the method.
24.How much money i have inserted

No since balance = Balance it doesnt matter what the method is named.

public void increaseScore(int points)
{
    score += points;
}

increaseScore Method

public void increaseScore(int points)
{
    score += points;
}

Yes, addCredits is a mutator method because it modifies the internal state of the object.

Student student = new Student();
student.addCredits(10); // Mutates the credits field
System.out.println(student.getCredits()); // Should print 10 


This shows that calling addCredits changes the value stored in the credits field.

Assuming price is a field in the class:
public void discount(int amount)
{
    price -= amount;
}



Setter for age Field
public void setAge(int currentAge)
{
    age = currentAge;
}


This sets the value of the age field using the parameter currentAge.

Setter for alive Field
public void setAlive(boolean status)
{
    alive = status;
}

37. My cat has green eyes.

43. Doesn't compile states that its an illegal expression but %D and %n are format specifiers.

46. The empty class is a mutator