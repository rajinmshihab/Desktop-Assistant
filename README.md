### Desktop-Assistant
A desktop assistant using Python.

### System Design

	The system is designed to be simple and precise. The functions are set up to be accurate based on performance. The keyword ‘assistant’ is required to be present before every command progression.




### Features

**Voice Activation & Exception Handling**

The system will be activated once the code runs and will stand by in listening mode. The user will speak out the questions or task commands in a specific manner for the system to acknowledge and carry out the command. The system will require a wake keyword to activate its core features, or it will ignore the command (as it will not understand) and return to listening mode. The wake keyword in this case is ‘Assistant’. If the requirements are not met for each command, the assistant will reply that it does not understand the command. 


**Greetings**

The user can greet the assistant using specific keywords and the assistant will greet the user back. The keywords are as follows – 
1.	Hi.
2.	Selamat pagi.
3.	Hello.
4.	Hey there.
The assistant will reply using any of the same greeting responses.

**Date Information**

The user may ask the assistant what the date is, and the assistant will provide the user with the entire day and month as well as the day of the week. The command for this feature is – “What is the date today”. The assistant will reply in a format such as – “Today is Wednesday, July the 26th”.


**Open Application**

The user can ask the assistant to open any application existing on the user’s computer. However, that requires preset application routes that determine where the application’s (.exe) file is. For now, the system will be able to open the following – 
•	Google Chrome
•	Microsoft Word
•	Microsoft PowerPoint 
•	Microsoft Excel
•	Visual Studio Code
The command for this feature is – “Open Google Chrome”. The assistant will reply with “Opening” and carry it out.

**Open Any Website**

The user may ask the assistant to open any websites existing throughout the internet. However, it requires clearly speaking out the name of the website as it will use that as the argument for the URL of the website. The command for this is – “Open a website”, followed by another cue for providing the website name.

**Open Keyword Specific Websites**

There are some specific websites that can be opened just by using the open command and saying out their name. More websites can be configured in a similar way for easier access by providing the URL within the code. The system can now open the following websites directly using their name – 
•	Google
•	YouTube
•	StackOverFlow
The command for this feature is – “Open YouTube”. 

**Searching Information on Google**

The assistant can search for any keywords given to it by the user via google. It uses the ‘Search’ or ‘Google’ command to search for any following keywords given by the user. It uses Google’s API and Authorization API to carry this out. The command for this feature is similar to – “Google John Doe” or “Search John Doe”. 

**Searching on YouTube**

	The assistant can search YouTube for any open-ended query the user gives it. The assistant will open the browser, head to YouTube and search for the given argument and show the results to the user. The command for this feature is – “Search YouTube John Doe”. 

**Searching Music on Spotify**

	The assistant can search Spotify for any open-ended query the user gives it. The assistant will open the browser, head to Spotify and search for the given argument and show the results to the user. The command for this feature is – “Search Spotify John Doe”. 

**Creating a Folder**

The assistant can create a folder on the user’s computer and will ask the name of the folder as well as where to create the folder. The command for this feature is – “Create a folder” and that will be followed by name-based input requirements.

**Location Information**

The user may ask the assistant where a specific location is. Provided that the assistant understands the name correctly, it will open google maps and show where that specific location is. The example command for this feature is – “Where is Kuala Lumpur”.

**Weather Information**

The assistant can provide the weather of a city. The user needs to provide the name of the city to the assistant, and it will provide temperature, humidity, and overall weather description of that city. The command for this feature is – “What is the weather in Kuala Lumpur”. The assistant will reply in a format such as – “The temperature in Celcius is 29.5 The humidity is 72 and The weather description is overcast clouds”.

**Jokes**

The user can ask the assistant to tell a joke and the assistant will carry it out by telling the user random jokes every time. The command for this feature is – “Tell me a joke”.

**Conversation Log**

The conversation of each day is always logged in separate files in the system. The log can be asked to be opened and the assistant will show the user the log for that day. The logs are available for further data analysis for development should the user choose to provide access to them to the developers. The process is carried out automatically, but the user can ask the assistant to open to log for the day. The command for this feature is – “Open our conversation log for today”. 

**Listening Termination**

If the user chooses to keep the system running continuously, he can do that. If he wishes to pause the listening feature of the assistant for a specific time for privacy or any other reason, he may ask the assistant to stop listening for by providing a specific time duration. The command for this feature is – “Stop Listening” or “Do not listen”. This will be followed by another cue for providing a specific time.



### I will try to add more features if I get more time as I move forward.
