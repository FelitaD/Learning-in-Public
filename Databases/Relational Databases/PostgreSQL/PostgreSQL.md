
Database type: https://www.notion.so/Relational-Databases-a3f456e217584528bbc53b866ea30297

PostgreSQL is an **object-relational** database management system (ORDBMS) with an emphasis on extensibility and standards compliance. 

- Core components : tables, constraints, triggers, roles, stored procedures and views

### [PSQL](https://tomcam.github.io/postgres/)
https://tomcam.github.io/postgres/
- Start server `postgres -D /usr/local/var/postgres`
    - IPv4 address
    - IPv6 address
    - Port
    - Unix socket : communication points on the same or different computers to exchange data → IP + port
    
    [“FATAL: le fichier de verrouillage” postmaster.pid “existe déjà”](https://www.notion.so/FATAL-le-fichier-de-verrouillage-postmaster-pid-existe-d-j-0fc364739eef4a3b88c8d411742aa5a0)
    
- Access server `psql postgres`
    
    `psql -U felita postgres`
    
- Dump DB
    
    pg_dump -h rdb.staging-pensieve.explain.fr -U admin_user -d pipeline_gi_impacters > pipeline_gi_impacters-18-10-2020.sql
    
    psql impacters < pipeline_gi_impacters-18-10-2020.sql
    
- Cheatsheets
    
    [PostgreSQL command line cheatsheet](https://gist.github.com/Kartones/dd3ff5ec5ea238d4c546)
    
    [psql Tips and Tricks - pgDash](https://www.notion.so/psql-Tips-and-Tricks-pgDash-f91a1d119e1e458290aa370b2266c0f0)
    

[PostgreSQL: Documentation: 14: Chapter 31. Logical Replication](https://www.notion.so/PostgreSQL-Documentation-14-Chapter-31-Logical-Replication-f5ad06c7a65545f69867b6176c25929e)

[PostgreSQL Tutorial - Learn PostgreSQL from Scratch](https://www.notion.so/PostgreSQL-Tutorial-Learn-PostgreSQL-from-Scratch-974747d2adc14c42bff2bf6733646899)

[postgresql - What's the fastest way to do a bulk insert into Postgres? - Stack Overflow](https://www.notion.so/postgresql-What-s-the-fastest-way-to-do-a-bulk-insert-into-Postgres-Stack-Overflow-a7e9d5420ad7487dbaedbbe314046405)

[sql - How to speed up insertion performance in PostgreSQL - Stack Overflow](https://www.notion.so/sql-How-to-speed-up-insertion-performance-in-PostgreSQL-Stack-Overflow-f0912f0db92f41958cf7c5ddb9dab231)

[Multiple INSERTS into one table and many to many table - Stack Overflow](https://www.notion.so/Multiple-INSERTS-into-one-table-and-many-to-many-table-Stack-Overflow-06b97c028672411d9e4f9e0313c19519)