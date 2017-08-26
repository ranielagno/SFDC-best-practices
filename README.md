# Salesforce Best Practices
# With Great Power Comes Great Responsibility!

The best applications are coded properly. The "properly" means the code not only does its job well, but is also easy to understand, add to, maintain and debug.

Coding standards are great! We want to ensure that the Salesforce.com org is self documented. The consistent and well-written code is critical to ensuring high quality standards across all applications. 

Here you will find the Best Practices (Naming Conventions & Coding Standards) of following components of Salesforce.com org:
1. Custom Objects
2. Custom Fields
3. Apex Triggers
4. Apex Classes
5. Re-factor Apex Classes

### Custom Objects
1. Custom Object names should be <b>CapitalizedCamelCase</b><p/>
<font size="5" color="green">Yes this one</font>
2. e.g. SalesOrder__c (Yes this one!)
3. Sales_Order__c (Not this one!)

### Custom Fields
1. Custom field names should be <b>CapitalizedCamelCase</b><p/>
2. e.g. SalesAmount__c (Yes this one!)
3. Sales_Amount__c (Not this one!)

### Apex Triggers
1. Apex Triggers names should be <b>CapitalizedCamelCase</b><p/>
2. e.g. AccountTrigger, SalesOrderTrigger,  (Yes this one!)
3. 
1. Apex Triggers should be Bulkified.
2. Apex Triggers should be implemented with NO Business Logic in it rather calling an Apex Trigger Handler to handle the Business Logic.

### Apex Classes
1. 