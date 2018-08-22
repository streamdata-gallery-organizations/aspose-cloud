{
  "info": {
    "name": "Aspose.Cloud https://api.aspose.cloud/oauth2/token",
    "_postman_id": "60525fa1-38f5-4f2d-a4e1-3367e4be31cc",
    "description": "Get Access/Refresh Token",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tokens",
      "item": [
        {
          "id": "8b141fe1-d065-498d-8c94-9302ef9b740a",
          "name": "Oauth2TokenPost",
          "request": {
            "url": "http://api.aspose.cloud/oauth2/token",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "client_id",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "client_secret",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "grant_type",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Get Access/Refresh Token"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ab3ced4-143c-42c9-b219-cd7384689830"
            }
          ]
        }
      ]
    }
  ]
}