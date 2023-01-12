# InfluxDB in Proxmox
Using InfluxDB to store Home Assistant data for Visualising in Grafana

## InfluxDB
InfluxDB is the time-series database handy to store your data coming from your Home Assistant instance. 
Since this will be a copy off the data in HA itself, I would recommend to use a separate LXC to run Influxdb.

## Install InfluxDB
- Go to the TTECK proxmox scripts and use the InfluxDB script
- Create a user named 'homeassistant'
- Create a database in InfluxDB named 'homeassistant' with same password.
- Make sure the user hass full acces on the database you just created

## Home Assistant Config
- add the following code to your Home Assistant configuration
- 
![image](https://user-images.githubusercontent.com/100353268/212092629-10b75feb-2959-4cf4-a09a-ee70c8e62a17.png)

