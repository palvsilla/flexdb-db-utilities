# Offline MySQL Backup and Restore
This folders contains backup and restore utilities script and readme to setup.

The Backup and Restore Utility is a collection of wrapper scripts 
developed in Bash and Python that leverage MySQL Shell utilities to
provide a flexible and standardized framework for offline MySQL 
backup and restore operations.

The framework utilizes the following MySQL Shell functions:

util.dumpTables – Dumps one or more tables from a single database
util.dumpSchemas – Dumps one or more databases (schemas)
util.dumpInstance – Dumps the complete MySQL instance
util.loadDump – Restores backup dumps

This framework was designed to simplify backup management,
improve operational automation, and provide a scalable and 
versatile solution for future enhancements, maintenance, 
and enterprise backup requirements.
