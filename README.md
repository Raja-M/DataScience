#DataScience

docker run  -i -d -p 24022:22 -p 8000:9000 -p 24240:14240 --name tigergraph_dev --ulimit nofile=1000000:1000000 -v /Users/rmudiga/work/tigergraph/share4_data:/home/tigergraph/mydata -t tigergraph:3.2.1

