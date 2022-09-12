# j4x-api-using-swagger-ui

>An attempt to help the Joomla! 4.x early adopters mainly focused for developers. It's an unofficial example of using an OpenApi 3.0 generated schema of [100+ Joomla! 4.x Web Services endpoints](https://github.com/alexandreelise/j4x-api-collection/blob/master/latest-postman-apis/j4x-webservices-openapi-schema.yaml), this time using [Swagger UI](https://github.com/swagger-api/swagger-ui)

### USAGE
1. To edit the list of "servers" available in the dropdown list, you have to fork the 
schema repo from [here](https://github.com/alexandreelise/j4x-api-collection/blob/master/latest-postman-apis/j4x-webservices-openapi-schema.yaml) and change the url part in servers list. By default, it's https://example.org

2. Once you dit that, fork this repo and edit the file dist/swagger-initializer.js
and put your own url for your schema. If you don't want to for this repo, 
just copy/paste your schema url in the swagger ui app in this repo GitHub page

3. Follow the instructions on the swagger ui app it should be self-explanatory
