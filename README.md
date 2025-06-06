![alt text](OpenAPI.png)

# Docusign OpenAPI Specifications  

Docusign uses the OpenAPI (OAI) Specification - formerly known as "Swagger" - to describe its REST APIs. The goal of the OAI specification is to define a standard, language-agnostic interface to REST APIs which allows both humans and computers to discover and understand the capabilities of the service.  For more info see the official [OAI](https://github.com/OAI/OpenAPI-Specification) spec.

## The Swagger file

![](https://validator.swagger.io/validator?url=https://raw.githubusercontent.com/docusign/OpenAPI-Specifications/master/esignature.rest.swagger-v2.1.json) `esignature.rest.swagger-v2.1.json` - the full swagger file for Docusign's eSignature REST API v2.1

![](https://validator.swagger.io/validator?url=https://raw.githubusercontent.com/docusign/OpenAPI-Specifications/master/esignature.rest.swagger-v2.json) `esignature.rest.swagger-v2.json` - the full swagger file for Docusign's eSignature REST API v2

![](https://validator.swagger.io/validator?url=https://raw.githubusercontent.com/docusign/OpenAPI-Specifications/master/rooms.rest.swagger-v2.json) `rooms.rest.swagger-v2.json` - the full swagger file for Docusign's Rooms API v2

![](https://validator.swagger.io/validator?url=https://raw.githubusercontent.com/docusign/OpenAPI-Specifications/master/click.rest.swagger-v2.json) `click.rest.swagger-v2.json` - the full swagger file for Docusign's Click API v1

![](https://validator.swagger.io/validator?url=https://raw.githubusercontent.com/docusign/OpenAPI-Specifications/master/admin.rest.swagger-v2.json) `admin.rest.swagger-v2.json` - the full swagger file for Docusign's Admin API v2 and v2.1

![](https://validator.swagger.io/validator?url=https://raw.githubusercontent.com/docusign/OpenAPI-Specifications/master/maestro.rest.swagger-v1.0.0.json) `maestro.rest.swagger-v1.0.0.json` - the full swagger file for Docusign's Maestro API v1

![](https://validator.swagger.io/validator?url=https://raw.githubusercontent.com/docusign/OpenAPI-Specifications/master/webforms.rest.swagger-v1.1.0.json) `webforms.rest.swagger-v1.1.0.json` - the full swagger file for Docusign's WebForms API v1.1

![](https://validator.swagger.io/validator?url=https://raw.githubusercontent.com/docusign/OpenAPI-Specifications/master/navigator.rest.swagger.json) `navigator.rest.swagger.json` - the full swagger file for Docusign's Navigator API

## What can I do with a Swagger file? 

We use OpenAPI/Swagger files to build many of our developer tools including our [client SDKs](https://developers.docusign.com/docs/esign-rest-api/sdk-tools) using `swagger-codegen`. We also use the OAI specification to build our [API Docs](https://docs.docusign.com/esign/) and [API Explorer](https://apiexplorer.docusign.com/#/) tools.  What will you build?  Let us know by filing an issue in this repository.

### Vendor-specific extensions

Some post-processing is performed on our eSignature Swagger spec which includes adding a number of vendor-specific extensions prefixed with `x-ds-`. See the [Docusign-Extensions.md](Docusign-Extensions.md) file for more information.

### Releases

The DocuSign eSignature REST API is updated monthly. The Swagger file in this repository is also updated monthly. See the "Releases" tab for version information. The current release information is available from the [Developer Account (demo)](https://demo.docusign.net/restapi/service_information) and [production](https://www.docusign.net/restapi/service_information) platforms.

## Support

Please log issues through GitHub. We also have an active developer community on Stack Overflow, search the [DocusignAPI](http://stackoverflow.com/questions/tagged/docusignapi) tag.

## License

The DocuSign OpenAPI (Swagger) Files are licensed under the following [License](LICENSE).
