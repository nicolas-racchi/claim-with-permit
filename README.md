# Claim with Permit • Digital signature scheme for allow-listed claims

Working proof of concept for a digital signature scheme that allows a user to sign a claim with a permit. The permit is a signed message that allows the claim to be signed by the user. The permit is signed by a trusted party, and the claim is executed by the user. The claim is only valid if the permit is valid.

## Contributing

You will need a copy of [Foundry](https://github.com/foundry-rs/foundry) installed before proceeding. See the [installation guide](https://github.com/foundry-rs/foundry#installation) for details.

### Setup

```sh
git clone https://github.com/transmissions11/foundry-template.git
cd foundry-template
forge install
```

### Run Tests

```sh
forge test
```

### Update Gas Snapshots

```sh
forge snapshot
```
