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

ANSWERS TO QUESTIONS:

2. The value returned is 0 cents.

3. I didn't receive any refunds when I had more money in my balance than the cost of a ticket. It gave me the ticket, but also returned my balance back to 0. When I tried to print a ticket without having the sufficient amount of money, it still was able to print a ticket and returned my balance back to 0 instead of being in the negatives (since ticket price>balance).

5. The printed ticket is exactly the same as the first one, but the only difference is the price indicated at the before last line of the ticket.

6. For Students: // the student's full name
                 private String name;
                 // the student ID
                 private String id;
                 // the amount of credits for study taken so far
                 private int credits;

   For LabClass: private String instructor;
                 private String room;
                 private String timeAndDay;
                 private ArrayList<Student> students;
                 private int capacity;

7. Yes, it does matter. After changing the source of the TicketMachine, it shows multiple errors on the source code. It also changed the name of the class to "public" and shows diagonal bars on the class. After trying to compile, it opens up the source code of the TicketMachine, and says "Error(s) found in class". The message isn't really clear since it's a bit vague due to the fact we do not know what those errors are, but it also shows the locations of the errors and the error itself.

8. It's possible to leave out the word public from the outer wrapper of the TicketMachine class.

9. It's not possible to leave out the word class. After trying to compile, I received an error message indicating there are multiple errors in the source code of the TicketMachine class.

10. Constuctor:public TicketMachine(int cost)
    Fields:- private/public
           - int
           - balance
           - void
           - price 
           - total
    Methods: - public int getPrice()
             - public int getBalance()
             - public void insertMoney(int amount)
             - public void printTicket()

11. It has initial values stored into the fields. The constructor has the same name as the class, TicketMachine.

12. private int count;                 (int)
    private Student representative;    (Student)
    private Server host;               (Server)

13. private boolean alive;             (alive)
    private Person tutor;              (tutor)
    private Game game;                 (game)

15. int private price -> Shows multiple red diagonal lines crossing each other.
    private price int -> Shows multiple red diagonal lines crossing each other.
    price private int -> Shows multiple red diagonal lines crossing each other.
    price int private -> Shows multiple red diagonal lines crossing each other.
After doing each test, it is safe to say the the order which the 3 words appear in are important.
The class diagram does gives clues to which orderings are possible. If there are red lines on it, it isn't possible; however grey lines means it is possible.

16. It is alway necessary since it's basically like a period at the end of a sentence. It tells the computer where does my statement end.

17. private int status;

18. It belongs to the Student class.

19. It has 2 parameters. The types are double and String.

20. Yes, it should be stored somewhere persistent like on the object's field. It can probably have a field of type String and double. The String would be like the title of the Book and the double would most likely be the price of the Book. No we cannot know anything for sure about the names of its field since the programmer could have chosen different names for the fields.

21. public Pet(String petsName)
    {
          name = petsName
    }

22. The header would be something like this: public newDate(String month, int day, int year)

23. Difference headers: The method names are different (one is called getBalance, while the other is getPrice).
    Difference bodies: One returns the value of a field named price while the other returns the value of a field named balance.

24. "How much money is in my balance?"

25. The return statement does not need to be changed for the code to compile it. It tells me the name of the field and method aren't really dependent of each other.

27. It says "missing return statement".

28. They have different return types. getPrice is int, while printTicket is void.

29. They have the same return statements which is "void". They both do not return any value, which is why they use the void statement.

32. Yes, the addCredits methos is a mutator. I could demonstrate it by first finding out the initial credit value by calling the getCredits method. Then I would call the addCredits method, and input the amount I would like to add. After I would again call the getCredits method to find out the credit value has changed.

34. public void setAge(int currentAge)
    {
         age = currentAge;
    }

35. public void setAlive(boolean isAlive)
    {
         alive = isAlive;
    }

36. After opening the inspector, I see that the value of price is 0 instead of the value I inputted, which was 100.

37. My cat has green eyes.

39. I think # price cents will be printed.

40. # price cents.

42. They show different outputs since they both have different values of the price field.

43. Yes, it does. %d, I believe it is the value of the price, but I'm not so sure what %n is.

44. The price of a ticket is now fixed at 1000 cents, and you cannot input a price for it when creating a new machine.

46. No, it doesn't need to take any parameters. The empty methos is a mutator since it changes the object in question.

