This repo was ispired by the following post https://medium.com/@gsarkar/build-a-csp-report-uri-endpoint-on-aws-serverless-caa6dc843c03.

Cloudfomation implemetnts Content Security Policy (CSP) reporting service URL, allowing to submit report that will be stored in the DynamoDb database created as a part of the template. 

To install the service please use the cloudformation template above to create stack. The template will deploy the api into the latest stage and will output the API URL endpoint for the stage. 
You might want to create a custom domain for the API endpoint to make it more robust. 
