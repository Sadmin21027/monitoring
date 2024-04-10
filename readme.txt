Monitoring Grafana+Prometheus+Blackbox
git clone https://github.com/Sadmin21027/Monitoring.git
cd monitoring
nano config/prometheus/prometheus.yml
№ change ip addres
docker compose up -d
# Permission Denied
chmod 775 volumes/prometheus/
chmod 775 volumes/grafana/
