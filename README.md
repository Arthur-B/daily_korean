# daily_korean
The goal of this project is to manage vocabulary lists and either print or send an email with the vocabulary I must learn for the day.

The code is based on stuff I read in "Automate the boring stuff with Python", by A. Sweigart.

# Using the script

Store your vocabulary list in an excel file, you can use one of the list from the folder "Vocabulary lists (clean)". First and second columns are read. Third and fourth are used by the script to write the date and mark if the vocabulary was previously learnt.

Put the excel file in the "Vocabulary lists (edited)" folder, it is the working folder.

Open "korean_vocab.py" and edit the parameters (lines 20-23). You just need to edit the parameters the first time you use the script, to initialize everything.

Run the script. Consider making a batch file or something to run it as an executable file and making it easier to use. I made a batch file that sit on my desktop so that I can launch it everyday.


# To-do list
- Make an exec file or something similar (using a batch file so far)
- Send an email without getting banned from Google (just printing so far)
- Add more vocabulary lists


