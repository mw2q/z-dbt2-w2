Fri May  1 17:38:45 BST 2015
no thinktime
Linux ECSPGSQL 3.0.76-0.11-default #1 SMP Fri Jun 14 08:21:43 UTC 2013 (ccab990) s390x s390x s390x GNU/Linux
Command line: /home/mark/bin/dbt2-run-workload -a pgsql -c 20 -d 600 -w 2 -o z-dbt2-w2 -s 100 -z no thinktime -p -c max_connections=50 -c checkpoint_segments=180 -c checkpoint_timeout=30min -c shared_buffers=2GB -c work_mem=16MB -r -n
Database Scale Factor: 2 warehouses
Test Duration: 600 seconds
Database Connections: 20
