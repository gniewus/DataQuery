# DataQuery
Bachelor Thesis: Design, Development, and Evaluation of a Voice User Interface for Queries on semistructured Data

# Architecture :

 - Event Handlers : 
 
EventHandlers.js states an entry point for every incoming request. At this point, we differentiate the the Initial Requests, IntentRequest and Unhanheld request. For every incoming Intent Request is forwarde to the accordingly to the state handlers. 

- State Handlers

Here, we investigate the current state of a dialog and pass it further accordingly. Currently there is only one state : "AskMode" 
