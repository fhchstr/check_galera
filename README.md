# Usage
```
usage: check_galera [-h] [--user USER] [--password PASSWORD] [--host HOST]
                    [--port PORT] [--expected-size EXPECTED_SIZE] [--verbose]

Nagios check to monitor the health of a Galera cluster.

optional arguments:
  -h, --help            show this help message and exit
  --user USER, -u USER  MySQL user used to read the cluster status. Default:
                        root
  --password PASSWORD, -p PASSWORD
                        Password of the MySQL user
  --host HOST           Host to monitor. Default: 127.0.0.1
  --port PORT           TCP port used for the connection. Default: 3306
  --expected-size EXPECTED_SIZE, -e EXPECTED_SIZE
                        Alert if the cluster size is smaller than this value.
  --verbose, -v         Show verbose output
  ```
