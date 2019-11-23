# ASP.NET REST Web API Basic Authorization Library
**Asmak9.AuthorizeRESTWebApiAK** is a 30 days free trial library that provides two main classe **RESTWebAPIAuthHeaderHandler** and **RESTWebAPIKey** for REST Web API basic authorization and API Key generation facility. You can install this library via Nuget package and enjoy 30 day free trial. You can use this library into your any ASP.NET REST Web API project. REST Web API authorization i.e. apiKeyName, apiKeyValue, username, password and licensKey (By Default empty) can be set via **RESTWebAPIAuthHeaderHandler**. In order to generate API Key, create your unique password and saltKey first then pass this information to **RESTWebAPIKey** class GenerateApiKey(...) method, this method wil return your API key.

### Nuget Installation Version 1.1.8: https://www.nuget.org/packages/Asmak9.AuthorizeRESTWebApiAK/

### [Buy License Key](https://bit.ly/354pOkv) Copyright (c) [Asma's Blog](https://www.asmak9.com/)

# Basic Usage for RESTWebAPIKey class

```C#

// Initialization.
string myPassword = "mypassword";
string mysaltKey = "mysaltkey";

// Generate API key.
string apiKey = RESTWebAPIKey.GenerateAPIKey(myPassword, mysaltKey);

```

# Basic Usage for RESTWebAPIAuthHeaderHandler class
Use below code in your project **Global.asax.cs** file i.e.

```C#

// Initialization.
RESTWebAPIAuthHeaderHandler authRegObj = new RESTWebAPIAuthHeaderHandler("myapiKeyName", "myapiKeyValue", "myusername", "mypassword");

// API authorization registration.
GlobalConfiguration.Configuration.MessageHandlers.Add(authRegObj);

```

# Examples

1. [ASP.NET REST Web API Basic Authorization](https://bit.ly/2pGrHVo)
2. [Generate REST Web API Key](https://bit.ly/2KNwcVD)

<br/>
<br/>
<br/>


Like, Share, Support, Subscribe!!!

#### YouTube: https://bit.ly/2sY1aBb 

#### Website: https://www.asmak9.com/

#### Facebook: https://www.facebook.com/AK.asmak9/

#### Twitter: https://twitter.com/asmak/

#### LinkedIn: https://www.linkedin.com/in/asmak9/ 
