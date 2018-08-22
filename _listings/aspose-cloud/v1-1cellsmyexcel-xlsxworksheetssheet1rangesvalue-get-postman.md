{
  "info": {
    "name": "Aspose.Cloud Gettings Cells Data based on Named Range",
    "_postman_id": "6bf7826b-5427-44be-b7ec-4e8864af1c01",
    "description": "Gettings Cells Data based on Named Range",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tokens",
      "item": [
        {
          "id": "6cdeb58e-245f-4ba2-8c83-bf694dcec6e8",
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
              "id": "8dc2ff01-8705-4606-b565-ed821034af2e"
            }
          ]
        }
      ]
    },
    {
      "name": "Spreadsheets",
      "item": [
        {
          "id": "52a03ee2-9285-4f6c-b1e7-e26a70b1ca51",
          "name": "V11CellsMyExcelXlsxWorksheetsSheet1RangesValueGet",
          "request": {
            "url": "http://api.aspose.cloud/v1.1/cells/MyExcel.xlsx/worksheets/Sheet1/ranges/value?columnCount=%7B%7D&firstColumn=%7B%7D&firstRow=%7B%7D&rowCount=%7B%7D",
            "method": "GET",
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
              "mode": "raw"
            },
            "description": "Gettings Cells Data based on Named Range"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f4a8f32-ada7-4be1-a1af-89f4276cb3ad"
            }
          ]
        }
      ]
    }
  ]
}