
Set up:
1.Install Node and mongodb 
2.download the code into your local machine
3.open command prompt from the folder
4.type "npm install", this will install all the node dependencies
5.Go to MongoDB installed folder till bin,
		Run mongod.exe (make sure you have C:/data/db folder created)
6.Create a folder “views” in the root folder where you have downloaded the code and place your index.html in the "views" folder
		(Use name "index.html" for the initial page and place that in the "views" folder.)
7.Create a folder “client”  in the root folder and place your UI code(your angular js codes for the assignment) in that folder(if 		you want you can create sub folders inside "client" folder)
8. Please follow the basic steps while writting your UI code	
		While creating a router, mention template url as "client/<your path>"(append "client/" to your template urls, since you 		placed your code inside the folder "client" )
		
		Use server calls as below:
			Creating an employee: /add   , Method: POST
			Viewing employee details: /view   , Method: GET
			Updating employee details: /update/:id  , Method: PUT
			Deleting employee details: /delete/:id , Method: DELETE
9.Run the app using "node app.js"
10.Go to browser and hit url : http://localhost:8888/index	
