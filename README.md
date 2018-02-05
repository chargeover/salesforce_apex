# Salesforce Apex + the ChargeOver REST API

Examples showing how to send data from Salesforce to ChargeOver via Apex trigger and the REST API

## Configuration within ChargeOver

You'll need to enable the ChargeOver REST API:

* See this guide: https://developer.chargeover.com/apidocs/rest/#getting-started


## Configuration within Salesforce

Within Salesforce, you need to allow Salesforce to call out to ChargeOver by:

* Navigate to SETUP > SECURITY > REMOTE SITES
* Click the ADD NEW REMOTE SITE button
* For the URL, enter your ChargeOver REST API endpoint


## Configuration within the example Apex code

* In ChargeOver.apxc, you'll need to swap in your URL, username, and password


## The Examples

* Push_Accounts_to_ChargeOver.apxt - this shows how to push Accounts in Salesforce to Customers in ChargeOver
* ChargeOver.apxc - helper methods