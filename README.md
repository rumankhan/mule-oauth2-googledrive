# mule-oauth2-googledrive
This solution is used to demonstrate oauth2 dance and retrieve files from google drive.

### Configurations:
Fill out below fields in the application. 
- oauth.clientid=<<fill your client id>>
- oauth.clientsecret=<<fill your client secret>>
- oauth.redirection.url=<<fill your call back url configured>>
To test, run the application and navigate to http://localhost:8082/login where you will be presented with google login screen.
After successful login, navigate to http://localhost:8081/ to retrieve files on google drive

###
More details can be found at the blog post: https://rumanblogs.com/authenticating-with-google-drive-in-mule-part-1-oauth2/
  
### Contributing
All pull requests are welcome
