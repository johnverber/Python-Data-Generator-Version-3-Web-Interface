# Python Data Generator Version 3 Web Interface
Name: Python Data-Generator

Author: John Verber

Version 3.0

Complete modular functionality.  All functions still run from web_data_generator.py.
Interface is now on web based.  
Requires PyWebIO installed (python3 -m pip install pywebio)
To run without web interface use data_generator_version1.py
Files can be downloaded and saved via web interface
In order to run just run python or python3 web_data_generator.py


Version 2.0

Added modular functionality.  All functions run from data_generator.py.  Do not need to spin up another instance to get csv or json files.  

Version 1.1

It still works the same.  I just added a main.py.  And some success messages.

In order to run this simply run it with python main.py.  See below for more description.


Version: 1.0

Description: This script will generate 'person' data for between 1 to 1000 distinct records.  It can generate more if you'd like to modify the code.  
It will output the data in the following formats: .txt, .csv, .json.  
The data per record is as follows: Last Name, First Name, Email, Address, and Phone number.  

Note: The last names are shared between the male and female names.  So some records may contain the same last name.
But all first names are distinct.  


System Requirements: Python
Ran and tested with Python 3.10.

Operating Instructions:
1) Simply run python data_generator.py or python3 data_generator.py
    



Files:
    Python files:
        data_generator.py (generates a txt file - data.txt - of a user defined number of data)
        csv_writer_module.py (generates a csv file from the data.txt file created by data_generator)
	json_writer_module.py (generates a json file from the data.txt file created by data_generator)
    Text Files:
        address.txt - file of 1000 random addresses
        phone.txt - file of 1000 random phone numbers
        female_done - file of 1000 random female first names and last names (comma separated)
        male_done - file of 1000 random male first names and last names (comma separated)
        data.txt - file created by data_generator.py (created after first run)
        data.csv - file created by csv_writer_module.py (created after first run)
        data.json - file created by json_writer_module.py (created after first run)
Known Bugs:
    None as of now.  But please update if you find one so it can be fixed.  Or better yet, fix it and create a pull request.  Thanks. 
