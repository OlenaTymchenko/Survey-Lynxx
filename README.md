# Survey-Lynxx

## To run the server:
```cd server && npm start```

You will receive a message: 'Express server is listening on port 5007'. You will also need to point the index.js to client/src in ```const path = __dirname + '/build'``` instead of build folder. 

---
Survey data is located in json file in routes/style-pages/data folder. You will also need to change the name in survey/survey-app.js

---

Express serves static React files so the application is using one port.

This is a production version of the app running a React *build folder* with Express on Heroku. 

**Main React application for development** is in a survey-app/client folder. 

---

Express index.js receives an API call from React to save the user responces in json format with unique date and time name. 

React calls Express api/handle from *src/routes/style-pages/survey/component.js* in triggerBackendUpdate function. This can be changed to a database call. 

:slightly_smiling_face:	:smiley: :upside_down_face:
