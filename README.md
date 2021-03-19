# Dashboards
This repository is an aggregation of community supported dashboards which work with ServerStatistics. These dashboards are here to not only show you what the plugin is capable of monitoring, but to also give you an example of how Grafana, Prometheus or InfluxDB work.

## Usage
In order to use these dashboards, simply look for a dashboard that suits your needs here in the repository. Once you found something to your liking, you should see a set of JSON files; one dashboard for each datasource. Simply choose the one that matches the datasource you're using.

Copy the JSON contents to your clipboard. In Grafana, hover over the plus icon on the left, then click import. Then, paste the JSON contents from your clipboard into the textbox under "Import via panel JSON", and hit import. During the import you may be prompted to select the correct datasource.

## Profiles
Some dashboards require specific profiles to be installed. When this requirement exists, it will be mentioned and referenced in the README file under the dashboard folder. Simply install the necessary profile in ServerStatistics.