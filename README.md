### Folder Structure
src<br/>
└─── app.js&ensp;&ensp;# Entry point for application<br/>
└─── config&ensp;&ensp;# Application environment variables and secrets<br/>
└─── controllers&ensp;&ensp;# Express controllers for routes, respond to client requests, call services<br/>
└─── loaders&ensp;&ensp;# Handles all startup processes<br/>
└─── middlewares&ensp;&ensp;# Operations that check or manipulate request prior to controller utilizing<br/>
└─── models&ensp;&ensp;# Database models<br/>
└─── routes&ensp;&ensp;# Express routes that define API structure<br/>
└─── services&ensp;&ensp;# Encapsulates all business logic<br/>
└─── test&ensp;&ensp;# Tests go here<br/>
└─── utils&ensp;&ensp;# App utilities