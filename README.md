
Docker image for hbase standalone 1.2.0 for testing/developing


Build image

    docker build -t hbase1-2-0 .

Run image

    docker run --name my_hbase -d -p 2181:2181 -p 60010:60010 -p 60000:60000 -p 60020:60020 -p 60030:60030 -h my_hbase hbase1-2-0

NOTE: To connect from outside you need to resolve host `my_hbase` (for testing you can add use your local host name...)