# README #

# Create Networks
cd dockprom; make create-network; cd ..;

cd efk; make create-network; make create-volume; cd ..;

cd grafana; make create-network; make create-volume; cd ..;

cd mssql; make create-network; make create-volume; cd ..;

cd redis; make create-network; make create-volume; cd ..;

cd superset; make create-network; make create-volume; cd ..;
