Fork of `ws` for better streaming

Added SSL support (wss://). To create a server in SSL mode simply pass `key` and `cert` to the WebSocketServer `options` parameter:

```
WebSocketServer({
  key:    fs.readFileSync('www.sample.com.key'),
  cert:   fs.readFileSync('www.sample.com.crt')
}, ...);
```
