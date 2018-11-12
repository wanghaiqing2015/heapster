docker pull krman/heapster-influxdb-amd64:v1.3.3
docker pull krman/heapster-grafana-amd64:v4.4.3
docker pull krman/heapster-amd64:v1.4.2
 
docker tag krman/heapster-influxdb-amd64:v1.3.3 k8s.gcr.io/heapster-influxdb-amd64:v1.3.3
docker tag krman/heapster-grafana-amd64:v4.4.3  k8s.gcr.io/heapster-grafana-amd64:v4.4.3
docker tag krman/heapster-amd64:v1.4.2          k8s.gcr.io/heapster-amd64:v1.4.2

docker tag krman/heapster-influxdb-amd64:v1.3.3 gcr.io/google_containers/heapster-influxdb-amd64:v1.3.3
docker tag krman/heapster-grafana-amd64:v4.4.3  gcr.io/google_containers/heapster-grafana-amd64:v4.4.3
docker tag krman/heapster-amd64:v1.4.2          gcr.io/google_containers/heapster-amd64:v1.4.2