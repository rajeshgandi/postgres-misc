```
Shall we begin the interview.
Before, getting into the technical discussion, briefly introduce yourself
WHat is the relevant experience with PostgrESQL and relevant with AWS Cloud
What's your role and responsibilities in your project?
what  is PostgreSQL ? And why do we choose that over other database systems

Can we do reindex in postgres
Can you discuss high availability in PostgreSQL and what methods you would use to ensure it?

Suppose, we deleted a physical file that related to a single table inside your base directory. What happenns to your database?
What are FSM and VM files that are generated in the base directory

What is the function of a Vacuum in PostgreSQL and why is it used?

Explain the streaming replication mechanism. How does repl works?

How would you troubleshoot a slow-running query in PostgreSQL?
Why and when would you partition a table in PostgreSQL? -- Extension 

What are the different backup strategies in PostgreSQL?

How would you identify and kill a long running process in PostgreSQL? --> What if it is in active, idle and idle in transaction state

Can you explain about Foreign Data Wrappers in PostgreSQL? When it is used
What steps do you take to enhance your database security?
Diff bewteen view and mview.. How you will refresh mview

What is the maximum size for a table in PostgreSQL?

pg_relation_filepath

how to know your data directory.

What is max_wal_senders
DIff bw VACUUM FREEZE and VACUUM FULL
What is the importance of postmaster.pid file in the base directory
Tell any 5 folders or files present inside data directory
How do you know the location your data directory
What is transaction wraparound ? -- Accordingly, there are only roughly four billion (232) possible Txids.
What is MVCC
Explain ACID properties. Explain Isolation
Isolation Levels -- dirty read, nonrepeatable read, phantom read,
Read uncommitted, Read Committed, Repeatable reads, Serializable

How you will troubleshoot when there is a prod issue? What's your approach
Tell any 3 changes you faced in production databases? And how did you solve it. What's your contribution.
How do you initialize the cluster
Diff between Vacuum and Vacuum analyze
Diff between explain and explain analyze
Without looking into the postgres.conf file --> how can you check any parametr group setting... Name the pg_catalog view
How you will take the backups? 
How many types of backup you can take with pg_dump
What is table-bloat and how you will fix it?
How to take a dump of a specific schema
Challenges you faced during  major upgrades ... What are the pre-requisites
Zero Downtime upgrades
How you will start and stop the cluster
How many ways we can install the postgres in your Linux machine
Supppose you observed, there is a performance impact during Autovacuum of a specific large table. And you want to disable. How do you do that?
ANy 5 background processes --> logger, checkpointer, walwriter, writer, archiver, stats collector, logical repl
Enable archive logging --> log_destination = 'stderr' logging_collector = on log_directory = 'log' log_filename = 'alert_postgresql.log'
what is max_wal_size
How do you get the control file information of your database.. pg_controldata
Why pgbench
what is search_path
How you will drop the entire schema 
Can we restore a single table from the total schema backup which is taken by pg_dump... If yes, which format is supported
PITR Recovery
Difference between role and user
Other than cat,cd, cp, mv, rm --> tell any 5 linux commands that you use frequently
Which GUI tool you use to access your database
Any 5 parameters that we use rarely, in postgresql.conf 
Diff bw straming and logical repl
pgbackrest
patroni, repmgr, efm
What details you will find inside hba.conf file

Do we have any Drawbacks of PostgreSQL and how have you addressed them in your work?
Mention Any 5 extensions and its use.
You have given a excle or csv file. How you will load that data into table 

How would you set up the monitoring of PostgreSQL database? What tools

Can you discuss an instance where you had to migrate a PostgreSQL database from one hosting platform to another?

WHy postgreSQL auto conf
5 column names in pg_stat_activity
Distingusish bw active, idle and idle in transaction states
what happends if I kill log processor 
bgwr, wal writer and checkpoint........
physical location of a table.... vm and fsm
what happen if i do rm one table file

static or dynamic. how to reflect dynamic

pg_squeeze and pg_repack
any 5 pg_catalog tables


shared_buffers ,.. bwst suggested size


how to you reflect the change of a dynamic parameters
3 parameters that require system restart.

psql: command not found....... how do you fix it

any 3 authentication methoods in pg_hba.conf
TYPE  DATABASE        USER            ADDRESS                 METHOD

local and host diff
reindex

(autovacuum_enabled = false);

maintenance_work_mem  -> improve the index creation and autovacuum activuty..  max_parallel_maintenance_workers

SHELL SCRIPTING....what tasks you automated using shell

how you will remove the old backups
any 3 third pary backup tools

backup only schema structure (metadata)

pg_squeeze vs pg_repack

authentication bases
which instance class in AWS


```
