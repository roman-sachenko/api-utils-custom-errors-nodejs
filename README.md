# Custom API Errors (NodeJS)

Usage

```
const { BadRequest, Forbidden } = require('./apiErrors')

throw new BadRequest();

throw new Forbidden('not allowed');

```