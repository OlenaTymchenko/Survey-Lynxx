# Survey-Lynxx

## To run the surver:
```cd server && npm start```

You will receive a message: 'Express server is listening on port 5007'

---

Express serves static React files so the application is using one port.

This is a production version of the app running a React *build folder* with Express on Heroku. 

**Main React application for development** is in a client folder. 

---

Express index.js receives an API call from React to save the user responces in json format with unique date and time name. 

React calls Express api/handle from *src/routes/style-pages/survey/component.js* in triggerBackendUpdate function. This can be changed to a database call. 

:slightly_smiling_face:	:neutral_face: :upside_down_face:
