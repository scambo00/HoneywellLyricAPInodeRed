# HoneywellLyricAPInodeRed
access hoenywell lyric API with node red
# Integrating Wink Node Red and a custom "Action on Google" using API.AI
This will detail step by step how to import a prebuilt "Assistant Action" and how to keep it private (ie. you can use the Action in your own Google Home device, but it will not be publicly available).
The idea is to create an flow for wink node-red (webhook) that is triggered by an Action built with API.AI.  
## 1)API.AI
API.AI is a development tool for conversational end points. It allows to create a natural language interactions action for Google Home.
### 1.1)Create an account
You must create the account with the same Google email that you use to control your Google Home.
* Create an account on [API.AI](https://api.ai/):

### 1.2)Create Agent
Once we have signed up, we will be taken straight to the Api.ai interface where we can create our virtual AI assistant. Each assistant we create and teach specific skills to is called an “agent” in Api.ai. So, to begin, we create our first agent by clicking the “Create Agent” button on the top left hand side:
<img src='/images/createAgent2.png'/>
On the next screen, we enter in our agent’s details, including:
* Name: This is just for your own reference to differentiate agents in the api.ai interface. You could call the agent anything you would like, (I chose WinkNodeRed).
* Description: A human readable description so you can remember what the agent’s responsible for. This is optional and might not be needed if your agent’s name is self-explanatory.
* Language: The language which the agent works in. For this tutorial, we will be choosing English.

When you have input your agent’s settings, choose “Save” next to the agent’s name to save everything:

### 1.3)Import Agent
Download the following file which is a prepopulated Agent for the wink node-red interface.  This file will be imported as described.
* [winkNodeRed_0_1.zip](winkNodeRed_0_1.zip)
* In "Agent Setting"  Click on "Export and Import" and select "Import from zip"

<img src='/images/importAgent.jpg'/>
