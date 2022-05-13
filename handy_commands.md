# Python related
```shell
# find Django path in env
python -c "import django; print(django.__path__)"


```

# PostgreSQL related
```shell
# Use systemctl/service/other commands to manage postgresql service:
# Initialize the server by running the command:
sudo service postgresql-13.6 initdb #

# 1. START
# all
systemctl start postgresql
sudo service postgresql start

# start specific server
systemctl start postgresql@14-main
sudo service postgresql-13.6 start #
sudo service postgresql-14.2 start

## 2. STOP
systemctl stop postgresql
service postgresql stop

# 3. STATUS
systemctl status postgresql
service postgresql status
pgrep -u postgres -fa -- -D

# show information about all PostgreSQL clusters
pg_lsclusters

# 4. DISABLE (not auto-start any more)
systemctl disable postgresql

# 5. ENABLE (auto-start)
systemctl enable postgresql
systemctl enable postgresql@14-main

# Find PostgreSQL location
sudo find /usr -wholename '*/bin/postgres'

# Find your port
# example: sudo sed -n 4p <$PGDATA>/postmaster.pid
sudo sed -n 4p /var/lib/postgresql/13/main/postmaster.pid

# Log on to the psql command-line tool by running the command:
sudo -u postgres psql

# Login as `postgres` user
sudo su - postgres

# Control cluster startup
cat /etc/postgresql/13/main/start.conf


```
