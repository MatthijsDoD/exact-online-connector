# Exact Online Connector
**Connector Azure Data Factory and the Exact Online REST API**

In this Readme file is a **step-by-step** configuration of your Exact Online REST API connector. 

**Access token** - Expires after 10 minutes
**Refresh token** - Expires after 30 days

## **STEPS:**
1. First you need to register an application in the Exact Online App Centre.
2. You request an authorization code from the API, using your client id and a redirect URI.
3. Once you have the code, you make a new call to the API using the code and your client secret to get your first pair of refresh/access tokens.
4. We store these in the database, and now we can request access tokens when we want.

## Register Your Exact Online App
First, sign up for a developer's subscription [here](https://support.exactonline.com/community/s/knowledge-base#All-All-DNO-Content-developerssubscriptiont) and fill in all the fields. 
