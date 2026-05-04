# @dipcoinlab/perp-ts-library

Perpetual exchange library housing helper methods and classes to interact with the DipCoin protocol deployed on Sui blockchain.

## Installation

```bash
npm install @dipcoinlab/perp-ts-library
```

## Quick Start

```typescript
import { DipCoinPerp } from '@dipcoinlab/perp-ts-library';

const perp = new DipCoinPerp({
  network: 'mainnet',
  privateKey: process.env.SUI_PRIVATE_KEY
});

// Get market info
const markets = await perp.getMarkets();
console.log(markets);
```

## Documentation

See [docs/](./docs/) for full API documentation.

## License

Apache-2.0
