# unly-utils-googletag

This project is a transversal project, helpers for google tag manager

Install:

npm or yarn

```
npm install https://github.com/UnlyEd/unly-utils-googletag.git
```

Use:

```
const { gaPageview } = require('unly-utils-googletag');
```

Library:

|   | param(s)         |  |
| :--------------- |:---------------:| :-----:|
| convertTrackingIDToGTag |  trackingId  | generate a tracker based on trackingId |
| gaPageview  | tracker |  |
| initializeAsHTML | trackingId | |

## Development

### Test

Run once:
```
yarn run test:once
```

Watch:
```
yarn test
```

Coverage:
```
yarn run test:coverage
```

### Lint

```
yarn run lint
```
