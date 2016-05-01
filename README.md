# akshayscu.github.io
# Tasks_App

1. Tasks_App: You can Create, Update and Delete your TasksLists including the Tasks in it using the App, it uses your Google account Tasks and keeps it updated when ou make changes!

2. Tasks_App, uses Google Tasks API in the backend. It needs a google account authorization sign-in.

3. Written purely in JavaScript and no Frameworks used.

4. Details:

=> index.html: Consists of sign in button that uses "Google Sign-in" to authenticate the user

=> oauthCallback.js: To handle the access token provided by Google Api.

=> homePageCtrl.js: Handles all the functionalities, such as Update, Delete & Create 'Task LISTS' as well as Update, Delete & Create 'TASKS' within the Lists!

=> taskListHandler.js: Handles the Operations performed on the 'Task LISTS'.

=> tasksHandler.js: Handles the Operations performed on the 'TASKS'.

=> templateStore.js: Helps with the Dynamic HTML creation!

=> signUpApp.js & todoApp.js: For future use, to provide more features!

(There is always one default list for the user at the start)

*How to Use:*
	
	1. Sign in with your Google account credentials.
	2. Once Authenticated:
		
		a. You can create New Task LISTS by clicking on the 'Add Task List'	
		
		b. You can delete the Task LIST by clicking the 'minus' symbol
		
		c. You can update the Task LIST by right-clicking on the Task LIST
		
		*Similarly for the TASKS within the LISTS:*
	
		a. You can create New TASK by clicking on the 'Add Task'	
	
		b. You can delete the TASK by clicking the 'minus' symbol
	
		c. You can update the TASK by right-clicking on the Task.
