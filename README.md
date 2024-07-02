# NoSQL-Challenge

1.	Title:  Module 12 Challenge-NoSQL

2.	Description:  The focus of the Module 12 Challenge is learning concept and application of the NoSQL database with MongoDB.  The exercise for this module will require importing a JSON file of food establishment ratings data to a MongoDB database and conducting analysis to help a food magazine make decisions about their future articles. ollecting, organizing, storing and analyzing data will be required to successfully complete the module. The following are the key areas covered:

a.	Database and Jupyter Notebook Set Up:
    i.	 Import the data provided in the establishments.json file from the Terminal
    ii.	 Name the database uk_food and the collection establishments.
    iii. Import libraries needed: PyMongo and Pretty Print (pprint).
    iv.	 Create an instance of the Mongo Client
    v.	 List the databases you have in MongoDB. Confirm that uk_food is listed
    vi.	 List the collection(s) in the database to ensure that establishments is loaded.
    vii. Assign the establishments collection to a variable
b.	Update the Database:
    i.	 Use NoSQL_setup_starter.ipynb for the Challenge. 
    ii.	 Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType.
    iii. Update the new restaurant with the BusinessTypeID 
    iv.	 Use update_many to convert latitude and longitude to decimal numbers
c.	Exploratory Analysis:
    i.	 Use count_documents to display the number of documents contained in the result.
    ii.	 Display the first document in the results using pprint.
    iii. Convert the result to a Pandas DataFrame

3.	Usage

a)	The NoSQL-Challenge file will have a Resources folder that contains Jupyter notebook Analysis and Setup starter files. In addition to an Establishements json file. 
b)	In order to achieve the coding outputs described above, the script sequencing for the NoSQL-Challenge requirements are as follows:
    i.	 Import required file dependencies
    ii.	 Create an instance of Mongo Client
    iii. List the databases in MongoDB
    iv.	 List the collections in the database
    v.	 Find and display documents

4.	Dependencies
a.	Importing the correct files
b.	Create and connect to local MongoDB databases 
c.	Create, read, update, and delete MongoDB documents
d.	Import data from CSV and JSON files to MongoDB
e.	Convert a MongoDB result to a Pandas DataFrame.
5.	Known Issues: Issues with the script.
a.	There were no know issues with the script that I am aware of.

6.	Author – Anthony Lipscomb


7.	Resources:  

a)	The code source for this Challenge assignment is based on assistance and debugging from our TA-Javier, Peer-Michael Andies, and the use of Xpert Learning Assistent and ChatGPT.

8.	Version History – Version 1

