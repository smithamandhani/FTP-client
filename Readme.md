# FTP-client
READ ME-
This Project is used to create FTP inorder to connect to linux.cs.pdx.edu server via proper userid and password.
In order to use this project -
Clone the project using command-
git clone https://github.com/smitha/Agile510.git
cd Agile510
git checkout FTPClientAgile
Now the correct project structure will be ready to execute the project 
Import the cloned project in IntelliJ or Elipse using pom.xml 
Go to -> Run -> Edit Configuration  ->click on "+" symbol , add new application name- FTPConnectDemo
Main Class - FTPConnectDemo
Program Arguments -> linux.cs.pdx.edu 22 userID Password
Choose Proper Working Directory
Click on Apply
Pass your arguments using ftp.properties file(set UserID , Password)
Click on Run -> Click Run Application
FTP Client gets connected.
Enter the following commands to carry out various functions-
ls --> to list directories.
rd->Download/get single file from remote directory(this command will support downloading multiple files once that story is completed)
mkdir directory_name --> to make directory on remote server.
rm file_name --> to remove file on remote server.
rmdir directory_name --> toremove directory on remote server.
logout-logout from the current session
q --> quit the program

