# messengerbot


Steps to create your first Messenger Bot.

Step 1 : Create a Facebook Page

Step 2 : Create a Facebook App

Step 3 : In the Facebook App, Enable Messenger. Select the Facebook Page created to get the Page Access Token

Step 4 : Log in to api.ai and create an Agent. 

Step 5 : In Api.ai console, go to Domains, select "Small-Talk" and switch it ON.

Step 6 : Run this app (sudo node index.js). 

Step 8 : Go to Facebook App. Enter Webhook URL (Webhook URL = <SERVER_BASE_URL>/webhook)*, token string. select all the message subscription option. Click on Verify and Submit.

Step 9 : Open Facebook Page and start a conversation.

*To get https URL on your localhost, use ngrok or host your app on heroku.
