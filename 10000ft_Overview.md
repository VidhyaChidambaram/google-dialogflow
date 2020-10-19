# Google Dialogflow Overview
 - Use any SDK of choice to write fulfillment code. Seems better than Alexa UI.
 - Simple sign up via Google, delete account from DialogFlow -> Account -> Delete Account
 
## Core Concepts
 - Agent, Intent, Entities, Contexts, Fulfillment

## Key Terms

### User Expression 
 - Text fragment used by the user to construct the query
 - User will use the interface we have created using dialogflow (Viber, facebook, slack etc.,)
 
### Agent
 - Uses NLP to understand what it is that the user meant in the above User expression
 - Once agent is able to decode the User expression, it maps it to an Intent.
 - Transform user request to actionable data
 
### Intent
 - Defined by developer
 - Different actions that the code can execute
 - Example of intent:
    - Update my information
    - Delete my information
    - Get my information
 
### Fulfillment
 - Execute the action / intent above and create a response
 - Response in the form of text message is sent to the user

## Big picture data flow

- From User -> fulfillment <br/>
    ```User -> DialogFlow interface -> Agent -> Request -> Fulfillment -> Create Response```
- From fulfillment to user <br/>
    ``` Response -> Fulfillment -> Agent -> Dialogflow interface -> User```
    
Coding required only during fulfillment, otherwise mostly UI driven.