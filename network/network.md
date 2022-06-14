ifconfig -L en0 inet
ifconfig -L en0 inet6
ipconfig getifaddr en0

netstat -r -f inet6: displays the routing table in your computer (this may take some time to completely finish):

netstat: give you detail information bout the network connectivity or network activity on your linu machine

netstat -a : all of the listening ports for tcp and udp connection
netstat -u udp
netstat -t tcp
netstat -at


curl -X POST google.com //This send a post request
curl -X POST --data "p1=value1&p2=value2" google.com
或者用-d代替--data ，一个-d 后面跟一个parameter， you can use multiple -d in one command
curl google.com
#### get the information from weather.csv to request
curl -o request https://raw.githubusercontent.com/ds5110/rdata/main/data/weather.csv

#### get the information from weather.csv to weather.csv
curl -O https://raw.githubusercontent.com/ds5110/rdata/main/data/weather.csv

#### It shows you http header
curl -I https://raw.githubusercontent.com/ds5110/rdata/main/data/weather.csv