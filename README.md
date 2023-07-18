# DataCollection-Challenge


## Instructions

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.



## Outline

This new assignment requires you to submit the following deliverables:

Deliverable 1: Database and Jupyter Notebook Set Up - Use NoSQL_setup_starter.ipynb for this section of the challenge.

Deliverable 2: Update the Database - Use NoSQL_setup_starter.ipynb for this section of the challenge.



### Part 1: Database and Jupyter Notebook Set Up

>1. Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments. Copy the text you used to import your data from your Terminal to a markdown cell in your notebook.

>2. Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).

>3. Create an instance of the Mongo Client.

>4. Confirm that you created the database and loaded the data properly:
>>>4.1 List the databases you have in MongoDB. Confirm that uk_food is listed.
>>>4.2 List the collection(s) in the database to ensure that establishments is there.
>>>4.3 Find and display one document in the establishments collection using find_one and display with pprint.

>5. Assign the establishments collection to a variable to prepare the collection for use.



### Part 2: Update the 
## The magazine editors have some requested modifications for the database before you can perform any queries or analysis for them. Make the following changes to the establishments collection:

>1. An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis. Add the following information to the database:

![image](https://github.com/ChenitaFrancis-Hare/NoSQL-Challenge/assets/131192552/51928816-7fd5-4f4b-84bc-9b83018e9a58)

>2. Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.

>3. Update the new restaurant with the BusinessTypeID you found.

>4.The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.

>5. Some of the number values are stored as strings, when they should be stored as numbers.

>>> 5.1. Use update_many to convert latitude and longitude to decimal numbers.

>>> 5.2. Use update_many to convert RatingValue to integer numbers.



## References

UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).





