# google-dialogflow
 Notes taken learning Hands-on-google-dialogflow Udemy course. <br/>
 Hands on practice using
 
## Index

[10000 ft overview](10000ft_Overview.md)

### Google DialogFlow notes

* api.ai
* Free to use from gmail, no cost, free
* Linked to GCP, ensure you do not activate GCP demo / credits as it is not required for learning dialogflow

## Intents

* What does the user intend to ask the AI?
* Default fallback and default welcome intents are automatically added, but not fully configured.

* Fallback is triggered when agent is not able to find a match.

## Training
Train your agent

## Integrations
Integrate with third party software like slack, twilio, viber etc.,

## Fulfillment
Custom code specific to your business system. Can be written in Node.js or python etc.,


## Pre-built agents


## Small Talk
Make the bot conversational and chatty. Enable from Small talk tab.

## Entities
Slots or parameters that can be gathered from user pattern. Eg : City, Date, Room (Book A Room Intent)
We have built-in system entities provided by google dialogflow.

For example, we dont need to specify all possible dates or cities. The only entity we need to developer needs to define is room type.
This is business / developer defined entities.

- System Entities : Provided by google
- Developer Entities : Defined by developer with knowledge of business system
- User Defined Entities : Session specific data defined by a user. For example : a spotify playlist



## Events
There are two ways for a user to interact with your dialog flow. One is using natural language query
Second is using a Event, which is a pre-configured workflow to be invoked by an application.

## Annotations
Makes connections between user text responses to the slots in entities to fulfill an intent.
Automatically added by dialog flow. If not automatic, you can always map it manually on the user expression.

## Non-Linear Dialog
* Context and Follow ups:
-  Information user has provided early on forms the context
-  Context makes the conversation conversational.

* Linear Dialog:
- Collect the information necesary to complete the required action.
- Example : Book the room

* Non-Linear Dialog:
- Several branches depending on users response
- Example : Customer Feedback form / Customer Satisfaction Survey





    
    
    
