## How to use Yarn

### corepack comes installed with node

```sh
corepack enable
```

### check yarn

```sh
yearn --version
```

## Common commands

### compile sol file

```sh
yarn solcjs --bin --abi --include-path node_modules/ --base-path . -o . SimpleStorage.sol
```

or

```sh
yarn compile
```

### run deploy.ts script (example)

```sh
PRIVATE_KEY_PASSWORD=password  yarn ts-node deploy.ts
```
