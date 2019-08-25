# Manual de Usuario ExpressionEngine®

The public user guide repository for the [ExpressionEngine](https://expressionengine.com) project. The online version of the user guide is hosted at [docs.expressionengine.com](https://docs.expressionengine.com).

## Setup

The ExpressionEngine user guide is written in human-readable Markdown and uses a simple script to generate beautiful HTML docs.

### Prerequisites

Building the docs requires Node and npm.

In the root of the repository, install all the dependencies:

    npm install

### Building the Docs

To build the docs:

    npm run build

To dynamically rebuild on any file changes:

    npm run watch

### Building theme assets

The documentation css and js files are located under `theme/assets-src`.

To build the theme assets, run `npm run buildAssets`. You can also dynamically rebuild the assets when a file changes: `npm run watchAssets`.

## Contributing

See something that needs fixing? Want to improve the user guide or make it more helpful? Great! Check out [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Copyright / License Notice

The ExpressionEngine project is copyright (c) 2003-2019 EllisLab Corp. ([https://ellislab.com](https://ellislab.com)) and is licensed under Apache License, Version 2.0. This project contains subcomponents with separate copyright and license terms, all of which are fully FOSS and compatible with Apache-2.0.

Complete license terms and copyright information can be found in [LICENSE.txt](LICENSE.txt) in the root of this repository.

"ExpressionEngine" is a registered trademark of EllisLab, Inc. in the United States and around the world. Refer to EllisLab's [Trademark Use Policy](https://ellislab.com/trademark-use-policy) for access to logos and acceptable use.
