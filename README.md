# Moralis Token Gating Server

This server project is built using Express to demo Token Gating capabilities using Moralis SDK.

## Getting Started

### 1. Install Dependencies

```sh
# Using NPM
npm i

# Using Yarn
yarn
```

### 2. Run Server

```sh
# Using NPM
npm run start

# Using Yarn
yarn start
```

### 3. Call Secret API

You can use any method to call the `/secret` REST API. Here is an example using CURL.

```sh
curl http://localhost:3000/secret \
    -H 'Content-Type: application/json' \
    -d '{"sessionToken":"<session-token-input>"}'
```

## License

MIT License
