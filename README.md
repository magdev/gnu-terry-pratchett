# gnu-terry-pratchett

Add a X-Clacks-Overhead HTTP-Header to your Express application. Inspired by (Redditor pocketknifeMT)[http://www.reddit.com/r/bestof/comments/2yyop7/rdiscworld_redditors_with_web_servers_start/cpe89jk].

## Usage

```javascript
var express = require('express'),
    gnutp = require('gnu-terry-pratchett'),
    app = express();
    
app.use(gnutp());
```


## License

Copyright (c) 2015 Marco Grätsch  
Licensed under the [MIT license](LICENSE.md).
