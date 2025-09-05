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
    private Student representative;    ()
    private Server host;               ()

13. private boolean alive;             ()
    private Person tutor;              ()
    private Game game;                 ()

**Questions 12-13 not completed.**


14. ?

15. int private price -> Shows multiple red diagonal lines crossing each other.
    private price int -> Shows multiple red diagonal lines crossing each other.
    price private int -> Shows multiple red diagonal lines crossing each other.
    price int private -> Shows multiple red diagonal lines crossing each other.
After doing each test, it is safe to say the the order which the 3 words appear in are important.
The class diagram does gives clues to which orderings are possible. If there are red lines on it, it isn't possible; however grey lines means it is possible.

16. It is alway necessary since it's basically like a period at the end of a sentence. It tells the computer where does my statement end.

17. ?

18. It belongs to the Student class.

19. ?

20. ?

21. ?

22. CHALLENGE EXERCISE (to do)

23. Difference headers: 
    Difference bodies:

24. "How much money is in my balance?"

25. The return statement does not need to be changed for the code to compile it. It tells me the name of the field and method aren't really dependent of each other.

27. It says "missing return statement".

28. They have different return types. getPrice is int, while printTicket is void.

29. They have the same return statements which is "void". They both do not return any value, which is why they use the void statement.

32. ?
