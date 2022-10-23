##   MEAN STACK DEPLOYMENT TO UBUNTU IN AWS SERVER

MEAN Stack is a combination of 
  > - MongoDB - It is Document Database that stores and allows to retreive data.
  > - Express - It is a Back-end application framework that makes request to Database for Reads and Writes.
  >-   Angular - It is a Front-end application framework that handles Clients and Server Request.
  > - Node.js - It is JavaScript runtme environment that accepts requests and displays results to an end user.

The task is to Implement a simple Book Register Web Form using MEAN Stack.

**Step** 1 - *Connect to AWS server using Ubuntu 20.04.5 LTS*

        - Connected to AWS server using Ubuntu
        - Changed Hostname to ProjectMEANstackserver to identify project name.
       
![Ubuntu connection](Images/new1...png)


- Updated and upgraded Ubuntu
     
     
![Updated](Images/new2.png)

![upgraded](Images/new3.png)
     
     
   ## Installing  *Node.Js*

![node certificate](Images/new4.png)

![node.js](Images/new6.png)

   
![images for node.js](Images/new5.png)
     
  ## Installing **MongodDB**


![images of mongodb certifcate](Images/new7.png) 
       

![images of mongodb](Images/mongodb.png)    
       
       
       - Starting the Server
       - Verifying that service is up and running

![images](Images/new8.png)

       
       - Install npm-Node package manager

![npm install](Images/npm.png)
       
       - Install body-parser package
       
       
![images of npm and body-parser](Images/Bodyparser.png)
       
       
       
         - Creating a Folder Named BOOKS
         
         - Initialize in the Book directory and npm project
         
         - Added file server.js and pasted a web server code inside the server.js
         
![images of server.js command](Images/books.png)

![images](Images/code.png)
         
         
         
STEP 3 - *INSTALLING **Express** AND SETTING UP **Routes** TO THE SERVER*
         
            - Express is used to pass book information to and from the Mongodb database.
            
             - Installing mongoose package
             
             - Created another folder called "apps" in Books directory
             
             - Created File routes.js and pasted web code inside it.
             
            
![images of mongosse command and apps directory](Images/mongoose.png)
             
             
![images of routes file and code inside](Images/codes.png)

![routes](Images/codesroutes.png)
             
             
             
             - Created a folder named models in the apps directory.
             
             - In the models folder created a file named book.js
             
             - Pasted web codes inside the file book.js
             
             
![images of folder models and file book.js](Images/model.png)
             
![images of web code inside the *book.js*](Images/codes3.png)

![images of cat book.js code](Images/code4.png)
             
             


STEP 4 - *ACCESS THE **Routes** WITH *AngularJS**
             
            
 - *AngularJS* provides a web frame work for creating dynamic views in the web applications.
             
             - Change directory back into Books
             
             - Created a folder named Public
             
             - changed directory into public folder and created file script.js
             
![images of the public folder and file scripts](Images/model.png)
             
![images of web code inside script.js](Images/code5.png)

![images of cat script.js](Images/code5..png)
             
             
             - In Public folder created file named index.html
              
             - Inserted web codes into index.html
             
![images of index.html file](Images/code6.png)
             
![images of web code insides index.html](Images/code6..png)
             
             
             
             
             - Changed directory back to Books
             
             - Started the server 
             
             - Confirmation of server running
             
![images of server running](Images/server.png)
             
             
             
             - Opened New port TCP 3300 in the AWS web console inorder to access the BOOK REGISTER WEB APPLICATION.
             
             
![images of port tcp 3300](Images/tcp.png)

![images of curl](Images/curl.png)
             
             
             - Accessing the BOOK REGISTER APPLICATION ON THE WEB using the public DNS
             
             
![images of the completed BOOK REGISTER Application](Images/complete.png)

![images fo web book register completed](Images/webform.png)




         
         
         
