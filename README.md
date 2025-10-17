# MoEngage API Documentation

Comprehensive API documentation for the MoEngage platform, built with Mintlify. This documentation provides developers with complete reference guides for integrating with MoEngage's suite of APIs.

## Overview

This documentation covers MoEngage's extensive API ecosystem, including:

- **Product Catalog API** - Manage product catalogs, attributes, and product data
- **Campaigns API** - Programmatically manage and retrieve campaign data
- **Push Templates API** - Manage push notification templates
- **Data APIs** - Handle user data and analytics
- **Template APIs** - Manage various communication templates (SMS, Email, In-App, etc.)
- **Business Events API** - Track and manage business events
- **Recommendations API** - Leverage AI-powered product recommendations
- **And many more...**

## Features

- 📚 Complete API reference with interactive examples
- 🌐 Multi-language support (English & Japanese)
- 🔍 Searchable documentation
- 💡 Code examples and integration guides
- 🎨 Modern, responsive design
- 🔗 Direct links to MoEngage dashboard and support

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## API Authentication

All MoEngage APIs use a combination of Basic Authentication and a custom MOE-APPKEY header. You can find your credentials in the MoEngage Dashboard under Settings > Account > APIs.

## Publishing Changes

This documentation is automatically deployed when changes are pushed to the main branch. The deployment is handled through Mintlify's GitHub integration.

## Contributing

When updating API documentation:

1. Update the relevant OpenAPI specification files in `/api-reference/`
2. Test changes locally using `mint dev`
3. Commit and push changes to the main branch
4. Changes will be automatically deployed

## Need Help?

### MoEngage Support
- [MoEngage Help Center](https://help.moengage.com/hc/en-us)
- [MoEngage Dashboard](https://dashboard.moengage.com/v4)

### Documentation Issues
- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
- [MoEngage Blog](https://www.moengage.com/blog)
