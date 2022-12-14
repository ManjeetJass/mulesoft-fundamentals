# Anypoint Platform Development: Fundamentals 



* **final-training-projects** folder contains training projects as on completion of module 13 of training. 
* **DIY** folder contains DIY projects of all modules. 



**DIY**

 * **DIY-06-1-customer-service-accounts** 

   * Sample endpoints:

     *	 http://localhost:8081/accounts-by-type?account_type=personal

     * http://localhost:8081/accounts-by-name?customer_name=Wendy Crafts

* **DIY-08-1-Customer-Service-Accounts**

  * Sample endpoints

    * http://localhost:8081/accounts-by-name?customer_name=Wendy Crafts

    * http://localhost:8081/accounts-by-type?account_type=personal

    * http://localhost:8081/create-accounts

      * [

          {

        ​    "name": "Rhea",

        ​    "type": "personal",

        ​    "address": "xxx yyy",

        ​    "air_miles": "100"

          },

          {

        ​    "name": "Ryan",

        ​    "type": "personal",

        ​    "address": "xxx yyy",

        ​    "air_miles": "110"

          }

        ]

* **DIY-08-2-Customer-Service-Accounts**
  * Sample endpoints
    * http://localhost:8081/account-transactions/4893
  
* **DIY-09-1-AccountsAPI-Implementation**
  * Sample endpoints
    * http://localhost:8081/api/accounts
    * http://localhost:8081/api/accounts?name=Wendy Crafts
    * http://localhost:8081/api/accounts?account_type=personal&name=Wendy Crafts
    * http://localhost:8081/api/accounts?account_type=personal
  
* **DIY-09-2-Customer-Service-Accounts**
  
  * Sample endpoints
    * http://localhost:8081/accounts-by-both?account_type=business&customer_name=Mat Siva&condition=AND
    * http://localhost:8081/accounts-by-both?account_type=business&customer_name=Mat Siva&condition=OR
  
* **DIY-10-2-Customer-Service-Accounts**

  * Sample endpoints
    * Condition error handling: http://localhost:8081/accounts-by-both?account_type=business&customer_name=Mat Siva&condition=O
    * Type error handling http://localhost:8081/accounts-by-both?account_type=busines&customer_name=Mat Siva&condition=OR
  
* **DIY-11-1-Customer-Service-Accounts**

  * Sample endpoints
    * http://localhost:8081/accounts-by-both?account_type=business&customer_name=Mat Siva&condition=OR
  
* **DIY-11-2-Customer-Service-Accounts**

  * Sample endpoints

    * http://localhost:8081/account-transactions/4893

* **DIY-12-1-Customer-Account-Records**

  * Edit "accountsDir" in config.yaml for csv files location. 
  
* **DIY-13-1-Customer-Account-Records**

  * Edit "accountsDir" in config.yaml for csv files location.  
  
* **DIY-13-2-Customer-Account-Records**

  * Edit "accountsDir" & "inputDir" in config.yaml for csv files location.  
