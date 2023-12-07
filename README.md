This Python script facilitates the migration of data from a remote CSV file stored on an SFTP server to a PostgreSQL database. It uses multithreading to improve efficiency, allowing for parallel processing of data chunks.

script reads the partitions file via sftp and writes each partition to postgres in a separate thread and pool
