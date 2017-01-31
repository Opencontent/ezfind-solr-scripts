# ezfind-solr-scripts
eZ Find init scripts for various linux distribution

Once installed, better schedule a night restart to free java ram

```
# restart solr
20  1 * * * /etc/init.d/solr-xxx  restart > /dev/null
```
