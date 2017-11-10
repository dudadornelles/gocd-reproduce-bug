 docker run -d -v $(pwd)/home:/home/go -v $(pwd)/godata:/godata -p8153:8153 -p8154:8154 gocd/gocd-server:v17.7.0
