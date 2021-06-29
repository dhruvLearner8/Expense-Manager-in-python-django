# Expense-Manager-in-python-django

#This is a expense manager website using python and django

#Steps to run this file:
1)install vs code
2)must have python and django installed in your system .
3)Download main folder named dhruv and open in VS code 

BELOW STEPS FOR POSTGRESQL YOU CAN ALSO RUN THIS FILE WITH DEFAULT SQLITE3(WATCH SOME YOUTUBE VIDEO FOR DATABASE CONNECTIVITY WITH SQLITE3)
4) download Postgresql https://www.postgresql.org/download/ this will also install pgadmin4 in your system
5)type "pip install psycopg2" (double inverted commas excluded) in your terminal in vs code this is a software which will connect django and postgresql
6)type "pip install pillow" (double inverted commas excluded) in terminal in vs code

7)after this in your computer's search bar type pgadmin4 and open it and it will ask for password type anypassword you want, then click on servers and again it will ask for password so type"1234" 
  and click on database and create a database named "dinero2" 
8)now in vs code in main folder dhruv in terminal type "python manage.py migrate"
9) now in same terminal type "python manage.py runserver"
10)type "pip install secure-smtplib" for importing smtplib(for sending otp to mail for new password)

#Functions available:
1) Register,login,logout
2)Forget Password,new password
3)History of all expenses


