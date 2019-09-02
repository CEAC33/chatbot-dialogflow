# chatbot-dialogflow


## Connect Facebook App with DialogFlow

- Create the Facebook Page - https://www.facebook.com/pages/creation/
- Create a Facebook Application - https://developers.facebook.com/
```
My Apps > Add New App > Insert a Name
```
- DialogFlow Setup - https://dialogflow.com/ 
- Create a New Agent -  https://console.dialogflow.com/api-client/#/agent/
```
Create New Agent > Insert a Name > Select Language & Default Timezone
```
- Integrate it with Facebook (Generate Callback URL)
```
Integrations > Enable Facebook Messenger > Now we have the Callback URL
```
- Connect DialogFlow and Facebook App - https://developers.facebook.com/apps/
```
Messenger > Set Up > Select your FB Page > Continue as ... > Ok > Page Access Token is created
```
- Copy and Paste this `Page Access Token` in your DialogFlow Messenger Integration
- Add the `Verify Token`, this is like a password that you set > Start > Copy your `Verify Token`
- Go Back to FB App > Setup Webhooks > Paste `Verify Token`
- Go to your DialogFlow Agent and copy `Callback URL` > Paste it on your FB App
- Add subscriptions `messages` & `messaging_postbacks` > Save
- Select the Page > Done!
