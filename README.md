# ONOS-SDMN
Include: solutions for Radio Access Network (RAN), Core Mobile Network, Carrier Network, Cloud, Datacenter, etc.,implimented in ONOS controller environment.
# SDMN
SDMN- Software Defined Mobile Network.
# RUN ONOS & BUIL APPLICATION (on MAC OS)
1. docker pull dosinhuda/onos
2. sudo docker run -t -d --name onos1 dosinhuda/onos
3. docker inspect --format='{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' "onos1"
4. ssh -p 8101 karaf@172.17.0.2
