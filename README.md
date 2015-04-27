# public-api

npm's public APIs are haphazard, old-fashioned, and scattered. We can and will do better. An internal API was created to handle the needs of [www](https://github.com/npm/newww), but needs some work before it can be publicly released. In particular, the existence of private packages means that

* we can't just expose all the data
* we have to provide an authentication mechanism, so you can see *your* data

This is very doable, and we intend to do it, but we don't have a timeline yet. In the meantime, this repo is for collecting feature requests and tracking work on this in future. Check out the [issues](https://github.com/npm/public-api/issues).
