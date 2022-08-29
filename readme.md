{
    "definitions": {
      "general_settings": {
        "type": "object",
        "title": "GeneralSetting",
        "description": "CIT general Settings",
        "properties": {
          "data": {
            "type": "object",
            "properties": {
              "id": {
                "type": "string"
              },
              "type": {
                "type": "string"
              },
              "attributes": {
                "type": "object",
                "properties": {
                  "orgName": {
                    "type": "string"
                  },
                  "subdomainName": {
                    "type": "string"
                  },
                  "subdomainNameFormatted": {
                    "type": "string"
                  },
                  "timeZoneName": {
                    "type": "string"
                  },
                  "date_format": {
                    "type": "string"
                  },
                  "dateFormatID": {
                    "type": "number"
                  },
                  "id": {
                    "type": "number"
                  }
                }
              }
            }
          }
        }
      }
    }
  }