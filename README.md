# promethous_graphana

## NOTE: if issue commes in promethus:  [[ Warning! Detected 105706.78 seconds time difference between your browser and the server. Prometheus relies on accurate time and time drift might cause unexpected query results.]] 
then run below command to worker/master node


1. Install below package to worker / master node.
   # apt-get install ntpdate
   # systemctl start ntpdate.service


2. check with this query **process_cpu_seconds_total** 
