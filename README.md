# Virtual_ads
This app was initialized with create-near-app
# Quick start
To run this project locally:

Prerequisites: Make sure you've installed Node.js ≥ 12
Install dependencies: yarn install
Run the local development server: yarn dev (see package.json for a full list of scripts you can run with yarn)
Now you'll have a local development environment backed by the NEAR TestNet!

Go ahead and play with the app and the code. As you make code changes, the app will automatically reload.
# Exploring the code
The "backend" code lives in the /contract and nft-contract folders. See the README there for more info.

# Install Near Cli
near-cli is a command line interface (CLI) for interacting with the NEAR blockchain. It was installed to the local node_modules folder when you ran yarn install, but for best ergonomics you may want to install it globally:

yarn install --global near-cli
Or, if you'd rather use the locally-installed version, you can prefix all near commands with npx

Ensure that it's installed with near --version (or npx near --version)

# Troubleshooting
On Windows, if you're seeing an error containing EPERM it may be related to spaces in your path. Please see this issue for more details.
