# graphql base-goerli

You can install Graph CLI with either npm or yarn.

Note: You need version 0.21.0 or above

1. INSTALL GRAPH CLI USING NPM

   ```sh
   npm install -g @graphprotocol/graph-cli
   ```

## INIT

Initialize your subgraph.

1. INITIALIZE SUBGRAPH

   ```sh
   graph init --studio safes
   ```

1. AUTH & DEPLOY

   > Authenticate within the CLI, build and deploy your subgraph to the Studio.

1. AUTHENTICATE IN CLI

   ```sh
   graph auth --studio eb3738—7f5a7e

   ```

1. ENTER SUBGRAPH

   ```sh
   cd safes
   ```

1. BUILD SUBGRAPH

   ```sh
   graph codegen && graph build
   ```

1. DEPLOY SUBGRAPH

   ```sh
   graph deploy --studio safes
   ```
