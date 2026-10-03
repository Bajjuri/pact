# pact

My sandbox for learning and experimenting with [Pact](https://docs.pact.io) consumer-driven contract testing in Node.js.

It contains a small Order Web (consumer) and Order API (provider) example with Mocha tests.

## Run

```bash
npm install
npm run test:consumer   # generates the pact in ./pacts
npm run test:provider   # verifies the provider against the pact
```

Run a single spec: `npx mocha consumer/consumer.spec.js`

## Credits

Started from [pact-foundation/pact-5-minute-getting-started-guide](https://github.com/pact-foundation/pact-5-minute-getting-started-guide) (MIT). See the [Pact docs](https://docs.pact.io/5-minute-getting-started-guide) for the original walkthrough.
