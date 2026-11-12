# WebWiki
My WebWiki.js and Monitoring Stack using Docker Compose
PostgreSQL stores Wiki.js data.
Wiki.js connects to PostgreSQL through Docker's internal network.
Prometheus collects monitoring metrics.
Grafana will display those metrics.
cAdvisor monitors Docker containers.
Node Exporter monitors your Ubuntu machine.
