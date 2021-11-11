# Email Sending Using Python
The whole point of this exercise is to count lines of code by scanning files of code, languages found, coments, number of files, etc... within a folder/file
# Scope
The file scanning of a specific file can count the files and deploy the data within the file with a chart of explination. While using Python on the other hand. The code will allow the file that has collected all the data of cloc and sent the file to a designated email with proof of the documentation of cloc. 

# Steps
In order for the process of the cloc to be sent to an email using Python, there are some things that need to be handled before succefully finishing the production.
1) Go to your gmail that the email will be sent to and go to the "Manage Your Google Account" button
2) Go to "Security"
3) Click the toggle button that will "Allow less secure apps" to be ON
4) Use the Python code to send the file over to an email
5) After running the cloc and received teh data of cloc, then start up the Python code to send the email

# Troubleshoot a problem
1) If the email was not received, double check if "Allow less secure apps" is ON. If it is off, the email will not go through
2) Python code was written on Visual Studio Code. If it does not run try running the source code on Terminal
3) If cloc is not recognized, make sure the cloc file is within the folder that you are using to catpure and send your data
4) If the file you are trying to send is not sending it to the email while running the Python code, make sure you type the correct file name of the cloc data correctly or "Copy the path" of the file and use that instead

