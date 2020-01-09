# pl_sql-dblink-avaibility-check
Oracle database link activity check

run jobs:
- dblink_monitor_api.monitor
- dblink_monitor_api.monitor_deleted_jobs

and you will see Oracle Database DB link activity:

select * from DBLINK_MONITOR.V_DBLINKS t
