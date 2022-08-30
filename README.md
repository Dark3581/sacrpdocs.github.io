# SACRP Framework Documentation

This repo contains all documents related to the SACRP Framework documentation
site. This goes fully in-depth to all features included within the Framework,
from character creation to interaction with other players.

## Requirements

The following requirements and dependencies are used by the documentation:

- [`Node.js`](https://nodejs.org) version 16.14+
- [`yarn`](https://yarnpkg.com) (any decently recent version should be fine)

## Development

To get your environment set up and install all dependencies, you can simply use
the `yarn` command in the same directory as this `README.md`.

Afterwards, make whatever changes you plan to make, then in a terminal you can
use `yarn start` to create a development server which will be accessible at
[`localhost:3000`](http://localhost:3000) in your web browser.

## Building

The `yarn build` command generates a static version of the documentation site
in the `build/` directory. As of now, this appears to be deployed using GitHub
Pages.