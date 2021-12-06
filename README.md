### Folder Structure
src<br/>
└─── app.js&emsp;&emsp;&emsp;&emsp;# Entry point for application<br/>
└─── config&emsp;&emsp;&emsp;&emsp;# Application environment variables and secrets<br/>
└─── interfaces&emsp;&emsp;&emsp;&emsp;# Application interfaces<br/>
└─── controllers&emsp;&emsp;# Express controllers for routes, respond to client requests, call services<br/>
└─── loaders&emsp;&emsp;&emsp;&ensp;# Handles all startup processes<br/>
└─── middlewares&emsp;# Operations that check or manipulate request prior to controller utilizing<br/>
└─── models&emsp;&emsp;&emsp;&ensp;# Database models<br/>
└─── routes&emsp;&emsp;&emsp;&ensp;&ensp;# Express routes that define API structure<br/>
└─── services&emsp;&emsp;&emsp;# Encapsulates all business logic<br/>
└─── test&emsp;&emsp;&emsp;&emsp;&emsp;# Tests go here<br/>
└─── utils&emsp;&emsp;&emsp;&emsp;&ensp;# App utilities