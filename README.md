# Facebook-API-Testing

### A simple Facebook API testing example using Postman tool.

##### In order to get it working on Postman, after importing the configuration files you must set the following environment variables:
- client_id
- client_secret

##### Also, you must generate a user access token on your Facebook developer dashboard and configure it in the section "Authorization" of the "Post" folder.

---

###### Tested endpoints:
- https://graph.facebook.com/oauth/access_token - Token generation and authentication
- https://graph.facebook.com/v2.12/me/feed - Publish a user comment
- https://graph.facebook.com/v2.12/{post_id} - Update a user comment

###### Files to import collection and environment configurations:
- [Facebook API Testing.postman_collection.json](Facebook%20API%20Testing.postman_collection.json)
- [Facebook.postman_environment.json](Facebook.postman_environment.json)

###### Test execution results:
- [Facebook API Testing.postman_test_run.json](Facebook%20API%20Testing.postman_test_run.json)

###### Test cases document:
- [Casos de testes - Desafio Sensedia.pdf](Casos%20de%20testes%20-%20Desafio%20Sensedia.pdf)
