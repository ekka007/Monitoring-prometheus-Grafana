# Monitoring-prometheus-Grafana
demo setup project
Step 1 - Configure Prometheus
The Prometheus server requires a configuration file that defines the endpoints to scrape along with how frequently the metrics should be accessed.
![prometheus](https://user-images.githubusercontent.com/105065311/182145707-15d7abb0-27b4-4047-bbcf-a50dfc2abffe.PNG)
 Start Node Exporter
To collect metrics related to a node it's required to run a Prometheus Node Exporter. Prometheus has many exporters that are designed to output metrics for a particular system, such as Postgres or MySQL.
![prometheus-1](https://user-images.githubusercontent.com/105065311/182145722-880896b7-6c19-431c-9546-806e6fe8ac1c.PNG)
View Metrics
With the containers launched, Prometheus will scrape and store the data based on the internals in the configuration.
![promethues-monitoring](https://user-images.githubusercontent.com/105065311/182145731-88a96b1d-4947-4bba-bce6-464ecd8402fb.PNG)
