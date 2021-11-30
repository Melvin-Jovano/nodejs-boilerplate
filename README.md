### Folder Structure
src<br/>
└───app.js          # Entry point for application<br/>
└───config          # Application environment variables and secrets<br/>
└───controllers     # Express controllers for routes, respond to client requests, call services<br/>
└───loaders         # Handles all startup processes<br/>
└───middlewares     # Operations that check or manipulate request prior to controller utilizing<br/>
└───models          # Database models<br/>
└───routes          # Express routes that define API structure<br/>
└───services        # Encapsulates all business logic<br/>
└───test            # Tests go here<br/>
└───utils           # App utilities