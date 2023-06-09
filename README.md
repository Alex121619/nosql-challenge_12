# nosql-challenge
# Intructions

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.


# Part 1: Database and Jupyter Notebook Set Up  ( found in "1. NoSQL_setup_starter" )
- Use NoSQL_setup_starter.ipynb for this section of the challenge.

  	- Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments. Copy the text you used 	         to import your data from your Terminal to a markdown cell in your notebook.

	- Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).

	- Create an instance of the Mongo Client.

	-  Confirm that you created the database and loaded the data properly:


# Part 2: Update the Database ( found in "1. NoSQL_setup_starter" )

- Use NoSQL_setup_starter.ipynb for this section of the challenge.
	- The magazine editors have some requested modifications for the database before you can perform any queries or analysis for them. Make the following changes to 	   the establishments collection:

# Part 3: Exploratory Analysis (found in "2. NoSQL_analysis_starter" )
- Use count_documents to display the number of documents contained in the result.
- Display the first document in the results using pprint.
- Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.
