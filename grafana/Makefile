create-network:
	docker network create monitor-net

create-volume:
	docker volume create --driver local --opt type=none --opt device=/volumes/grafana/grafana_data --opt o=bind grafana_data


copy-provisioning:
	cp -R grafana/provisioning  /volumes/grafana/grafana_data/