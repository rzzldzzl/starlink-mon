# starlink-mon
Docker Compose and Grafana configs to stand up:
* [starlink-grpc-tools](https://github.com/sparky8512/starlink-grpc-tools)
* InfluxDB
* Grafana
  * [Starlink Dashboard](#grafana-starlink-dashboard-screenshot)

## Running Containers
* [Install Docker Desktop on Mac](https://docs.docker.com/desktop/mac/install/)  
* Install **docker-compose**  
  * ```sudo curl -L "https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose```
  * ```sudo chmod +x /usr/local/bin/docker-compose```
* Clone Repo  
  * ```git clone https://github.com/rzzldzzl/starlink-mon.git```  
* Execute **docker-compose**  
  * ```docker-compose -f starlink-mon/docker-compose.yaml up -d```

## Grafana Url
http://localhost:3000

## Grafana Starlink Dashboard Screenshot
![](images/ScreenShot_1.png)
