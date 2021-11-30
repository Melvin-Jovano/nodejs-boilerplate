### Folder Structure
src
└───app.js          # Entry point for application
└───config          # Application environment variables and secrets
└───controllers     # Express controllers for routes, respond to client requests, call services
└───loaders         # Handles all startup processes
└───middlewares     # Operations that check or manipulate request prior to controller utilizing
└───models          # Database models
└───routes          # Express routes that define API structure
└───services        # Encapsulates all business logic
└───test            # Tests go here
└───utils           # App utilities