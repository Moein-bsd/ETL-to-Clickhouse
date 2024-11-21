

Download clickhouse .deb files for Debian Linux:
mkdir clickhouse
cd clickhouse
wget https://github.com/ClickHouse/ClickHouse/releases/download/v24.8.7.41-lts/clickhouse-client_24.8.7.41_amd64.deb
wget https://github.com/ClickHouse/ClickHouse/releases/download/v24.8.7.41-lts/clickhouse-common-static-dbg_24.8.7.41_amd64.deb
wget https://github.com/ClickHouse/ClickHouse/releases/download/v24.8.7.41-lts/clickhouse-common-static_24.8.7.41_amd64.deb
wget https://github.com/ClickHouse/ClickHouse/releases/download/v24.8.7.41-lts/clickhouse-server_24.8.7.41_amd64.deb



install all clickhouse.deb in All 4  CH nodes :

sudo dpkg -i  clickhouse-client_24.8.7.41_amd64.deb clickhouse-common-static_24.8.7.41_amd64.deb clickhouse-common-static-dbg_24.8.7.41_amd64.deb


set password : default