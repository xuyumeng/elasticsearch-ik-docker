# elasticsearch-ik-docker

elasticsearch(2.1) + ik(1.6.2) plugin docker, add chinese stopword dictionary based on grantchen/elasticsearch-ik

# How to use

```bash
git clone git@github.com:xuyumeng/elasticsearch-ik-docker.git
cd elasticsearch-ik-docker
docker build -t yourname/elasticsearch-ik .
```
# How to start

```bash
docker run -d -p 9200:9200 -v "/home/grantchen/esdata":/usr/share/elasticsearch/data yourname/elasticsearch-ik
```
