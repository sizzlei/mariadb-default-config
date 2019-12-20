# mariadb-default-config
MariaDB Version 10.3 < 

## Vriables 
+ thread_pool_size 
  - CPU Core Count.
+ thread_pool_max_thread
  - Same max_connections value.
+ innodb_buffer_pool_size
  - OS Memory 50%~70%
+ innodb_buffer_pool_instances
  - buffer_pool_size / Data Size
+ innodb_write_io_threads / innodb_read_io_threads
  - CPU Core Count / 2
+ innodb_thread_concurrency
  - CPU Core Count * 2
+ innodb_io_capacity
  - Disk IOPS Value
  
Important! This is Default! Setting.
