# wai-middleware-metrics

[![Build Status](https://travis-ci.org/Helkafen/wai-middleware-metrics.svg?branch=master)](https://travis-ci.org/Helkafen/wai-middleware-metrics)

A [WAI](https://hackage.haskell.org/package/wai) middleware to collect the following [EKG](https://ocharles.org.uk/blog/posts/2012-12-11-24-day-of-hackage-ekg.html) metrics from compatible web servers:
- number of requests (counter `wai.request_count`)
- number of responses by status code, broken down by class (counter `wai.response_status_xxx`, eg `wai.response_status_2xx`)
- latency distribution (distribution `wai.latency_distribution`)

Compatible web servers include the following: Yesod, Scotty, Spock, Servant, Warp.

Documentation and sample code [here](https://hackage.haskell.org/package/wai-middleware-metrics).
