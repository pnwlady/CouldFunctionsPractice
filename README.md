# CloudFunctionsPractice
Learning Cloud Functions in NodeJS

## 1. To deploy the translate cloud function
    gloud functions deploy translate \
    --trigger-http --stage-bucket mybucket

from https://www.youtube.com/watch?v=CoKJiGCVzAg

## 2. Excape Html example 
    Dir helloworld/index.js
from https://cloud.google.com/functions/docs/bestpractices/tips

## 3. Example of performance best practices: using global variable to cache object for future invocations
    Dir tips/index.js
from https://cloud.google.com/functions/docs/bestpractices/tips

## 4. Lazy initialization of global variables
    Dir tips/lazy.js
from https://cloud.google.com/functions/docs/bestpractices/tip

## 5. Sendgrid Node app with Google Clouse - practicing gcloud cli
    server.js, Dir views
from https://cloud.google.com/community/tutorials/send-email-with-sendgrid-and-nodejs-on-google-app-engine

## 6 Promises examples in Typescript
    functions/index.ts
    1.  Promises with HTTP Triggers in the cloud
        Calling to a firestore app to get weather data, handling the response, sending it to the client in json, error handling
        https://www.youtube.com/watch?v=7IkUgCLr5oA
    