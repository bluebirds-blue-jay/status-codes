# StatusCode

Enums and utilities around status codes.

## Requirements

- `node >= 7.10`
- `typescript >= 2.4`

## Installation

`npm i @bluejay/status-code`

## Usage

```typescript
import { StatusCode, isStatusCode, is5xx } from '@bluejay/status-code';

StatusCode.OK; // 200
isStatusCode(200); // true
is5xx(StatusCode.INTERNAL_SERVER_ERROR); // true
```


## Documentation

See [Github Pages](https://bluebirds-blue-jay.github.io/status-code/).