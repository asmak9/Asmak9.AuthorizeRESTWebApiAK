# ASP.NET REST Web API Basic Authorization Library
**Asmak9.AuthorizeRESTWebApiAK** provides two main classe **RESTWebAPIAuthHeaderHandler** and **RESTWebAPIKey** for REST Web API basic authorization and API Key generation facility. You can install this library via Nuget package and enjoy 30 day free trial. You can use this library into your any ASP.NET REST Web API project. REST Web API authorization i.e. apiKeyName, apiKeyValue, username, password and licensKey (By Default empty) can be set via **RESTWebAPIAuthHeaderHandler**. In order to generate API Key, create your unique password and salt first then pass this information to **RESTWebAPIKey** class GenerateApiKey(...) method, this method wil return your API key.

### Nuget Installation Version 1.0.0: https://www.nuget.org/packages/CSVLibraryAK/

### For detail article visit [C#.Net Import/Export CSV Library](https://bit.ly/2XYnh8g) at [Asma's Blog](https://www.asmak9.com/)

# Basic Usage

```C#

// Initialization.
bool hasHeader = true;
string importFilePath = "C:\\import.csv";
string exportFilePath = "C:\\export.csv";

// Impot CSV file.
DataTable data = CSVLibraryAK.Import(importFilePath, hasHeader);

// Export CSV file.
CSVLibraryAK.Export(exportFilePath, data);

```

# Examples

1. [ASP.NET REST Web API Authorization](https://bit.ly/2XVaXcb)

<br/>
<br/>
<br/>


Like, Share, Support, Subscribe!!!

#### YouTube: https://bit.ly/2sY1aBb 

#### Website: https://www.asmak9.com/

#### Facebook: https://www.facebook.com/AK.asmak9/

#### Twitter: https://twitter.com/asmak/

#### LinkedIn: https://www.linkedin.com/in/asmak9/ 
