this is github repo:
https://github.com/SaqerAli/LaptopAndPcStore.git


steps to run asp.net program for the Laptop and pc store:

1-download Online Laptop and pc Shop rar folder

2-exctract it

3-Run sql managment studio (my version is sql server 2019)

4-Attach the GroceryDB database that is in Online Grocery Shop\App_Data folder to your sql server

5-open the project folder in visual studio as a website (chose the whole (Online Grocery Shop) folder)

6-Connect the database to the project you just opend by (chosing Tools/Connect to Database... in visual studio) then put your sql server name and choose the
GroceryDB database and press ok.

7-Replace the connection string in Web.Config file. and you do that by first geeting your connection string from your database connection in visual studio
and you do that by open the server explorer in visual studio and right click your database connection which is (your server name).GROCERYDB.dbo and choosing
properties and copying your connection string then you have to open Web.config and change the connection string with the one you just coped.

7- after all steps are done run Home.aspx with your chrome browser.



Admin user name is: admin

Admin password is: admin