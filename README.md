# fastify-stream-sample

Install [fyn].

```bash
$ fyn
$ fun start
```

## routes

- `http://localhost:3000` - return streaming response
- `http://localhost:3000?fail=2` - cause a failure on 2nd streaming chunk
- `http://localhost:3000/multi` - send back multiple streams in response

> Note in `multi`, both streams were produced concurrently, so the second one show up in one go after the first one's streamed.

## Others

- [Hapi] - <https://github.com/jchip/hapi-stream-sample>
- [koa] - <https://github.com/jchip/koa-stream-sample>
- [express] - <https://github.com/jchip/express-stream-sample>

# License

Licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

---

[fyn]: https://www.npmjs.com/package/fyn
[hapi]: https://hapijs.com/
[koa]: https://koajs.com/
[express]: https://expressjs.com/
