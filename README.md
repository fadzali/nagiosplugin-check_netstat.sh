# nagiosplugin-check_netstat.sh
monitoring any listening and outgoing port 
netstat -tn | grep 7770
sudo check_netstat.sh -p 7770 -w 2 -c 5
