
**Update: Huge Milestone for a home project. The database already have 1.1 Million apps.** 
---------------------------------------------------------------------------
**Update 2: Amazon AWS Started to Charge me, and the Mongo Database is eating up my whole disk, so please, avoid executing Insertions on this database. Try to use it as read-only for your personal researches. I will pay for the network outbound cost monthly, but if the cost increases too much, i will have to un-host the database. Use it wisely**
---------------------------------------------------------------------------
**Update 3: Dropbox blocked out my public link with the exported database because of the traffic it generated. I just hosted it on my own Amazon S3 bucket**
---------------------------------------------------------------------------

GooglePlayStoreCrawler
======================

Simple scalable crawler for Apps data from the Play Store.

You don't have to input any of your Google Account credentials since this Crawler acts like a "Logged Out" user.

# Exporting the Database
As people kept requesting me, i decided to export the database on it's current state.
Heres the link for download as a comma delimited file ( csv with headers): https://s3.amazonaws.com/GooglePlayStore/Google%20Play%20Stats.7z

Have in mind that downloading the database costs me money, since i pay for the outbound traffic provided by AWS when you query the database
So, consider making a donation (via paypal) to marcello.grechi@gmail.com (the value is up to you).

Alternativelly, you can use the "AppsExporter" project that i included to write your own query logic, exporting only the records / fields you need, which will be cheaper than downloading the whole database.

# Opening the Database

Since the exported database contains more than 1 milion lines, you will have to use one text editor such as "EM Editor" for opening the file. Regular text editor such as Notepad++ and Sublime won't open it and will crash.

# About me
My name is Marcello Lins, i am a 23 y/o developer from Brazil who works with BigData and DataMining techniques at the moment.

http://about.me/marcellolins

# What is this project about ? 

The main idea of this project is to gather/mine data about apps of the Google Play Store and build a rich database so that developers, android fans and anyone else can use to generate statistics about the current play store situation

There are many questions we have no answer at the moment and we should be able to answer than with this database.

# What do i need before i start?

* I highly recommend you read all the pages of this wiki, which won`t take long.

* Know C#

# How about the database?

* I have made my MongoDB database public, including a user with read/write permissions so we can all use and populate the same database

* If you feel like, you can make your own MongoDB Database and change the code Consts to point the output to your own MongoDB Database. No Biggie


**Refer to the Pages section of this wiki for individual information about each aspect of the project.**
