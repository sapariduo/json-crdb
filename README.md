# json-crdb
reder json and sink to cocroachdb table gpslog

[-] Usage

Replace db-host adn db-schema to target db

It can be used with shell script for loop file name using file walks method.

./ruptela-file-migration --file="./testfile.log" --db-host="localhost:26257" --db-schema="zz_log" --log-level=debug --worker-count=25
