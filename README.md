# lab03

## What do you think is the type of each of the following fields? 
* private int count;
* -integer
* private Student representative;
* -representative
* private Server host;
* -host

## What are the names of the following fields? 
* private boolean alive;
* -alive
* private Person tutor;
* -tutor
* private Game game;
* -game

## From what you know about the naming conventions for classes, which of the type names in teh above questions would you say are class names?
The name of the class should always start with capital letter,Student,Server,Person,Game are the class name from above questions.

## In the following field declaration from the `TicketMachine` class  
```
private int price;
```
does it matter which order the three words appear in? Edit the TicketMachine class to try different orderings. After each change, close the editor. Does the appearance of the class diagram after each change give you a clue as to whether or not other orderings are possible? Check by pressing the Compile button to see if there is an error message. Make sure that you reinstate the original version after your experiments! 
Yes,the order matters!Other orderings are not possible because when we compile it shows a error


## Is it always necessary to have a semicolon at the end of a field declaration? Once again, experiment via the editor. The rule you will learn here is an important one, so be sure to remember it. 
Yes,it is important to put a semicolon at the end of a field declaration.

## Write in full the declaration for a field of type `int` whose name is `status`.
int status;

## To what class does the following constructor belong?
```
public Student(String name)
```
Class Student
## How many parameters does the following constructor have, and what are their types?
```
public Book(String title, double price)
```
Two-String and Double.
## Can you guess what types some of the `Book` class’s fields might be, from the parameters in its constructor? Can you assume anything about the names of its fields?
-int booknumber,string bookname,string booktype.


## Suppose that the class `Pet` has a field called `name` that is of the type `String`. Write an assignment statement in the body of the following constructor so that the `name` field will be initialized with the value of the constructor’s parameter.
```
public Pet(String petsName)
{
}
```
petsName=name;
## The following object creation will result in the constructor of the `Date` class being called. Can you write the constructor’s header?
```
new Date("March", 23, 1861)

```
Try to give meaningful names to the parameters.

public Date(String Month,int date,int year)
