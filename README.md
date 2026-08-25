# Awesome time series database with stars

[![Build Status](https://travis-ci.org/xephonhq/awesome-time-series-database.svg?branch=master)](https://travis-ci.org/xephonhq/awesome-time-series-database)
[![Netlify Status](https://api.netlify.com/api/v1/badges/2ea12ac4-c2b9-4767-87d6-8ac65ce5ee30/deploy-status)](https://app.netlify.com/sites/awesome-time-series-database/deploys)

A curated list of time series databases.
For filtering based on language, backend etc. Check out the [Website](https://awesome-time-series-database.netlify.com/).

<!--DBTABLE_START-->

|       name      |                                               github                                              |   status   |    lang    |              backend             |  protocol  |            query            |   license   |
| :-------------: | :-----------------------------------------------------------------------------------------------: | :--------: | :--------: | :------------------------------: | :--------: | :-------------------------: | :---------: |
|     Akumuli     |                          <https://github.com/akumuli/Akumuli> ⚠️ Archived                         | maintained |     c++    |              localfs             |     tcp    |             text            |  apache-2.0 |
|      Arctic     |        <https://github.com/man-group/arctic> ⭐ 3,085 \| 🐛 97 \| 🌐 Python \| 📅 2024-04-08       |   active   |   python   |              mongodb             |     tcp    |            python           |     lgpl    |
|      Argus      |                               <https://github.com/salesforce/Argus>                               |    dead    |    java    |               hbase              |    http    |             json            |     bsd     |
|      Atlas      |          <https://github.com/Netflix/atlas> ⭐ 3,562 \| 🐛 8 \| 🌐 Scala \| 📅 2026-08-23          | maintained |    scala   |              memory              |    http    |            stack            |  apache-2.0 |
|     Beringei    |                     <https://github.com/facebookarchive/beringei> ⚠️ Archived                     |    dead    |     c++    |              memory              |   thrift   |            thrift           |     bsd     |
|   BigGraphite   |                        <https://github.com/criteo/biggraphite> ⚠️ Archived                        | maintained |   python   |             cassandra            |    http    |           graphite          |  apache-2.0 |
|    Blueflood    |        <https://github.com/rackerlabs/blueflood> ⭐ 598 \| 🐛 54 \| 🌐 Java \| 📅 2024-08-19       |    dead    |    java    |      cassandra,elasticsearch     |    http    |             json            |  apache-2.0 |
|      BTrDB      |          <https://github.com/BTrDB/btrdb-server> ⭐ 910 \| 🐛 13 \| 🌐 Go \| 📅 2021-08-14         | maintained |     go     |               ceph               |    http    |             json            |     gpl     |
|      Catena     |            <https://github.com/Cistern/catena> ⭐ 390 \| 🐛 4 \| 🌐 Go \| 📅 2016-03-24            |    dead    |     go     |              localfs             |    http    |             json            |     bsd     |
|     Chronix     |                     <https://github.com/ChronixDB/chronix.server> ⚠️ Archived                     | maintained |    java    |               solr               |    http    |             json            |  apache-2.0 |
|      Citus      |         <https://github.com/citusdata/citus> ⭐ 12,723 \| 🐛 1,064 \| 🌐 C \| 📅 2026-08-24        |   active   |      c     |            postgresql            |     tcp    |             sql             |   agpl-3.0  |
|    ClickHouse   |     <https://github.com/ClickHouse/ClickHouse> ⭐ 49,434 \| 🐛 7,056 \| 🌐 C++ \| 📅 2026-08-25    |   active   |     c++    |              localfs             |     tcp    |             sql             |  apache-2.0 |
|      Cortex     |       <https://github.com/cortexproject/cortex> ⭐ 5,856 \| 🐛 355 \| 🌐 Go \| 📅 2026-08-25       |   active   |     go     |  s3,cassandra,bigtable,dynamodb  |    http    |            promql           |  apache-2.0 |
|     CrateDB     |           <https://github.com/crate/crate> ⭐ 4,426 \| 🐛 329 \| 🌐 Java \| 📅 2026-08-25          |   active   |    java    |         elasticsearch,s3         |     tcp    |             sql             |  apache-2.0 |
|   DalmatinerDB  |    <https://github.com/dalmatinerdb/dalmatinerdb> ⭐ 691 \| 🐛 28 \| 🌐 Erlang \| 📅 2019-02-11    | maintained |   erlang   |              localfs             |    http    |             text            |     mit     |
|      FiloDB     |          <https://github.com/filodb/FiloDB> ⭐ 1,467 \| 🐛 67 \| 🌐 Scala \| 📅 2026-08-25         |   active   |    scala   |             cassandra            |    http    |       promql,metricsql      |  apache-2.0 |
|      Flint      |         <https://github.com/twosigma/flint> ⭐ 1,177 \| 🐛 44 \| 🌐 Scala \| 📅 2020-07-03         | maintained |    scala   |               spark              |    http    |             json            |  apache-2.0 |
|     Gnocchi     |        <https://github.com/gnocchixyz/gnocchi> ⭐ 323 \| 🐛 46 \| 🌐 Python \| 📅 2026-05-08       |    dead    |   python   |              localfs             |    http    |             json            |  apache-2.0 |
|      GridDB     |           <https://github.com/griddb/griddb> ⭐ 2,475 \| 🐛 51 \| 🌐 C++ \| 📅 2026-03-19          |   active   |     c++    |              localfs             |    jdbc    |           sql,tql           |  apache-2.0 |
| HawkularMertics |                     <https://github.com/hawkular/hawkular-metrics> ⚠️ Archived                    | maintained |    java    |             cassandra            |    http    |             json            |  apache-2.0 |
|      Heroic     |                          <https://github.com/spotify/heroic> ⚠️ Archived                          | maintained |    java    | bigtable,cassandra,elasticsearch |    http    |             json            |  apache-2.0 |
|     InfluxDB    |     <https://github.com/influxdata/influxdb> ⭐ 31,714 \| 🐛 2,149 \| 🌐 Rust \| 📅 2026-08-20     |   active   |     go     |              localfs             |    http    |        influxql,flux        |     mit     |
|      IoTDB      |     <https://github.com/apache/incubator-iotdb> ⭐ 6,382 \| 🐛 733 \| 🌐 Java \| 📅 2026-08-25     |   active   |    java    |           hdfs,localfs           |     tcp    |             sql             |  apache-2.0 |
|      IRONdb     |                     <https://www.circonus.com/solutions/time-series-database/>                    |   active   |      c     |              localfs             |    http    |             json            | proprietary |
|     KairosDB    |        <https://github.com/kairosdb/kairosdb> ⭐ 1,762 \| 🐛 141 \| 🌐 Java \| 📅 2026-03-05       | maintained |    java    |             cassandra            |    http    |             json            |  apache-2.0 |
|     Khronus     |          <https://github.com/khronus/khronus> ⭐ 234 \| 🐛 16 \| 🌐 Scala \| 📅 2018-06-05         |    dead    |    scala   |             cassandra            |    http    |        json,influxql        |  apache-2.0 |
|      LinDB      |            <https://github.com/lindb/lindb> ⭐ 3,066 \| 🐛 11 \| 🌐 Go \| 📅 2026-07-27            |   active   |     go     |              localfs             |    http    |             sql             |  apache-2.0 |
|        M3       |              <https://github.com/m3db/m3> ⭐ 4,894 \| 🐛 220 \| 🌐 Go \| 📅 2026-08-17             |   active   |     go     |              localfs             |    http    | promql,graphite,m3query,sql |  apache-2.0 |
|    Metrictank   |                        <https://github.com/grafana/metrictank> ⚠️ Archived                        |   active   |     go     |      cassandra,elasticsearch     |    http    |           graphite          |   agpl-3.0  |
|      Newts      |           <https://github.com/OpenNMS/newts/> ⭐ 194 \| 🐛 33 \| 🌐 Java \| 📅 2026-07-22          | maintained |    java    |             cassandra            |    http    |             json            |  apache-2.0 |
|     OpenTSDB    |        <https://github.com/OpenTSDB/opentsdb> ⭐ 5,065 \| 🐛 538 \| 🌐 Java \| 📅 2024-12-12       | maintained |    java    |               hbase              |  http,tcp  |             json            |     lgpl    |
|   Apache Pinot  |    <https://github.com/apache/incubator-pinot> ⭐ 6,127 \| 🐛 1,399 \| 🌐 Java \| 📅 2026-08-25    |   active   |    java    |           s3,hdfs,azdls          |    http    |             pql             |  apache-2.0 |
|     PinusDB     |           <https://github.com/pinusdb/pinusdb> ⭐ 120 \| 🐛 0 \| 🌐 C++ \| 📅 2024-03-19           | maintained |     c++    |              localfs             |     tcp    |             sql             |   gpl-3.0   |
|    PipelineDB   |       <https://github.com/pipelinedb/pipelinedb> ⭐ 2,662 \| 🐛 133 \| 🌐 C \| 📅 2022-02-20       |    dead    |      c     |            postgresql            |     tcp    |             sql             |  apache-2.0 |
|    Prometheus   |      <https://github.com/prometheus/prometheus> ⭐ 65,804 \| 🐛 918 \| 🌐 Go \| 📅 2026-08-24      |   active   |     go     |              localfs             | prometheus |            promql           |  apache-2.0 |
|     QuestDB     |        <https://github.com/questdb/questdb> ⭐ 17,277 \| 🐛 935 \| 🌐 Java \| 📅 2026-08-25        |   active   |    java    |              localfs             |  postgres  |             sql             |  apache-2.0 |
|    Seriously    |                          <https://github.com/dustin/seriesly> ⚠️ Archived                         |    dead    |     go     |              localfs             |    http    |             json            |     mit     |
|    Sidewinder   |          <https://github.com/srotya/sidewinder> ⭐ 26 \| 🐛 15 \| 🌐 Java \| 📅 2020-06-19         |    dead    |    java    |              localfs             |     tcp    |             sql             |  apache-2.0 |
|      SiriDB     |          <https://github.com/SiriDB/siridb-server> ⭐ 514 \| 🐛 4 \| 🌐 C \| 📅 2026-07-27         |   active   |      c     |              localfs             |    http    |             text            |     mit     |
|     TDengine    |         <https://github.com/taosdata/TDengine> ⭐ 25,083 \| 🐛 449 \| 🌐 C \| 📅 2026-08-24        |   active   |      c     |              localfs             |     tcp    |             sql             |   agpl-3.0  |
|      Tgres      |              <https://github.com/tgres/tgres> ⭐ 513 \| 🐛 5 \| 🌐 Go \| 📅 2021-12-22             |    dead    |     go     |            postgresql            |     tcp    |             sql             |  apache-2.0 |
|      Thanos     |         <https://github.com/thanos-io/thanos> ⭐ 14,184 \| 🐛 879 \| 🌐 Go \| 📅 2026-08-24        |   active   |     go     |            localfs,s3            |  http,grpc |            promql           |  apache-2.0 |
|     Timebala    |          <https://github.com/mattbostock/timbala> ⭐ 91 \| 🐛 48 \| 🌐 Go \| 📅 2018-02-11         |    dead    |     go     |              localfs             |    http    |            promql           |  apache-2.0 |
|      Timely     |   <https://github.com/NationalSecurityAgency/timely> ⭐ 396 \| 🐛 20 \| 🌐 Java \| 📅 2026-05-13   | maintained |    java    |           hdfs,accumulo          |    http    |             json            |  apache-2.0 |
|   TimescaleDB   |       <https://github.com/timescale/timescaledb> ⭐ 23,406 \| 🐛 393 \| 🌐 C \| 📅 2026-08-24      |   active   |      c     |            postgresql            |  postgres  |             sql             |  apache-2.0 |
|     TrailDB     |           <https://github.com/traildb/traildb> ⭐ 1,090 \| 🐛 38 \| 🌐 C \| 📅 2021-01-24          |    dead    |      c     |              localfs             |    embed   |            python           |     mit     |
|    tsdb-layer   |       <https://github.com/richardartoul/tsdb-layer> ⭐ 523 \| 🐛 2 \| 🌐 Go \| 📅 2019-08-27       |    dead    |     go     |           foundationdb           |    grpc    |             text            |   unknown   |
|       μts       |                             <https://github.com/mixer/uts> ⚠️ Archived                            |    dead    | javascript |              memory              |    embed   |             json            |     mit     |
|    Vaultaire    |        <https://github.com/afcowie/vaultaire> ⭐ 58 \| 🐛 14 \| 🌐 Haskell \| 📅 2015-03-25        |    dead    |   haskell  |               ceph               |    http    |             json            |   unknown   |
| VictoriaMetrics | <https://github.com/VictoriaMetrics/VictoriaMetrics> ⭐ 17,591 \| 🐛 779 \| 🌐 Go \| 📅 2026-08-25 |   active   |     go     |              localfs             |    http    |       promql,metricsql      |  apache-2.0 |
|      Vulcan     |                        <https://github.com/digitalocean/vulcan> ⚠️ Archived                       |    dead    |     go     |             cassandra            |    http    |            promql           |  apache-2.0 |
|      Warp10     |        <https://github.com/senx/warp10-platform> ⭐ 414 \| 🐛 10 \| 🌐 Java \| 📅 2026-02-20       |   active   |    java    |           leveldb,hbase          |    http    |          warpscript         |  apache-2.0 |
|     Xephon-K    |           <https://github.com/xephonhq/xephon-k> ⭐ 23 \| 🐛 4 \| 🌐 Go \| 📅 2020-02-13           |    dead    |     go     |         cassandra,localfs        |  http,grpc |             json            |     mit     |

<!--DBTABLE_END-->

## Acknowledgement and Alternatives

* [awesome big data](https://github.com/onurakpolat/awesome-bigdata#time-series-databases) ⭐ 14,542 | 🐛 3 | 📅 2026-07-31
* [awesome db](https://github.com/numetriclabz/awesome-db) ⭐ 1,378 | 🐛 38 | 📅 2024-03-04
* [dbdb.io](https://github.com/cmu-db/dbdb.io) ⭐ 577 | 🐛 36 | 🌐 Python | 📅 2026-08-24 A database for all the databases by [@apavlo](https://github.com/apavlo) from [CMU DB](https://db.cs.cmu.edu/)
* [List of Time Series Databases](https://misfra.me/2016/04/09/tsdb-list/) by [Preetam Jinka](https://twitter.com/PreetamJinka)
* [Ultimate-TSDB-Comparison](https://tsdbbench.github.io/Ultimate-TSDB-Comparison/)
* [Github topic: timeseries-database](https://github.com/topics/timeseries-database)
* [Open Source Time Series DB Comparison](https://docs.google.com/spreadsheets/d/1sMQe9oOKhMhIVw9WmuCEWdPtAoccJ4a-IuZv4fXDHxM/edit#gid=0)

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Pinglei Guo](https://github.com/at15) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
