# Mobile SDK

* Consumer Key - A value used by the consumer—in this case, the Mobile SDK app—to identify itself to Salesforce. Referred to as `client_id`.
* Access Token - A value used by the consumer to gain access to protected resources on behalf of the user, instead of using the user’s Salesforce credentials. The access token is a session ID, and can be used directly.
* Refresh Token - A token used by the consumer to obtain a new access token, without having the end user approve the access again.
* Authorization Code - A short-lived token that represents the access granted by the end user. The authorization code is used to obtain an access token and a refresh token.
* Connected App - An application external to Salesforce that uses the OAuth protocol to verify both the Salesforce user and the external application.
