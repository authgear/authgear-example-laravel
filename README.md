# An Example App For Adding User Authentication with Authgear and OAuth 2.0 to a Regular PHP Website.

## What is Authgear?
Authgear is a secure authentication and user management platform. It uses OpenID Connect (OIDC) and OAuth 2.0 to identify who a user is and grant authorization to protected resources.

This repository contains example code for using Authgear in a Laravel project. The example Laravel app allows users to log in using OAuth 2.0. Hence this could also be a good starting point for learning how to add OAuth 2.0 user authentication to a Laravel app.

## How to Run the Project
To run this project on your computer do the following:
1. Sign up for a free Authgear account.
2. Create an Authgear app, and add the configuration for your Authgear project to the Laravel projects env file using the following fields:

```
AUTHGEAR_PROJECT_URL = ""
AUTHGEAR_APP_CLIENT_ID = ""
AUTHGEAR_APP_CLIENT_SECRET = ""
AUTHGEAR_APP_REDIRECT_URI = ""
```
To run the app on you local mechine, run the following commands:

```
php artisan migrate
```
and

```
php artisan serve
```

For a more detailed step-by-step guide on how to use Authgear, check out this post:
[https://docs.authgear.com/get-started/regular-web-app](https://docs.authgear.com/get-started/regular-web-app)

