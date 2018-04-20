# MaaS360_API
This is a MaaS360 API which requests a MaaS360 token and pull the user and device data from your MaaS360 Account.

Type “npm install” in your terminal to use the “package.json” to download the necessary dependencies and get started.
{
  "name": "maas360_api",
  "version": "1.0.0",
  "description": "MaaS360 API",
  "main": "app.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Jonas Schindzielorz",
  "license": "ISC",
  "dependencies": {
    "body-parser": "^1.18.2",
    "ejs": "^2.5.8",
    "express": "^4.16.3",
    "node-fetch": "^2.1.2",
    "xmldom": "^0.1.27"
  }
}


You will need the required information to great an MaaS360 token which are provided by MaaS360:
{
			"authRequest": {
          	"maaS360AdminAuth": {
            "billingID": "",
            "platformID": "",
            "appID": "",
            "appVersion": "",
            "appAccessKey": "",
            "userName": "",
            "password": ""
          }
        }
}

Once you have this, type the data into the index view and you can test your own MaaS360 API.

Also, you want to take a look at this:

URL Generator:
https://maas360apidocs.mybluemix.net

WebServices Reference guide:
https://ibm.box.com/v/MaaS360webservices

How to connect to MaaS360:
https://www.ibm.com/developerworks/community/forums/html/topic?id=00000bb7-eeea-40f7-8635-6f442583698b