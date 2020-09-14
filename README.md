# A Curated List of Sample Redis Datasets

This page shows the sample datasets available for Redis Modules. Click the below sample dataset to lean more about it.



## [RediSearch](https://github.com/redis-developer/redis-datasets/blob/master/redisearch/README.md)


| List of Dataset | Description |
| --- | --- |
| [Movie Dataset](https://github.com/Redis-Developer/redis-datasets/tree/movie-dataset/movie-database) | Contains details on Movie Database listings |
| [OpenBeerDB](https://github.com/Redis-Developer/redis-datasets/tree/master/redisearch/openbeerdb) | Contains details on Openbeer listings |


## [RedisGraph](https://github.com/redis-developer/redis-datasets/blob/master/redisgraph/README.md)

| List of Dataset | Description |
| --- | --- |
| [An API of Ice and Fire](https://github.com/Redis-Developer/redis-datasets/blob/master/redisgraph/datasets/iceandfire/README.md) | Contains details on Ice & Fire API Database listings |
| [Redis Graph Bulk Loader](https://github.com/Redis-Developer/redis-datasets/tree/master/redisgraph/redisgraph-bulk-loader) | Loading bulk data into Redisgraph |

## RedisGears

| List of Dataset | Description |
| --- | --- |
| [Sample IMDB Dataset](https://github.com/Redis-Developer/redis-datasets/blob/master/redisgears/README.md) | Contains details on IMDB Movie Database listings |



## [RedisJSON](https://github.com/redis-developer/redis-datasets/blob/master/redisjson/README.md)

| List of Dataset | Description |
| --- | --- |
| Sample  Dataset | Contains details on Sample Database listings |
| Sample Dataset | Contains details on Sample listings |



## [RedisTimeseries](https://github.com/redis-developer/redis-datasets/blob/master/redistimeseries/README.md)

| List of Dataset | Description |
| --- | --- |
| [Sample AirQuality Dataset](https://github.com/Redis-Developer/redis-datasets/tree/master/redistimeseries/AirQualityUCI) | Contains details on Air Quality listings |
| Sample Geospatial  Dataset | Contains details on Sample Database listings |

## RedisAI


| List of Dataset | Description |
| --- | --- |
| [Animal Recognition Demo](https://github.com/Redis-Developer/redis-datasets/tree/master/redisai) | Contains details on Animal Recognition listings |
| [Edge Real time Video Analytics](https://github.com/Redis-Developer/redis-datasets/tree/master/redisai)| Contains details on Edge Real time Video Analytics listings |
| [Chat Bot Demo](https://github.com/Redis-Developer/redis-datasets/tree/master/redisai) | Contains details on Chat Bot Demo listing |
[ Redis AI Showcase](https://github.com/Redis-Developer/redis-datasets/tree/master/redisai) | Contains details on Chat Bot Demo listing |

## [RedisBloom](https://github.com/redis-developer/redis-datasets/blob/master/redisbloom/README.md)

| List of Dataset | Description |
| --- | --- |
| [Unique Website Visitor](https://github.com/redis-developer/redis-datasets/blob/master/redisbloom/README.md) | Contains details on Unique IP address visitors listings |



## How to test drive these Modules

<details><summary>
### Using Redis Cloud
  </summary>
Sign up for a free account [here](https://redislabs.com/redis-enterprise-cloud/) and get 30MB free tier at $0. Use the button below to register yourself and get started in no seconds. 

[![](https://github.com/Redis-Developer/redis-datasets/blob/master/images/recloud.png)](https://app.redislabs.com/#/add-subscription)

</details>

<details><summary>
### Using Linux
</summary>

Following are the pre-requisites for using Redis Modules



#### Installing Redis
Reference and more detailed steps: [here](https://redis.io/download#installation)

```bash
$ wget http://download.redis.io/redis-stable.tar.gz

$ tar xvzf redis-stable.tar.gz

$ cd redis-stable

$ make

$ make test

$ sudo make install
```
</details>
<details><summary>
#### Build RedisGraph Module(Example)
  </summary>
Reference and more detailed steps: [here](https://oss.redislabs.com/redisgraph/)

```bash
# Ubuntu/Linux

$ sudo apt-get install build-essential cmake m4 automake peg libtool autoconf

# Mac

$ brew install cmake m4 automake peg libtool autoconf

$ git clone --recurse-submodules -j8 [https://github.com/RedisGraph/RedisGraph.git](https://github.com/RedisGraph/RedisGraph.git)

$ cd RedisGraph

$ make
```
</details>



