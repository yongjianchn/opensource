# SinaEdge contributions

## ATS

* Fix HTTPInfo::unmarshal function memory leak by call ats_malloc
    * https://github.com/apache/trafficserver/pull/4872 by @wolfgangbai, closed
    * https://github.com/apache/trafficserver/pull/4874 by @scw00, merged

* fix crash in CacheVC::openReadFromWriter
    * https://github.com/apache/trafficserver/pull/5122 by @rienzi2012

* fix If-None-Match and If-Modified-Since priority problem
    * https://github.com/apache/trafficserver/pull/5268 by @wolfgangbai

* Segmentation fault in HttpTunnel::chain_abort_all about gzip,HttpTunnel
    * https://github.com/apache/trafficserver/issues/5294 by @wolfgangbai

* fix 3939 collision
    * https://github.com/apache/trafficserver/issues/5175 by @rienzi2012
    * https://github.com/apache/trafficserver/pull/5362 by @wolfgangbai

## DPVS
https://github.com/iqiyi/dpvs/pull/662  
https://github.com/iqiyi/dpvs/pull/670  
https://github.com/iqiyi/dpvs/pull/774  
