# AWS-CF-RedisDB
# RedisJSON
RedisJSON is a [Redis](https://redis.io/) module that implements [ECMA-404 The JSON Data Interchange Standard](https://json.org/) as a native data type. It allows storing, updating and fetching JSON values from Redis keys (documents).

## Primary features:

* Full support of the JSON standard
* [JSONPath](https://goessner.net/articles/JsonPath/) syntax for selecting elements inside documents
* Documents are stored as binary data in a tree structure, allowing fast access to sub-elements
* Typed atomic operations for all JSON values types
* Secondary index support when combined with [RediSearch](https://redisearch.io)
