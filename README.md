# testings

This is a software engineering question that requires designing and implementing an API to query 
and access books from a PostgreSQL database dump of books for data 

Swagger description of the API (YML file or hosted swagger)
Implementation of the API at a publicly accessible location for testing
Code for the implementation (preferably in Github or another hosted git repository)


Retrieve books meeting zero or more filter criteria
Return the number of books meeting the criteria and a list of book objects containing title, author information, genre, language, subject(s), bookshelf(s), and links to download the book in available formats (mime-types)
If the number of books exceeds 25, return 25 at a time and support retrieving the next sets of 25 books until all are retrieved
Return books in decreasing order of popularity (number of downloads)
Return data in JSON format
Support filtering on book ID numbers, language, mime-type, topic (on subject and bookshelf), author, and title
Support multiple filter criteria and multiple filter values for each criteria


Need to create python environment. 

With Bash that can be 

python -m venv .venv 
-Activate this environment 

After this do  
--pip install requirements.txt

Manual implementation 
So once that is done. we have to need include an env file with some details .  
DEBUG=True
DB_NAME=""
DB_USER=""
DB_PASSWORD=" "
DB_HOST=""
DB_PORT=""
SECRET_KEY = " "
Then we have to makemigrations, migrate and check the server
