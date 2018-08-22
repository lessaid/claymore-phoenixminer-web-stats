# claymore-phoenixminer-web-stats
Claymore-PhoenixMiner-Web-Stat is a simple PHP web stats page that utilizes the remote monitoring ports (JSON-RPC API) available on Claymore Miner and PhoenixMiner. This page allows you to view the following stats pulled from your miners:

* Global hashrate for all miners
* Miner uptime
* Miner version
* Connected pool and port
* Submitted, stale and invalid shares
* Per GPU hashrates
* Per GPU temperatures (with configurable thresholds)
* Per GPU fan percentages (with configurable thresholds)
* Auto Refreshing (configurable)



##How to use

Usage of the script is simple, and all you need to run it is a server with PHP and IIS/Apache

Installation Instructions

* Copy all files to a directory of your choice
* Edit `config.php` to update the server list, you can have as many or as few as you want
* Browse to `your/path/index.php` and view stats
* If you wish to edit the yellow and red warning thresholds for fan speed and GPU temp, you can change the values in `config.php`



##Screenshot

This is what the application looks like:

![Screenshot of claymore-phoenixminer-web-stats](https://raw.githubusercontent.com/jimok82/claymore-phoenixminer-web-stats/master/screenshot.png)

