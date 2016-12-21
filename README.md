# cors-prefetch-middleware

[![NPM](https://nodei.co/npm/cors-prefetch-middleware.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/cors-prefetch-middleware/)

Express middleware for cors prefetch

## Usage

```javascript
import express from 'express';
import corsPrefetch from 'cors-prefetch-middleware';

const app = express();

app.use(corsPrefetch);

app.listen(8080);
```
