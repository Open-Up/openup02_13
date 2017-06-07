# OpenUp lesson 13

## Load-balancing, failover, and replication

Retrieve this presentation [online](https://rawgit.com/Open-Up/openup02_13/master/presentation/index.html)

## Interesting readings

### About load balancing

Load balancer at **Spotify** : [Part 1](https://labs.spotify.com/2015/12/08/els-part-1/) and [Part 2](https://labs.spotify.com/2015/12/09/els-part-2/)

Evaluation of [different load balancing strategies](https://blog.buoyant.io/2016/03/16/beyond-round-robin-load-balancing-for-latency/)

### About replication

I want to provide an example of [why consensus is needed](https://aphyr.com/posts/317-jepsen-elasticsearch).

> Some of these problems can be ameliorated by improving Elasticsearch’s GC performance and overall responsiveness–but this will only reduce the frequency of split-brain events, not fix the underlying problem. Elasticsearch needs a real consensus algorithm to linearize updates to documents.

By the way, the entire [Jepsen](https://aphyr.com/tags/jepsen) blog post list is a *must read* if you consider being a backend developer, and might still be interresting for full stack developers. Start from the begining.
