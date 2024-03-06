# Supply chain Contracts

### 🏗️ Building

```sh
cargo b -p "supply-chain*"
```

### ✅ Testing

Run all tests, except `gclient` ones:
```sh
cargo t -p "supply-chain*" -- --skip gclient
```

Run all tests:
```sh
# Download the node binary.
cargo xtask node
cargo t -p "supply-chain*"
```
