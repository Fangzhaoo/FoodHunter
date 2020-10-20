# FoodHunter

The domain modeled in this project is some selected restaurants in Vancouver mainland. This project is done using CPSC department’s Oracle database system in assistance with PHP.

The aspects of the restaurants we will be modeled consist of two levels. The fist level includes different restaurants’ profiles. As a simplified model, we are concerned with five restaurants (i.e., Haidilao Hotpot/ Miss Korean BBQ/ Pacific Poke/ Cactus Club Cafe/ Church Chicken) with all their profiles including address, phone, zip, etc. The second level is for user interaction, which takes into consideration two identities, namely the customers and the employees. Customers can use functions including placing order, rating restaurants, etc. Employees have the right to purchase ingredient and edit the menu, etc.

With respect to the application, the project is designed to involve interactions between different layers, i.e., customers can only order dishes existing in menus designed by employees, customers can rate restaurants which are later ranked based on these ratings and recommended to other users. Besides, a login system is added to our application to prevent unauthorized people from accessing our database and limit different rights to different users.

The login URL is https://www.students.cs.ubc.ca/~zfzhao/h.php (access to some pages is restricted due to the limitation of the department’s database system, which is only available during the course time). Some functions and the design philosophy can be visualized below:

General idea:

 ![image](https://github.com/Fangzhaoo/FoodHunter/blob/main/Food%20Hunter/images/database.png)

Starting Page:

 ![image](https://github.com/Fangzhaoo/FoodHunter/blob/main/Food%20Hunter/images/initialPage.png)

Login:

 ![image](https://github.com/Fangzhaoo/FoodHunter/blob/main/Food%20Hunter/images/Login.png)

Customer Homepage:

 ![image](https://github.com/Fangzhaoo/FoodHunter/blob/main/Food%20Hunter/images/userPage.png)

Employee function - purchasing ingredient:

 ![image](https://github.com/Fangzhaoo/FoodHunter/blob/main/Food%20Hunter/images/Purchase%20Ingredient.png)
