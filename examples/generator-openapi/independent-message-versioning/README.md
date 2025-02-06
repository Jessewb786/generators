# EventCatalog OpenAPI Example - Independent Message Versioning

This example shows you how you can use the `x-eventcatalog-message-version` extension to assign a version to each message in your OpenAPI file.

By default EventCatalog will use the version of your OpenAPI file for all messages in that specification. 

If you prefer to assign a version to each message, you can use the `x-eventcatalog-message-version` extension.

This example contains:

- Assigning a version to each message in an OpenAPI file
- Using EventCatalog with many OpenAPI Files
- Assigning OpenAPI files to domains in the eventcatalog.config.js file

### Getting Started

1. Clone this project
1. Run `npm install`
1. Get a OpenAPI license key from [OpenAPI](https://eventcatalog.cloud) (14 day free trial)
1. Run the generators `npm run generate`
1. Run the catalog `npm run dev`
1. View your catalog at https://localhost:3000

### Features for OpenAPI Plugin

- Auto versioning of domains, services and messages
- Document events, queries and commands using custom extensions to OpenAPI
- Assign each route/message a version independent of your OpenAPI version
- Visually see OpenAPI files in your catalog.
- And much more...

To dive into how this plugin can help you, you can read the [OpenAPI Plugin Docs](https://www.eventcatalog.dev/integrations/openapi)




