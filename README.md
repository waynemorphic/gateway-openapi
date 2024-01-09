## Vital

To use *Google Cloud Endpoints* to deploy and monitor the API Gateway configured with OpenAPI specification:

1. OpenAPI specification 2.0 (Swagger) should be used to create the spec file
2. There should be a Google Cloud account already set up
3. A Google Cloud Service Account should be created. This serves as the host for the spec file

## GCP Commands

1. Update Google Cloud components

  `gcloud components update`

2. Login to your Google Cloud Account

  `gcloud auth login`

3. Set PROJECT from default

  `gcloud config set project <YOUR PROJECT_ID>`

4. Deploy to Google Cloud

  `gcloud endpoints services deploy <openapi_spec_file_name.yaml>`

Wait for Operation to complete successfully

## URL

https://console.cloud.google.com/endpoints/api/echo-api.endpoints.verdant-art-410710.cloud.goog/overview?project=verdant-art-410710
