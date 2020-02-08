# percona_setup
setting up pmm to any msql db server
- First Setup a Percona Server 
Then
- add clients to pmm-server
####
By default, retention is set to 30 days for Metrics Monitor and to 8 days for Query Analytics. Also consider disabling table statistics, which can greatly decrease Prometheus database size.

-e METRICS_RETENTION=192h use this in docker command to set metrices retention 
