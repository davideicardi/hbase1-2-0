
Docker image for hbase standalone 1.2.0


Build image

    docker build -t hbase1-2-0 .

Run image

    docker run --name my_hbase -d -p 2181:2181 -p 60010:60010 -p 60000:60000 -p 60020:60020 -p 60030:60030 -h hbase hbase1-2-0
