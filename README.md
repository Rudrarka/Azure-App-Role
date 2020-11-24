---
page_type: sample
languages:
- python
products:
- azure-active-directory
description: "This sample demonstrates a Python web application calling a Microsoft Graph that is secured using Azure Active Directory."
urlFragment: ms-identity-python-webapp
---
# Integrating Microsoft Identity Platform with a Python web application

## About this sample


This sample demonstrates a Python web application that signs-in users with the Microsoft identity platform and calls the Microsoft Graph.

1. The python web application uses the Microsoft Authentication Library (MSAL) to obtain a JWT access token from the Microsoft identity platform (formerly Azure AD v2.0):
2. The access token is used as a bearer token to authenticate the user when calling the Microsoft Graph to display the app role of the user.

3. The acces token is decoded and the scopes are displayed. 

