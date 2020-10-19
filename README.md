# SPS-7160-Movie-ticketing-bot
[Integration of IBM Watson Assistance with Node-RED Services]

   This is repository is aimed at helping movies lovers to get started with understanding how to use Watson Assistant service to create a user-friendly chat bot that will book seats to a movie for you. n this project, we will be building a chatbot using Watson assistant. This will be done using a features called IBM Watson Assistant Lite and Node-RED UI Services. This chat should have the following capabilities:
   
   @ Give the list of movies available
   @ The Bot should be able to show different show timings
   @ When a movie is selected the bot should show the availability of tickets and their respective prices.
   @ The bot should be in a position to book tickets.

Youtube Link
---------------------------------

      https://youtu.be/L7EiRYdgSfw


# Watson Assistant
The [Watson Assistant](https://www.ibm.com/watson/ai-assistant/) service available as a Platform as a Service (PaaS) on IBM Cloud provides a AI tooling that can easily allow creating converstaional solutions that fits one's business needs. 

# Basic Concepts & Terminologies
## Workspace
A workspace in Watson Assistant is a container for all artifacts that define the behaviour of your system, i.e. Chatbot.

## Utterance
An utterance or user example is an input that a user provides when prompted, including questions and statements.

## Intent
An intent is the purpose expressed by user input, which usually acts as a label for a group of utterances.
For instance, if "Where can I find the gym?" is the question provided by a user, the Watson Assistant service understands that the user’s intent is to ask about the location of something (in this case, the gym, which is called the entity).

## Entity
An entity is usually a classification of objects aimed to help alert the response to an intent.
Using the same example of the user asking "Where can I find the gym?", the Watson Assistant service understands that the entity being asked about is the gym. The entity could have been something else like the restaurant, to which the Watson Assistant service would have provided a different response, despite the intent being the same.

## Context
Context is information gathered from an external source to customize responses.

## Response 
A response is what the Conversation service returns to the user’s utterances based on the detected intent, and entity can be in the form of text or an action like displaying a map.

## Dialog
A dialog defines the conversational flow, which is simply a logical flow that determines responses based on a met condition. The dialog flows in a top-to-bottom, left-to-right fashion.

## Dialog Node
A diaglog node is a single interaction in a conversation that is triggered when a condition is met and provides a response back to the user.

## Slots
Slots are considered the easiest way to gather information from users, allowing what usually takes serveral dialog nodes to be consolidated into a single node.

# Process 
## Sign up on IBM Cloud
An IBM Cloud account - A lite account, which is a free of charge account that doesn’t expire, can be created through going to [IBM Cloud](https://cloud.ibm.com/).

## Create a Watson Assistant service
1.  Select **Catalog** found at the top right of the page.
2.  Click on **Watson** from the menu on the left, which you can find under **Platform** services.
3.  Select **WWatson Assistant (formerly Conversation)**.

## Importing a workspace
Alternatively, instead of going step-by-step, we can import the entire workspace containing all defined intents, entities and the dialog flow.
1.  In the main page of the Workspaces, click on the arrow found beside **Create** that is next to **Workspaces** title.
2.  Select the file called *skill-myfirst-skill.json*, which can be found in this repository.

## Integrate It into an Movie ChatBot Application and Deploy it to Node-RED Service.
This can be done by following the steps found in this [Github repository](https://github.com/watson-developer-cloud/assistant-simple). The difference is that we will be using the Watson Assistant service and workspace we just created. 
        
    Install node-red-dashboard nodes from manager pallete option.
    import the "assistant updated flow with audio out and image.json" file into the Node-Red interface by using import option.

Seetharamaiah Vadde
IBM Software Technical Trainer,
IBM Carrier Education,
Email: vadde.seetha@gmail.com'
SmartInternZ Email: ram.javaapps@gmail.com
Mobile : +91 7396455803 (WhatsApp)
Tamil Nadu, Chennai- 600001
@Linkdin : https://www.linkedin.com/in/seetharam...
@Youtube Channel: https://www.youtube.com/channel/UCkJC...
