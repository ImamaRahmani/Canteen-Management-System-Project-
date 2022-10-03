# Canteen-Management-System-Project-
Canteens are a go to place for any student or employee when they need a break from their hectic routine and have a snack or just gossip with their fellow classmates or colleagues. In their hectic routine they spare a very little time to visit the canteen. For that matter we want to provide a management system to reduce the customers waiting time.   Our project is based on canteen management system and the main objective of this project is to provide fast and easy service to the customers. This project will also allow the user to manage the food items, its sale, and the orders received and executed in a very systematic manner.

2.	**Introduction of your project**
Our project is based on canteen management system and the main objective of this project is to provide fast and easy service to the customers. This project will also allow the user to manage the food items, its sale, and the orders received and executed in a very systematic manner.
**3.	Methodology/ Plan development to solve the Problem**
We applied the knowledge we gained in object-oriented programming so far. The main four modules of this management system are:
•	Login Module.
•	Store Module.
•	Employee Module.
•	Billing Module.
 All these modules are able to add, edit, update, access, and delete items and different details according to their requirement. The details of food, their quantities, employee details etc. are handled by filed handling. 
**Pseudo code of the Program is:**

1)	Start
2)	Hompage 
If 1 goto login 
If 2 exit
3)	login
If 1 goto owners login 
If 2 goto employee login
If 3 goto exit
4)	Owners login
If 1 ask owners password
If true 
then
1. DISPLAY ALL EMPLOYEE DETAILS
     2. ADD NEW EMPLOYEE DETAILS
     3. REMOVE OLD EMPLOYEE DETAILS
     4. VIEW SALES RECORD
     5. CLEAR SALES RECORD
     6. STOREPAGE
     7. EXIT
Else again
5)	If 1 display from file Employee
6)	If 2 write in file Employee
Ask name age and salary
7)	If 3 delete from file employee
Ask name to delete 
8)	If 4 display from file sales
9)	If 5 delete from file sales 
10)	If 6 open store menu
     1. MANAGE INVENTORY
     2. VIEW INVENTORY
     3. TAKE ORDER
     4. VIEW SALES RECORD
     5. EXIT
     11) if 1 
             1. EDIT PRICE
		Write in file sales 
		Ask item and price 
             2. ENTER QUANTITY 
Write in file inventory 
		Ask item and quantity

11)	if 2
display from file inventory 
12)	if 3
 display inventory
ask item and quantity
	return price * Quantity in bill

13)	if items are not available 
display not available
14)	Employee login
If 1 ask employee password
If true 
then
     1. MANAGE INVENTORY
     2. VIEW INVENTORY
     3. TAKE ORDER
     4. VIEW SALES RECORD
     5. EXIT
     15) if 1 
             1. EDIT PRICE
		Write in file sales 
		Ask item and price 
             2. ENTER QUANTITY 
Write in file inventory 
		Ask item and quantity

16)	 if 2
display from file inventory 
17)	if 3
 display inventory
ask item and quantity
	return price * Quantity in bill

18)	if items are not available 
display not available
**4.	  Specifications**
The specifications of our project are as follows:
•	We used global variables for easy access and to avoid the difficulty of defining the same variable again and again.
•	We used four different classes i.e., Login, Store, Employee, and Billing classes.
•	We used file handling to handle the data such as employee record, food items price and their quantities in the canteen, sales made to the customer etc.
•	We used switch cases to provide menu options.

![image](https://user-images.githubusercontent.com/92652883/193621889-2b5d5e38-9f4a-4e86-a30a-d881e2822013.png)

![image](https://user-images.githubusercontent.com/92652883/193622029-296bd95f-953f-4490-87e7-69a8b9fa1134.png)

![image](https://user-images.githubusercontent.com/92652883/193622107-cf47b5e4-ccff-4b27-87a7-c421210d16e0.png)

![image](https://user-images.githubusercontent.com/92652883/193622206-6a8762b8-3c78-4a14-9d24-dd2ec71c372f.png)

![image](https://user-images.githubusercontent.com/92652883/193622261-1756d974-02ba-4c94-b776-041e40b61d39.png)

	**Conclusion**
This program is efficient in maintaining customer details and can easily perform operations on customer’s records and also works to handles the information of the products available in a canteen. This program also reduces the workload of the canteen.
 In future, this program can be launched as a website along with some alterations.
 
** References**
1. https://www.codewithc.com/c-projects-with-source-code/.
2. https://www.freeprojectz.com/paid-projects/canteen-management-system.


