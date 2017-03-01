# elasticsearch-2.x-vagrant

## Usage:

Install Vagrant first

```bash
> git clone https://github.com/arusland/elasticsearch-2.x-vagrant.git
> cd elasticsearch-2.x-vagrant
> vagrant up
```

To check installed elasticsearch

```bash
> curl http://localhost:9200
```

You will get something like
``` json
{
  "name" : "Professor Power",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "_xkKjMYXSgeWxFXmoqUR1g",
  "version" : {
    "number" : "2.4.4",
    "build_hash" : "fcbb46dfd45562a9cf00c604b30849a6dec6b017",
    "build_timestamp" : "2017-01-03T11:33:16Z",
    "build_snapshot" : false,
    "lucene_version" : "5.5.2"
  },
  "tagline" : "You Know, for Search"
}
```


Source https://qbox.io/blog/qbox-a-vagrant-virtual-machine-for-elasticsearch-2-x
