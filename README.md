# TIG stack for RPI

Single install script for setting-up TIG stack on RPI. Configures a start-up dashboard as well.

TIG:
Telegraf agent, InfluxDB, Grafana

# Install Steps for jessie

* `git clone https://github.com/rpi-tig-stack`
* `cd rpi-tig-stack`
* `chmod 755 install.sh`
* `sudo ./install.sh`
* Execution time depends on network connection. Paste the grafana link into browser to access dashboards

Disclaimer:
I had a script for this lying around that I got from either a blog or maybe from Github, I had to modify it to work with my specific RPIand I don't remember where I got the orginal from - not very good open-source morals I know!
