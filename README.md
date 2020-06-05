A simple Gmail client made with [Create-React-App](https://github.com/facebook/create-react-app) and [Chakra UI](https://github.com/chakra-ui/chakra-ui/) using [Gmail's public Javascript API](https://developers.google.com/gmail/api/).

**How does it work?**  
The account sign-in and authentication process is **totally managed by Gmail's secure protocols**.  The workflow is as follows:

 - First-time users will see a landing page with a button to sign in to
   Gmail.
 - Once successfully signed-in, Gmail will display a screen asking the
   user for permission to use the account in the application.
  - After permission is granted, the application will load all account data and display the Inbox folder

**IMPORTANT:** The application does **NOT** store or persist any account or user data in any way at all. It simply fetches data from Gmail's API and displays it in the browser.


**Requirements:**

- All Gmail API requests require an ***API Key*** and an ***OAuth 2.0 Client ID***. You can follow [these instructions](https://developers.google.com/fit/android/get-api-key) to obtain those credentials. Then, store those two values in the ***[.env](https://facebook.github.io/create-react-app/docs/adding-custom-environment-variables)*** file located in the root folder by replacing `<YOUR_API_KEY>` and `<YOUR_CLIENT_ID>` respectively.


Features:

- Responsive Viewport (with Bootstrap and CSS3 flexbox styling)

- Read, Send, Reply, Move to Trash.

LICENSE: [MIT License](https://opensource.org/licenses/MIT)
