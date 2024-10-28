# Assignment
You are required to build a Phone Directory to save contacts. Create a class Contact  . A contact will have following characteristics

•	private String fName, lName;
•	private String[] phoneNum;
•	private String affiliation;
•	private String occupation;
•	private String note = "";
•	private GregorianCalendar dob;
•	private boolean blocked;//= false;//Eager initialization
 Provide these methods

1.	Default & parameterized constructor.
2.	Provide overload constructor.
3.	Provide setters for all data members.
4.	Provide getters of all data members.
5.	Write a method replaceNumber(String old, String new),this will match the old number in the array and replace it wit new one.
6.	Provide toString() Method.

          Now create another class Directory having following characteristics
•	private ArrayList<Contact>  directory;
•	private int num;
Provide these methods

1.	Default & parameterized constructor.
2.	Provide overload constructor.
3.	Provide setters for all data members.
4.	Provide getters of all data members.
5.	Provide toString() Method.
6.	Provide a method addContact(Contact c) which will add a new Contact to arrayList directory.
7.	Also write another method which will also add new contact to directory addContact(String f, String l, String p[], String a, String o, String n, GregorianCalendar dob).
8.	Now write another metho Search which will search a particular contact in the directory using first name.
9.	Now write a method which delete a contact from directory using first name.
10.	Now create a TestApplication Create a menu 
•	Add Contact
•	Search Contact
•	Delete a Contact
•	Replace a Number
•	Display All.
•	Block a number//this will set blocked status of desired contact to true,
Make objects of Contact and directory input the values from user.
Call the methods and Display the value.
