# _nodeCommerce_

## About

The aim of this project is to create an ecommerce platform that is reactive. This project is separated into two sub-services - Frontend and Backend.

Here are the aims for each of the services:

### Frontend:

- Built on react
- Supports themes
- Supports 3rd party plugins (later)
- Is reactive and quick

### Backend:

- Built on apollo and graphql
- Allow the frontend to easily gather information required
- Provides authentication end-points
- Supports 3rd party plugins (later)
- Secure

## Plans by version:

### v0.1.0 (Current)

Backend first. Allow the creation of products, placing of orders, accounts - the most basic eCommerce CMS functionalities.
Once the MVP of the Backend is done, the Frontend should be developed to use the backend functionality. This should provide with a proof of concept (PoC) platform, that later can be reflected upon and planned out more in-depth, in that way laying the foundation of the complete.

## Development guidelines:

- There must be unit tests. I will try to develop this in a TDD manner at the best of my capabilities.
- Let the linter format your code (I think I still need to set this up)
- Features must be introduced via PRs (both pull requests and peer reviews)

That's it for now...
