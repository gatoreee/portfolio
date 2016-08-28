# portfolio
Project: Portfolio  - [Enrique B]
================================

Required Libraries and Dependencies
-----------------------------------
The project uses Twitter's Bootstrap. The Bootstrap stylesheets are linked to in the index.html files so there's no need for local copies.
In order to easily configure and run the project with the instructions below, the user should have grunt and python installed and configured in their system. 


How to Run Project
------------------
The project repository can be found at https://github.com/gatoreee/portfolio. Save all files to a local folder.
In order to run the application, open a command prompt and follow the instructions below:
1) From the command prompt, use cd command to take you to the folder where the files are saved.
2) From the command prompt, run the 'grunt' command to create a new images folder with optimized versions of the source images.
3) From the command prompt, run the command 'python -m SimpleHTTPServer' to launch a local server that will serve index.html on localhost port 8000.
4) Open Chrome and enter 'localhost/8000' in the address bar.


Extra Credit Description
------------------------
For this project I added a grunt file that takes large source images and produces several smaller versions that are seleceted by the browser depending on the viewport size.
The project uses media queries at different breakpoints to provide a pleasent and responsive interface for different device types.

