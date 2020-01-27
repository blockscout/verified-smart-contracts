# verified-smart-contracts

All dumps are in `./pg-dumps` folder. A single file per chain. Each file can be restored in the Postgres DB into `smart-contracts` table with the following sample command:

```
pg_restore --host <db_host> --port <db_port>  -U <db-user> -d rink "./rinkeby_smart_contracts_table_dump" --verbose
```