--------------------At Server side------------

C:\Users\admin>E:

E:\mongodb-win32-x86_64-2008plus-2.6.2\mongodb-win32-x86_64-2008plus-
2.6.2\bin>mongod.exe --dbpath E:\dvs

Note: keep the server in running state



-------------------At Client side-----------

Open Another CMD prompt

Go to bin folder of Mongodb

C:\Users\admin>cd E:\mongodb-win32-x86_64-2008plus-2.6.2\mongodb-win32-x86_64-2008plus-2.6.2\bin

C:\Users\admin>E:

E:\mongodb-win32-x86_64-2008plus-2.6.2\mongodb-win32-x86_64-2008plus-2.6.2\bin>mongo.exe dvs

MongoDB shell version: 2.6.2

connecting to: dvs

Now dvs database is ready. You can perform all the related operations on the dvs database.

At server side :

You will find the following:

2014-06-20T17:44:09.233+0530 [initandlisten] connection accepted from 127.0.0.1:

49360 #1 (1 connection now open)


-------------Java Program--------------
1.>Extract the MobileDB.rar file.
2.>Open the MobileDB\dist\ folder
3.>Directly run the MobileDB manager JAR Executable file.
4.>Username:-dvs
   Password:-bu 
Enjoy!