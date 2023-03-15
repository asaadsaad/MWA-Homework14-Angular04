# MWA - Homework 14 - Angular 04
### Backend Application (Express)
* Create a Restful public API for `POST /api/users/login` and `POST /api/users/signup`, after sign-up or sign-in, the backend API will generate a JWT and send it to your Angular app. Password must be encrypted (use `bcrypt` and `jsonwebtoken` packages)
* Create a middleware to verify and allow tokenized requests to pass through your protected routes. 
  
### Frontend Application (Angular)
* Use Angular router and create two public sign-up and sign-in forms.
* Create a guard to proctect other routes and add an interceptor to attach your token to the request header. (make sure all requests have the JWT in the request header (use intercepter) so the backend API will approve the request, your frontend route should be protected with a Guard so only logged in users can access to private components).



