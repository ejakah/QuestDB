# QuestDB
CREATE TABLE process_metrics ( system_host_name STRING, pid STRING, cpu_usage DOUBLE, memory_usage DOUBLE, timestamp TIMESTAMP, process_status STRING );

SELECT * FROM process_metrics
