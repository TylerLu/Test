# README 1523

[Test ab](Deply.pptx)

## Demo scenario overview and flow

See the [Demo Script](Demo Script.pptx) slide deck.

## Running the demo

Follow the steps in [Demo Script](Demo Script.pptx) slide deck.


## Demo scenario overview and flow

See the [Demo Script](Demo%20Script.pptx) slide deck.

## Running the demo

Follow the steps in [Demo Script](Demo%20Script.pptx) slide deck.


## TEST  u-88

### TEST 1

#### TEST 11

#### TEST 12

**TEST Bold**

### TEST 2



This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


AAA

BBB


Click the Deploy to Azure Button:

   [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FTylerLu%2FEDUGraphAPI-Ruby%2Fmaster%2Fazuredeploy.json)
   
   
   - In the Redirect URI (optional) section, select **Web** in the combo-box and enter the following redirect URIs: `http://localhost:8000/account/signin/azure_ad/callback`.

     > **Note:** The redirect URI is set for `localhost` instead of `127.0.0.1` which is the default IP Address used by the Django development server. This is because Azure AD requires that the redirect URL **must start with HTTPS or http://localhost**.

     > If you desire, you can enable SSL for the development server and add another redirect URI like `https://127.0.0.1:8000`.
