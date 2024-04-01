# Variable and Methods
Small info abt Attributes and Methods

 University Class:
Attributes(VARIABLES)
1. Name: The name of the university.
2. Location: The physical location where the university is situated.
3. Number of Students: The total number of students enrolled in the university.
4. Faculty Members: The total count of faculty members working in the university.
5. Courses Offered: A list of courses offered by the university.

Behaviors(METHODS)
1. Enroll Student: Method to enroll a student in the university.
2. Hire Faculty: Method to hire a faculty member.
3. Offer Course: Method to add a new course to the university's curriculum.
4. Organize Events: Method to organize events such as seminars, workshops, etc.

Bank Class:
Attributes
1. Name: The name of the bank.
2. Location: The physical location of the bank branch.
3. Total Assets: The total value of assets held by the bank.
4. Number of Accounts: The total number of accounts held by the bank.
5. Interest Rate: The interest rate offered by the bank on savings or loan accounts.

Behaviors
1. Open Account: Method to open a new account for a customer.
2. Close Account: Method to close an existing account.
3. Process Transaction: Method to process deposits, withdrawals, or transfers.
4. Calculate Interest: Method to calculate interest for savings accounts.

Theatre Class:
Attributes
1. Name: The name of the theatre.
2. Location: The physical location of the theatre.
3. Seating Capacity: The total number of seats available in the theatre.
4. Show Timings: The schedule of shows (e.g., movies, plays) at the theatre.
5. Ticket Prices: The prices of tickets for different types of shows.

Behaviors
1. Sell Tickets: Method to sell tickets for a show.
2. Reserve Seats: Method to reserve seats for customers.
3. Display Schedule: Method to display the schedule of shows.
4. Cancel Show: Method to cancel a scheduled show.

 Radio Class:
Attributes
1. Name: The name of the radio station.
2. Frequency: The frequency at which the radio station broadcasts.
3. Programs: The list of programs aired by the radio station.
4. Listenership: The number of listeners tuned in to the radio station.

Behaviors
1. Broadcast Program: Method to broadcast a program.
2. Change Frequency: Method to change the frequency of the radio station.
3. Advertise: Method to advertise products or services on the radio.
4. Collect Feedback: Method to collect feedback from listeners.

#JAVA and its Architecture

Java works through a combination of its language features, virtual machine architecture, and extensive library support.

1. Writing Code: You write Java code using a text editor or a specialized program like IntelliJ IDEA.
  
2. Compilation: Your Java code gets translated into a special kind of code called "bytecode."
  
3. Java Virtual Machine (JVM): This bytecode can run on any device with a JVM. It's like a translator that turns bytecode into instructions your computer understands.
  
4. Platform Independence: Because of the JVM, Java programs can run on different types of devices without needing to be rewritten.
  
5. Java API: Java comes with a bunch of pre-made tools and functions called the Java API. You can use these to do lots of different things without starting from scratch.
  
6. Execution: Once translated by the JVM, your code runs on the device just like any other program.

#POSSIBILITIES OF MAIN METHOD

C:\Users\SUKESH\Desktop\Programming\Ques\Core java>javac java1.java
java1.java:30: error: <identifier> expected
        **static public void main(String[])**
                                        ^
1 error


C:\Users\SUKESH\Desktop\Programming\Ques\Core java>javac java1.java
java1.java:30: error: invalid method declaration; return type required
       **static public main(String[]args)**
                      ^
1 error

C:\Users\SUKESH\Desktop\Programming\Ques\Core java>javac java1.java
java1.java:30: error: <identifier> expected
        **static public void(String[]args)**
                          ^
1 error

C:\Users\SUKESH\Desktop\Programming\Ques\Core java>javac java1.java
java1.java:30: error: <identifier> expected
         **public static void(String[]args)**
                           ^
1 error

**public static void main(String[]args)**
C:\Users\SUKESH\Desktop\Programming\Ques\Core java>javac java1.java

C:\Users\SUKESH\Desktop\Programming\Ques\Core java>java a
HELLOO

**static public void main(String[]args)**
C:\Users\SUKESH\Desktop\Programming\Ques\Core java>javac java1.java

C:\Users\SUKESH\Desktop\Programming\Ques\Core java>java a
HELLOO
C:\Users\SUKESH\Desktop\
