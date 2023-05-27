# zkSync Hardhat Template

zkSync Hardhat Template contract.

## Commands

- `yarn hardhat compile` will compile the contracts.
- `yarn run deploy` will execute the deployment script `/deploy/deploy-greeter.ts`. Requires [environment variable setup](#environment-variables).
- `yarn run greet` will execute the script `/deploy/use-greeter.ts` which interacts with the Greeter contract deployed.
- `yarn test`: run tests. **Check test requirements below.**

Both `yarn run deploy` and `yarn run greet` are configured in the `package.json` file and run `yarn hardhat deploy-zksync`.

### Local testing

In order to run test, you need to start the zkSync local environment. Please check [this section of the docs](https://v2-docs.zksync.io/api/hardhat/testing.html#prerequisites) which contains all the details.

If you do not start the zkSync local environment, the tests will fail with error `Error: could not detect network (event="noNetwork", code=NETWORK_ERROR, version=providers/5.7.2)`

## Docs

- <https://era.zksync.io/docs/api/hardhat/getting-started.html>

## Refs

- <https://github.com/matter-labs/zksync-hardhat-template>
