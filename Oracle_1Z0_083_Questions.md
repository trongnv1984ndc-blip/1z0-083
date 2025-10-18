# Oracle 1Z0-083 Exam Questions (DumpsCollection Version 7.0)

## Question #:1
Your SALES_ROOT application container has two application PDBs.
The SALES_APP application has a common table, FIN.REVENUE, in the two PDBs.
Examine this query and its output:
Which two are true? (Choose two.)
The CONTAINERS clause cannot be used in queries on the REVENUE table.
The REVENUE table must be a list-partitioned table.
The MAPTABLE tables defines a logical partition key on a commonly used column for the REVENUE
table.
The MAPTABLE table is a metadata-linked table.
A container map exists for the REVENUE table, but is not enabled.
The REVENUE table partitions are not pruned across the PDBs automatically.
Answer: C F

---

## Question #:2
Which two are true about an RPM-based Oracle Database installation? (Choose two.)
It uses a service configuration script to create a single-instance database as part of the installation.
From Oracle Database 18c, a single RPM can be used to install only Oracle Database Server for a single
instance.
It performs a software-only Oracle Database installation.
It includes the Oracle Preinstallation RPM.
Oracle - 1z0-083 Dumps Q&A
2 of 84 Success Guaranteed, 100% ValidE.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  
A.  
B.  
C.  
D.  
E.  It requires an Unbreakable Linux Network (ULN) subscription.
Answer: D E

---

## Question #:3
Which three are true about opatchauto? (Choose three.)
It performs a shutdown and then a restart of all processes in both Oracle Grid Infrastructure and Oracle
Database home during the patching process.
It must be invoked by a user with root user privileges.
Patches are applied via opatchauto.
Users must always input patch plans to opatchauto.
It requires the Oracle Grid Infrastructure and Oracle Database instances to be shut down before being
invoked.
It applies patches in nonrolling mode by default.
It is used to apply interim patches to Oracle Grid Infrastructure and Oracle Database home
combinations.
Answer: A B G

---

## Question #:4
Which three are true about creating container databases (CDBs) and pluggable databases (PDBs) in Oracle
19c and later releases? (Choose three.)
A PDB snapshot can be a sparse copy of a source PDB.
A PDB snapshot depends on an existing storage snapshot of the source PDB.
A CDB can be duplicated using Recovery Manager (RMAN) with no configuration required before
starting
the duplication.
A CDB can be duplicated using the Database Configuration Assistant (DBCA) in silent mode with no
configuration required before starting the duplication.
A PDB snapshot can be a full copy of a source PDB.
Oracle - 1z0-083 Dumps Q&A
3 of 84 Success Guaranteed, 100% ValidF.  
G.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  A snapshot copy PDB can be a full copy of a source PDB.
A snapshot copy PDB does not depend on an existing storage snapshot of the source PDB.
Answer: A B F

---

## Question #:5
Which three are true about actions that can or cannot be performed by users with the SYSBACKUP privilege?
(Choose three.)
They can view data from any data dictionary view or dynamic performance view.
They cannot create restore points.
They cannot drop tablespaces.
They can create any table.
They can drop any tablespace.
They can view data from any user-defined tables.
Answer: C D

---

## Question #:6
Which two are true about creating pluggable databases (PDBs) using snapshots in Oracle 19c and later
releases? (Choose two.)
A PDB snapshot is always a full copy of the source PDB.
A PDB snapshot is always a sparse copy of the source PDB.
A snapshot copy PDB depends on a storage snapshot which can only be stored on specific file systems.
A PDB snapshot depends on a storage snapshot which can be stored on any file system.
A PDB snapshot depends on a storage snapshot which can only be stored on specific file systems.
A snapshot copy PDB depends on a storage snapshot which can be stored on any file system.
A snapshot copy PDB can be created from a stand-alone clone PDB.
Answer: C G
Oracle - 1z0-083 Dumps Q&A
4 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.

---

## Question #:7
Which three are true about a whole database backup? (Choose three.)
It can consist of either backup sets or image copies.
It is the only possible backup type for a database in NOARCHIVELOG mode.
It can be consistent.
It can be created only by using RMAN.
It can be inconsistent.
It always includes all data files, the current control file, the server parameter file, and archived redo logs.
Answer: A C F

---

## Question #:8
Which three resources are always shared among CDB$ROOT and pluggable databases (PDBs)? (Choose
three.)
the data dictionary in CDB$ROOT
temporary tablespaces
the Process Monitor Process (PMON)
SYSAUX tablespaces
the log writer process (LGWR)
undo tablespaces
Answer: A B C

---

## Question #:9
Which two are true about creating RMAN backups for an Oracle container database? (Choose two.)
Online Redo Log backups can be created while connected to the root container.
Control file backups can be created while connected to the root container.
Oracle - 1z0-083 Dumps Q&A
5 of 84 Success Guaranteed, 100% ValidC.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  The BACKUP TABLESPACE command can back up a PDB tablespace even if RMAN is connected to
CDB$ROOT.
Archived Redo Log backups can be created while connected to an application root CDB.
Control file backups can be created while connected to a nonroot container.
Answer: D E

---

## Question #:10
Your CDB has two regular PDBs as well as one application container with two application PDBs and an
application seed.
No changes have been made to the standard PDB$SEED.
How many default temporary tablespaces can be assigned in the CDB?
six
seven
five
eight
three
Answer: C

---

## Question #:11
Which three actions will add a resource to an Oracle Restart configuration? (Choose three.)
creating an Oracle Database service by modifying the SERVICE_NAMES parameter
creating a disk group using the CREATE DISKGROUP SQL statement
creating a database using the CREATE DATABASE SQL statement
creating a database service using DBMS_SERVICE.CREATE_SERVICE
creating a database service using Oracle Database Configuration Assistant (DBCA)
Oracle - 1z0-083 Dumps Q&A
6 of 84 Success Guaranteed, 100% ValidF.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  
A.  
B.  
C.  
D.  
E.  
F.  creating an Oracle Automatic Storage Management (ASM) instance with ASM Configuration Assistant
(ASMCA)
Answer: C D E

---

## Question #:12
Which three true about recovering tables using RMAN? (Choose three.)
RMAN can recover tables in the SYSAUX tablespace.
RMAN can recover tables owned by the SYS user.
RMAN can recover tables in the SYSTEM tablespace.
RMAN always uses an auxiliary instance.
RMAN can recover tables in a standby database.
RMAN can recover a table after a DDL operation has altered the table structure.
RMAN can recover tables owed by the SYSTEM user.
Answer: A C D

---

## Question #:13
Which three are true about Audit policies In container databases (CDBs)?
All audit records are written to the audit trail in CDB$ROOT
A common unified audit policy can be created at the application root level.
A common unified audit policy can be created at the CDB level.
An application PDB cannot have a local audit policy.
Fine-grained auditing policies defined in an application root must be manually synchronized by each
application PDB contained in the application root.
Application-common unified audit policies defined In an application root must be manually
synchronized by each application PDB contained in the application root.
Answer: D E F
Oracle - 1z0-083 Dumps Q&A
7 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.

---

## Question #:14
Which three are true about the FLASHBACK DATABASE feature? (Choose three.)
FLASHBACK LOGS are archived after a log switch.
A database can be flashed back using SQL*PLUS.
Queries and DML have the same FLASHBACK LOG overhead when flashback is enabled for a
database.
FLASHBACK DATABASE only uses FLASHBACK LOGS to get the database to the desired flashback
time.
It always generates REDO and UNDO.
It requires that the target database be in ARCHIVELOG mode.
Answer: B C F

---

## Question #:15
For which two requirements can you use the USER_TABLESPACE clause with the CREATE PLUGGABLE
DATABASE command? (Choose two.)
to specify a default tablespace in a PDB cloned from another PDB in the same CDB.
to exclude all tablespaces except SYSTEM, SYSAUX, and TEMP when plugging in a PDB
to include specific user tablespaces only when relocating a PDB
to specify the list of user tablespaces to include when moving a non-CDB to a PDB
to exclude a temp tablespace when plugging in a PDB
to specify the list of tablespaces to include when creating a PDB from the CDB seed
Answer: D F

---

## Question #:16
You plan to perform cross-platform PDB transport using XTTS.
Which two are true? (Choose two.)
A backup of the PDB must exist, taken using the BACKUP command with the TO PLATFORM clause.
Oracle - 1z0-083 Dumps Q&A
8 of 84 Success Guaranteed, 100% ValidB.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  The source PDB must be in MOUNT state.
The source PDB must not be an application root.
The source PDB can be in MOUNT or OPEN state.
The source and target platforms must have the same endianness.
Automatic conversion of endianness occurs.
Answer: D E

---

## Question #:17
Which three are true about an application seed pluggable database (PDB)? (Choose three.)
It is automatically synchronized with its application root PDB when an application is upgraded.
It cannot be added to an application container after the application container has already been created.
A new application PDB created by cloning an application seed PDB can have an old version of the
application installed after cloning completes.
It is automatically synchronized with its application root PDB when an application is installed.
It cannot be dropped from its application container.
A new application PDB created by cloning an application seed PDB can have an up-to-date version of
the application installed after cloning completes.
It is not required in an application container.
Answer: D F G

---

## Question #:18
You want to transport the UNIVERSITY tablespace from one database to another.
The UNIVERSITY tablespace is currently open read/write.
The source and destination platforms have the same endian format.
Examine this list of steps:
1. Make the UNIVERSITY tablespace read-only on the source system.
2. Export the UNIVERSITY tablespace metadata using EXPDP.
Oracle - 1z0-083 Dumps Q&A
9 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
A.  
B.  
C.  
D.  
E.  3. Create a cross-platform backup set from the UNIVERSITY tablespace on the source system, using an
RMAN command that includes the DATAPUMP clause.
4. Copy the cross-platform backup sets to the destination system.
5. Copy the Data Pump dump set from the source to the destination system.
6. Restore the cross-platform backup set on the destination system using an RMAN command that includes
the DATAPUMP clause.
7. Import the UNIVERSITY tablespace metadata using IMPDP.
8. Make the UNIVERSITY tablespace read/write on the destination system.
Which are the minimum number of steps required, in the correct order, to transport the UNIVERSITY
tablespace?
1, 3, 4, 6, 8
3, 4, 6
1, 2, 3, 4, 5, 6, 7, 8
2, 3, 4, 5, 6, 7
Answer: A

---

## Question #:19
Which two are true about the Program Global Area (PGA) and its management in an Oracle database
instance? (Choose two.)
The private SQL area (UGA) is located in the System Global Area (SGA) when using dedicated servers.
PGA_AGGREGATE_LIMIT is a hard limit on the PGA size for any one session.
The entire PGA is located in the System Global Area (SGA) when using shared servers.
Sorts and Hash Joins use PGA memory.
The private SQL area (UGA) is located in the System Global Area (SGA) when using shared servers.
Answer: A B
Oracle - 1z0-083 Dumps Q&A
10 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.

---

## Question #:20
PDB1 and PBD2 are pluggable databases in CDB1.
Examine these commands:
CDB1 is then restarted.
Which three are true? (Choose three.)
PDB2 will be MOUNTED.
PDB1 will be MOUNTED.
PDB$SEED will be opened READ ONLY.
PDB2 will be opened READ WRITE.
PDB1 will be opened READ WRITE.
Oracle - 1z0-083 Dumps Q&A
11 of 84 Success Guaranteed, 100% ValidF.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  
H.  
A.  
B.  PDB$SEED will be MOUNTED.
Answer: C D E

---

## Question #:21
Which four are true about duplicating a database using Recovery Manager (RMAN)? (Choose four.)
Duplication can be done by having the auxiliary database instance pull backup sets from the target
database instance.
A connection to an auxiliary instance is always required.
A subset of the target database can be duplicated.
A new DBID is always created for the duplicated database.
A connection to the recovery catalog instance is always required.
A backup of the target database is always required.
Duplication can be done by having the target database instance push copies to the auxiliary database
instance.
A connection to the target database instance is always required.
Answer: A B C G
Explanation
A duplicate database is a copy of your target database. With the FOR STANDBY clause, it keeps the same
unique database identifier(DBID); If FOR STANDBY not specified it creates a new DBID. The duplicate
database can include the same content or only a subset from the source database. It can be in the same host or
a separate host. The principal work of the duplication is performed by the auxiliary channels.These channels
correspond to a server session on the auxiliary instance on the destination host for backup based duplication.
For active database duplication the target channels perform the work of pushing data file copies to the
auxiliary instance (if number of allocated target channels is greater than the number of allocated auxiliary
channels).

---

## Question #:22
A schema owner truncated a table in error and must recover the data.
Which Oracle Flashback feature could be used to recover the data?
FLASHBACK TRANSACTION
FLASHBACK VERSION QUERY
Oracle - 1z0-083 Dumps Q&A
12 of 84 Success Guaranteed, 100% ValidC.  
D.  
E.  FLASHBACK DATA ARCHIVE
FLASHBACK TABLE
FLASHBACK DATABASE
Answer: B

---

## Question #:23
Examine these queries and their output:
After a system crash, an instance restart and an attempted opening of the PDBs result in:
Oracle - 1z0-083 Dumps Q&A
13 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
Which two are true? (Choose two.)
Data file 24 can be recovered while PDB2 is opened.
Data file 24 must be recovered while the CDB is opened.
Data file 24 can be recovered while CDB$ROOT and PDB$SEED are opened.
Data file 24 cannot be recovered while the CDB is opened.
Data file 24 must be recovered while PDB2 is closed.
Answer: A B
Explanation
19c: PDB SYSTEM or UNDO Tablespace Recovery: The CDB and all other PDBs can be left opened. 1.
Connect to PDB 2. Shutdown abort the PDB, if its not automatically done. sqlplus sys@sales_pdb as sysdba
sql> SHUTDOWN ABORT; OR ALTER PLUGGABLE DATABASE CLOSE ABORT; rman target
sys@slaes_pdb rman> restore database; rman> recover database; rman> alter pluggable database sales_pdb
open;

---

## Question #:24
Which three are true about using an RMAN Recovery Catalog with a pluggable database (PDB) target
connection in Oracle Database 19c and later releases? (Choose three.)
The base catalog owner must give the Virtual Private Catalog access to metadata for one or more PDBs.
The base catalog must be enabled for Virtual Private Catalog use.
The target PDB must be registered in a base catalog.
Oracle - 1z0-083 Dumps Q&A
14 of 84 Success Guaranteed, 100% ValidD.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  The base catalog must be used by RMAN when performing point-in-time recovery for the PDB
registered
in the Virtual Private Catalog.
The target PDB must be registered in a Virtual Private Catalog.
The target PDB must be registered in both the base catalog and the Virtual Private Catalog.
Answer: A D E

---

## Question #:25
Which two are facets of performance planning that should always be considered or implemented for an Oracle
Database environment? (Choose two.)
defining primary keys for all tables to speed up all queries
using check constraints to speed up updates
defining foreign keys for all tables to speed up joins
the physical data model
the configuration of storage arrays
Answer: D E

---

## Question #:26
Which two are true about creating RMAN backups for an Oracle container database? (Choose two.)
Tablespaces from different PDBs with identical names must be backed up by connecting RMAN
separately to each PDB to back up the tablespaces.
The BACKUP DATABASE command will create a pluggable database (PDB) backup when RMAN is
connected to a PDB.
SPFILE backups can be created while connected to an application root PDB.
The BACKUP DATABASE PLUS ARCHIVELOG command will back up archive logs when RMAN is
connected to a PDB.
The BACKUP PLUGGABLE DATABASE command can be used to back up CDB$ROOT.
Answer: A B
Oracle - 1z0-083 Dumps Q&A
15 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.

---

## Question #:27
Which three actions are performed by Database Upgrade Assistant (DBUA)? (Choose three.)
It recompiles all stored PL/SQL code by using utlrp.sql.
It empties the RECYCLE BIN.
It performs prerequisite checks to verify if the Oracle database is ready for upgrade.
It sets all user tablespaces to “read-only” before starting the upgrade.
It removes the AUDSYS schema and the AUDIT_ADMIN and AUDIT_VIEWER roles
It increases tablespace size, if required, to meet upgrade requirements.
Answer: A C F

---

## Question #:28
Which three are true about Automatic Workload Repository (AWR)? (Choose three.)
By default, AWR snapshots are taken every 60 minutes.
Its collection level is determined by the value of the STATISTICS_LEVEL database parameter.
By default, AWR snapshots are retained for 7 days.
The taking of AWR snapshots can be disabled.
AWR data is stored in the SYSTEM tablespace.
Answer: A B D

---

## Question #:29
Which two are true about diagnosing Oracle Database failure situations using Data Recovery Advisor?
(Choose two.)
Using the Data Recovery Advisor LIST FAILURE command always requires that the database for
which failures are to be listed is in MOUNT state.
A failure can be closed only when it has been repaired.
Data Recovery Advisor can be used if a database is closed.
Oracle - 1z0-083 Dumps Q&A
16 of 84 Success Guaranteed, 100% ValidD.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  The Data Recovery Advisor CHANGE FAILURE command can be used only to change failure
priorities.
Data Recovery Advisor can proactively check for failures.
Answer: D E

---

## Question #:30
The HR_ROOT application container must support the execution of a query on a table shared by application
local PDBs PDB1 and PDB2, and remote PDB PDB3.
Which three are true? (Choose three.)
A proxy PDB must exist in the application root in the remote CDB.
A database link must exist in the local CDB root referring to the remote CDB.
PDB3’s application root replica must exist in the local CDB.
A database link must exist in the remote CDB referring to the local CDB.
The HR_ROOT replica must exist in the remote CDB.
A proxy PDB must exist in the application root in the local CDB.
Answer: D E F

---

## Question #:31
Which two are true about RMAN encryption? (Choose two.)
RMAN encryption keys are stored in a database keystore.
RMAN can encrypt the Oracle Database password file.
Dual-mode encrypted backups can be restored only if both the password and the keystore used for
encryption are available.
The SET ENCRYPTION command overrides encryption settings specified by the CONFIGURE
ENCRYPTION command.
Password encryption can be persistently configured using the CONFIGURE ENCRYPTION command.
Answer: C D
Oracle - 1z0-083 Dumps Q&A
17 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.

---

## Question #:32
Which two are true about RMAN backups when using a media manager? (Choose two.)
A media manager always writes RMAN requested backups to tape.
By default, a request for a proxy copy may result in a backup set being created.
A media manager is required to create RMAN proxy copies.
A media manager is required to create RMAN image copies.
The media manager layer (MML) routines provided by Oracle support any vendors’ media management
products.
Answer: A D

---

## Question #:33
Which three are true about transporting databases across platforms using Recovery Manager (RMAN) image
copies? (Choose three.)
By default, the transported database will use Oracle Managed Files (OMF)
Data files can be converted on the destination system.
Data files can be converted on the source system.
A new DBID is automatically created for the transported database.
Databases can be transported between systems with different endian formats.
The password file is automatically converted by RMAN.
Answer: A B C
Explanation
A: If you do not provide a destination, then the DB_FILE_CREATE_DEST initialization parameter must be
set in the target platform. RMAN restores the data files to the location specified by this parameter using new
Oracle Managed File (OMF) names. BC: While creating the cross-platform backup to transport a database,
you can convert the database either on the source database or the destination database. The benefit of
performing the conversion on the destination database is that the processing overhead of the convert operation
is offloaded from the source to the destination database.

---

## Question #:34
Oracle - 1z0-083 Dumps Q&A
18 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  Examine this output:
Which two are true? (Choose two.)
Any PDB not specified in the plan will be unable to execute statements in parallel.
PDB3 can use all available parallel execution processes at times.
PDB1 is always limited to 40% of the available system resources regardless of demand.
Any PDB not specified in the plan will be able to use a maximum of 16.5% of the available system
resources.
PDB3 is guaranteed to receive at least 20% of the available system resources if there is enough demand.
PDB2 is guaranteed at least 25% of the available parallel execution processes if there is enough demand.
Answer: A E

---

## Question #:35
Which two are true about Optimizer Statistics? (Choose two.)
They can be gathered by the DBMS_STATS package.
They are gathered by the SQL Tuning Advisor.
They provide real-time data about schema objects.
Oracle - 1z0-083 Dumps Q&A
19 of 84 Success Guaranteed, 100% ValidD.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  They are ignored by Optimizer if they are stale.
By default, they are automatically gathered by a maintenance job.
Answer: A E

---

## Question #:36
Which three are true about upgrading Oracle Grid Infrastructure? (Choose three.)
A direct upgrade can be performed only from the immediately preceding Oracle Grid Infrastructure
version.
The newer version is installed in a separate Oracle Grid Infrastructure home on the same server as the
existing version.
An existing Oracle base can be used.
The upgrade process will automatically install all mandatory patches for the current version of Oracle
Grid Infrastructure.
Existing Oracle Database instances must be shut down before starting the upgrade.
Only the grid user can perform the upgrade.
Answer: B C F

---

## Question #:37
Which should be tuned first when doing a performance tuning exercise for an Oracle Database environment?
SQL statements
log writer performance
general operating system health
database writer performance
database instance memory management and sizes
Answer: A

---

## Question #:38
Oracle - 1z0-083 Dumps Q&A
20 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  A user complains about poor database performance.
You want to verify if the user’s session has waited for certain types of I/O activity. Which view displays all
waits waited on by a session at least once?
V$SESSION_EVENT
V$SESSTAT
V$SESSION_WAIT
V$SESSION_WAIT_CLASS
V$SESSION
Answer: A

---

## Question #:39
Which three are true about Automatic Workload Repository (AWR) snapshots? (Choose three.)
They are generated if STATISTICS_LEVEL is set to TYPICAL.
They are generated if STATISTICS_LEVEL is set to ALL.
They are always created automatically.
They are always created manually.
They can be retained forever.
They are generated if STATISTICS_LEVEL is set to BASIC.
Answer: A C F

---

## Question #:40
Which two are true about OS groups and users for Oracle Grid Infrastructure and the Oracle Relational
Database Management System (RDBMS)? (Choose two.)
By default, members of the OSASM group can access Automatic Storage Management and RDBMS
instances.
The primary group for the Oracle Grid Infrastructure and Oracle Database owners must be the Oracle
Inventory group.
Oracle - 1z0-083 Dumps Q&A
21 of 84 Success Guaranteed, 100% ValidC.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  The Oracle Grid Infrastructure installation must be owned by the grid user.
The Oracle Grid Infrastructure owner owns Oracle Restart and Oracle Automatic Storage Management
binaries.
The Oracle Grid Infrastructure owner must have OSOPER, OSBACKUPDBA, and OSKMDBA as
secondary groups.
The same OSDBA group must be used for Automatic Storage Management and the Oracle Database.
Answer: B D

---

## Question #:41
Which two are true about automatic block repair? (Choose two.)
Automatic block repair can repair blocks with no standby database if DB_BLOCK_CHECKING =
TRUE.
Real-Time Query must be enabled on a physical standby database for automatic block repair to be done
on that physical standby database.
Real-Time Query must be enabled on a primary database for automatic block repair to be done on any of
its physical standby databases.
It is not possible for media corrupt blocks.
Real-Time Query must be enabled on a physical standby database for automatic block repair to be done
on its primary database.
Answer: B C

---

## Question #:42
Which two are prerequisites for using FLASHBACK TABLE? (Choose two.)
A table’s constraints must be disabled before issuing the flashback.
The FLASHBACK ANY TABLE system privilege or the FLASHBACK object privilege must be
granted to the
user performing the flashback.
A table’s indexes must be set to unusable before issuing the flashback.
Row Movement must be enabled on the table being flashed back.
Oracle - 1z0-083 Dumps Q&A
22 of 84 Success Guaranteed, 100% ValidE.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  The FLASHBACK ANY TABLE system privilege or the FLASHBACK object privilege must be
granted to the
table owner.
Answer: B E

---

## Question #:43
Which two are true about Rapid Home Provisioning of Oracle software? (Choose two.)
It can be used for applications and middleware.
It can be used only for Oracle Grid Infrastructure, excluding Oracle Restart.
It can be used only for Oracle Grid Infrastructure, including Oracle Restart.
It can be used for both Oracle Database and Oracle Grid Infrastructure, including Oracle Restart.
It can be used for both Oracle Database and Oracle Grid Infrastructure, excluding Oracle Restart.
Answer: B E
Explanation
Reference https://docs.oracle.com/en/database/oracle/oracle-database/12.2/cwadd/rapid-homeprovisioning.
html#GUID-CCEC5960-EDA4-4A3F-9643-0CA308EA49AA

---

## Question #:44
Your container database, CDB1, has an application container, HR_ROOT, with an application PDB,
HR_PDB1.
You have the required privilege to clone HR_PDB1 to container database CDB2, which does not contain
HR_ROOT.
Which two are always true? (Choose two.)
CDB1 and CDB2 must be in shared undo mode.
A common user must exist in CDB2 with the CREATE PLUGGABLE DATABASE privilege.
All transactions in HR_PDB1 of CDB1 must commit before the cloning process starts.
Cloning HR_ROOT automatically clones HR_PDB1.
The HR_PDB1 clone created in CDB2 will be in mount state when cloning ends.
Oracle - 1z0-083 Dumps Q&A
23 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  Answer: B D

---

## Question #:45
A container database (CDB) contains two pluggable databases PDB1 and PDB2.
The LOCAL_UNDO_ENABLED database property is set to FALSE in the CDB. Data file 24 of PDB2 was
deleted and you need to restore and recover it.
The only RMAN backup that exists was created with the BACKUP DATABASE command while connected
to
CDB$ROOT.
Which three are true? (Choose three.)
Data file 24 can be recovered only while connected to PDB2.
Data file 24 can be restored and recovered while connected to CDB$ROOT.
Data file 24 can be restored only while connected to CDB$ROOT.
Data file 24 can be restored only while connected to PDB2.
Data file 24 can be recovered while connected to PDB2.
Data file 24 can be recovered while connected to CDB$ROOT.
Answer: B C F

---

## Question #:46
Which three are true about an application container? (Choose three.)
It can contain a single application.
It can contain multiple applications.
It must have an application seed PDB.
It must have an application root PDB.
Two application containers can share an application seed PDB.
An application PDB can belong to multiple application containers.
Oracle - 1z0-083 Dumps Q&A
24 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  Answer: A D F

---

## Question #:47
How do you configure a CDB for local undo mode?
Open the CDB instance in upgrade mode. In CDB$ROOT, execute ALTER DATABASE LOCAL
UNDO ON,
and then restart the CDB instance.
Open the CDB instance in restricted mode. In CDB$ROOT, execute ALTER DATABASE LOCAL
UNDO ON,
and create an UNDO tablespace in each PDB, then restart the CDB instance.
Open the CDB instance in restricted mode. In CDB$ROOT, drop the UNDO tablespace. Execute
ALTER
DATABASE LOCAL UNDO ON in each PDB, and then restart the CDB instance.
Open the CDB instance in read-only mode. In CDB$ROOT, execute ALTER DATABASE LOCAL
UNDO ON,
and then change the CDB to read/write mode.
Open the CDB instance in upgrade mode. In each PDB, execute ALTER DATABASE LOCAL UNDO
ON,
create an UNDO tablespace, and then restart the CDB instance.
Answer: B

---

## Question #:48
Which statement correctly describes the SQL profiling performed by the SQL Tuning Advisor?
It is a set of recommendations by the optimizer to create new indexes.
It is a set of recommendations by the optimizer to restructure a SQL statement to avoid suboptimal
execution plans.
It is auxiliary information collected by the optimizer for a SQL statement to help use better joins orders.
It is auxiliary information collected by the optimizer for a SQL statement to eliminate estimation error.
Oracle - 1z0-083 Dumps Q&A
25 of 84 Success Guaranteed, 100% ValidE.  
A.  
B.  
C.  
D.  
E.  It is a set of recommendations by the optimizer to change the access methods used.
Answer: B

---

## Question #:49
Application PDBs, SALES_APP1 and SALES_APP2, must be created and they must access common tables of
the SALES_APP application.
Examine these steps:
1. Install the SALES_APP application, including the common tables, in the application root.
2. Install the SALES_APP application in the application root and the common tables in both the CDB root and
the application root.
3. Create an application seed.
4. Install the SALES_APP application in the application seed.
5. Create the SALES_APP1 and SALES_APP2 application PDBs.
6. Sync the SALES_APP1 and SALES_APP2 application PDBs with the application root.
7. Sync the SALES_APP1 and SALES_APP2 application PDBs with the application seed.
8. Sync the application seed with the application root.
Which are the minimum required steps in the correct sequence?
3,4,1,6,8
1,5,6
1,3,5,6,7
1,3,5,7
2,5,6
Answer: B

---

## Question #:50
While backing up to an SBT channel, you determine that the read phase of your compressed Recovery
Manager (RMAN) incremental level 0 backup is a bottleneck.
Oracle - 1z0-083 Dumps Q&A
26 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  FORCE LOGGING is enabled for the database.
Which two could improve read performance? (Choose two.)
Increase the size of tape I/O buffers.
Disable FORCE LOGGING for the database.
Increase the size of the database buffer cache.
Enable asynchronous disk I/O.
Increase the level of RMAN multiplexing.
Answer: D E

---

## Question #:51
Which two are true about reclaiming space used by Flashback logs in Oracle Database 19c and later
releases? (Choose two.)
Space is always reclaimed automatically when the retention period for Flashback logs is lowered.
Space might be reclaimed proactively before space pressure occurs.
Space might be reclaimed automatically when the retention period for Flashback logs is lowered.
Space is only reclaimed when there is space pressure in the Fast Recovery Area. (FRA)
Space is always reclaimed proactively before space pressure occurs.
Answer: C D

---

## Question #:52
Which are three of the steps taken by Database Configuration Assistant (DBCA) to clone a remote pluggable
database (PBD) starting from Oracle 19c? (Choose three.)
creating a database link from CDB$ROOT in the local database to the PDB in the remote system that is
to be cloned
creating a database link from CDB$ROOT in the local database to CDB$ROOT in the remote system
that is to
be cloned
Oracle - 1z0-083 Dumps Q&A
27 of 84 Success Guaranteed, 100% ValidC.  
D.  
E.  
F.  
G.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  
A.  
B.  creating a new empty PDB in the local database from PDB$SEED
creating a database link from CDB$ROOT in the remote database to be cloned to CDB$ROOT in the
local database
automatically dropping the database link to the remote database if it already exists
creating a database link from CDB$ROOT in the remote database to the PDB in the local database
opening the cloned PDB
Answer: B E F

---

## Question #:53
Which three are true about performing an Oracle Database install on Linux? (Choose three.)
The runfixup.sh script can install missing RPMs.
The Oracle Preinstallation RPM must be used to configure the Oracle database installation owner, the
Oracle Inventory group, and an Oracle administrative privileges group.
It allows you to select the languages supported by the Oracle database server.
It can be done before installing Grid Infrastructure for a Standalone Server.
The Oracle Preinstallation RPM can be used to configure the Oracle database installation owner, the
Oracle Inventory group, and an Oracle administrative privileges group.
It can be done after installing Grid Infrastructure for a Standalone Server.
The Oracle database administrator must be granted access to the root operating system account to tun
root privileged scripts.
Answer: C E G

---

## Question #:54
Which three are true about SGA memory management in a multitenant database? (Choose three.)
Setting DB_CACHE_SIZE for a PDB guarantees a minimum amount of Database Buffer Cache
memory for
that PDB.
The SHARED_POOL_SIZE setting for a PDB can be up to 80% of the SHARED_POOL_SIZE setting
Oracle - 1z0-083 Dumps Q&A
28 of 84 Success Guaranteed, 100% ValidB.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  of the
root container.
Setting SHARED_POOL_SIZE for a PDB guarantees a minimum amount of Shared Pool memory for
that
PDB.
The SGA_TARGET setting for a PDB cannot exceed 50% of the SGA_TARGET value of the root
container.
Setting SGA_TARGET for a PDB guarantees a minimum amount of SGA memory for that PDB.
SGA_MIN_SIZE cannot be set for a PDB.
Answer: C E F

---

## Question #:55
Which three are true about thresholds, metrics, and server-generated alerts? (Choose three.)
All metrics are instance related.
Cleared stateful alerts are displayed by querying DBA_ALERT_HISTORY.
A space usage management alert is automatically cleared after the underlying problem is resolved.
They are generated by SMON when a tablespace is 97% full.
Metrics are statistical counts for a specific unit.
STATISTICS_LEVEL must be set to ALL to generate alerts.
Answer: B C E

---

## Question #:56
Which three are true about Database Point-in-Time Recovery? (Choose three.)
The database must have FLASHBACK DATABASE ON to perform Database Point-in-Time Recovery.
The database must be in MOUNT state when performing Database Point-in-Time Recovery.
Database Point-in-Time Recovery is performed by the Managed Recovery Process (MRP)
The Database must be in ARCHIVELOG mode.
Oracle - 1z0-083 Dumps Q&A
29 of 84 Success Guaranteed, 100% ValidE.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  
A.  The target point for the recovery must be specified as a stime or System Change Number (SCN).
The database must be open RESETLOGS after Database Point-in-Time Recovery.
Answer: B D F
Explanation
https://docs.oracle.com/cd/B19306_01/backup.102/b14192/flashptr006.htm#:~:text=Database%20point%2Din%2Dtime%20recovery%20(DBPITR)%20restores%20the,forward%20to%20the%20target%20time.

---

## Question #:57
You issued this command:
RMAN> BACKUP RECOVERY AREA FORCE;
Which three are true? (Choose three.)
All files in the current FRA that have been backed up already, are backed up.
All Oracle recovery files normally written to the FRA and which have been backed up already to the
current
FRA, are backed up.
All Oracle recovery files normally written to the FRA and which have been backed up already to in any
previous FRA, are backed up.
All Oracle recovery files normally written to the FRA and which have not yet been backed up, are
backed
up.
All files in any previous FRA that have not yet been backed up, are backed up.
All files in the current fast recovery area (FRA) that have not yet been backed up, are backed up.
All files in any previous FRA that have been backed up already, are backed up.
Answer: D F G

---

## Question #:58
Which three are located by using environment variables? (Choose three.)
the Optimal Flexible Architecture (OFA) compliant path to store Oracle software and configuration
files.
Oracle - 1z0-083 Dumps Q&A
30 of 84 Success Guaranteed, 100% ValidB.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  the location of Oracle Net Services configuration files
the list of a disk group names to be mounted by an Oracle Automatic Storage Management (ASM)
instance at startup
default directories for temporary files used by temporary tablespaces
the temporary disk space used by Oracle Installer during installation
the maximum number of database files that can be opened by a database instance
Answer: A B E

---

## Question #:59
A database is configured in ARCHIVELOG mode.
Full RMAN backups are taken and no backup to trace has been taken of the control file. A media failure has
occurred.
In which two scenarios is complete recovery possible? (Choose two.)
when any archived log from, before, or after the most recent backup is corrupt.
after losing all copies of the control file
after losing an archived log from after the most recent backup
after losing an archived log from before the most recent backup
after losing the SYSTEM tablespace
Answer: D E

---

## Question #:60
You have configured RMAN SBT channels to write backups to media.
You then take an RMAN backup by using this command:
Oracle - 1z0-083 Dumps Q&A
31 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  Which three are true? (Choose three.)
The restore point is a label for the system change number (SCN) that will be saved two years after the
archival backup was taken.
The data file backups in the self-contained archive backup are not considered obsolete for two years
regardless of the retention policy.
All archive logs created after this backup are kept for two years.
The SPFILE is included in the self-contaied archival backup.
The control file is included in the self-contained archival backup.
The restore point is a label for the system change number (SCN) before the archival backup was taken.
Answer: B D E
Explanation
https://docs.oracle.com/cd/E18283_01/server.112/e17118/statements_6011.htm
http://devel.hotpilot.cz/ora11gR2u2-full/backup.112/e10643/rcmsubcl011.htm An example:
http://www.online-database.eu/recovery-manager-rman/143-rman-backupsets-with-restore-point

---

## Question #:61
On the 10th of August, you implement an incremental database backup strategy and configure a recovery
window of five days.
Level 0 backups are taken on the 10th, 17th, and 24th of August.
Differential level 1 incremental backups are taken daily between the level 0 backups.
Today is the 26th of August.
Which backups will be obsolete?
all backups prior to 10th of August
all backups prior to 22nd of August
all backups prior to 24th of August
all backups prior to 20th of August
all backups prior to 17th of August
Answer: C
Oracle - 1z0-083 Dumps Q&A
32 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
G.  
A.

---

## Question #:62
Which three activities are possible for PDBs? (Choose three.)
converting an application PDB to a regular PDB
converting an application PDB to an application root
converting an application seed to an application PDB
converting an application PDB to an application seed
converting a regular PDB to an application PDB
converting an application container into another application container in a different CDB
converting an application container into another application container in the same CDB
Answer: A E G

---

## Question #:63
Examine this configuration:
CDB1 is an Oracle Database 12c Release 2 database containing pluggable databases PDB$SEED,
PDB1, and PDB2.
PDB$SEED is open READ ONLY
PDB1 is open READ WRITE
PDB2 is MOUNTED.
ORACLE_HOME is /u01/app/oracle/product/18.1.0/dbhome_1.
You execute these commands before upgrading the database to the current release:
For which databases will fixup scripts be created?
Oracle - 1z0-083 Dumps Q&A
33 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  CDB1, PDB$SEED, PDB1, and PDB2
PDB$SEED, PDB1, and PDB2 only
CDB1 and PDB$SEED only
CDB1, PDB1, and PDB2 only
CDB1, PDB$SEED, and PDB1 only
Answer: E

---

## Question #:64
Which two are true about an Oracle gold image-based installation in Oracle 18c and later releases? (Choose
two.)
It can be used for both Oracle Database and Oracle Grid Infrastructure installation.
It can only install and configure Oracle Database software. The database has to be created separately.
It does not require the setup wizard.
It uses a single RPM that automatically extracts and installs the Oracle Database software.
It can be used to install and upgrade Oracle Database for single-instance and cluster configurations.
Answer: A E

---

## Question #:65
Examine this configuration:
While CDB1 is open, ‘/u02/app/oracle/fast_recover_area/cdb1/CDB1/controlfile02.ctl’ is accidentally deleted.
To recover from this critical failure, you execute these commands:
Oracle - 1z0-083 Dumps Q&A
34 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  
What will be the outcome?
It will create ‘$ORACLE_HOME/dbs/cdb1/CDB1/controlfile02.ctl’
It will create ‘/u01/app/oralce/oradata/CDB1/controlfile/controlfile02.ctl’.
It will re-create ‘/u02/app/oracle/fast_recover_area/cdb1/CDB1/controlfile02.ctl’
It will create ‘/u01/app/oracle/product/12.2.0.1/db_1/dbs/snapcf_cdb1control02.ctl’.
It will fail because there is no autobackup of the controlfiles.
Answer: C

---

## Question #:66
Which four are true about a Recovery Manager (RMAN) duplication without a TARGET connection? (Choose
four.)
The NOREDO clause must be used if the backups of the database being duplicated were taken when the
database was in NOARCHIVELOG mode.
The UNDO TABLESPACE clause is always required when no connection exists to the TARGET
instance.
RMAN “pushes” the backups of the database to be duplicated over the network to the auxiliary instance.
The NOREDO clause can be used if the backups of the database being duplicated were taken when the
database was in ARCHIVELOG mode.
RMAN SBT-based backups of the database to be duplicated can be used by the auxiliary instance.
The UNDO TABLESPACE clause is always required when no connection exists to the recovery catalog
and the TARGET database is closed.
The UNDO TABLESPACE clause is always required when no connection exists to the recovery catalog
Oracle - 1z0-083 Dumps Q&A
35 of 84 Success Guaranteed, 100% ValidG.  
H.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  and the TARGET database is opened.
RMAN disk-based backups of the database to be duplicated can be used by the auxiliary instance.
Answer: A D E H

---

## Question #:67
Which three are true about patchsets? (Choose three.)
They can be applied in a rolling fashion for Clusterware and the databases.
They can introduce new features.
They are installed via OPatch or OPatchAuto.
Installing a patchset is considered an “upgrade”.
They are only released quarterly.
A base release is not needed to install patchsets.
Answer: D E F

---

## Question #:68
Which two are true about RMAN duplexed backup sets? (Choose two.)
A duplexed backup set uses the same number of SBT channels as a non-duplexed backup set for the
same number of files.
A non-duplexed backup set written to disk can be duplexed to disk by backing up the backup set that is
already on disk.
A non-duplexed backup set written to SBT can be duplexed to tape by backing up the backup set that is
already on tape.
A non-duplexed backup set written to disk can be duplexed to tape by backing up the backup set that is
already on disk.
A non-duplexed backup set written to SBT can be duplexed to disk by backing up the backup set that is
already on tape.
A duplexed backup set always uses twice as many SBT channels as a non-duplexed backup set for the
same number of files.
Answer: B D
Oracle - 1z0-083 Dumps Q&A
36 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
G.  
A.  
B.  
C.  
D.  
E.

---

## Question #:69
Which three are true about backup, restore, and recovery operations done without using Recovery Manager
(RMAN)? (Choose three.)
Backing up a database in NOARCHIVELOG mode using O/S utilities requires that the database
instance be started and the dataabse be in the MOUNT state.
Backing up a database in ARCHIVELOG mode using O/S utilities requires that the database instance be
started and the database be in MOUNT state.
An Oracle database can be restored from backup files copied using O/S utilities.
Oracle data file backups, copied using an O/S utility, can be added to the RMAN catalog as IMAGE
COPIES.
Backing up a database in NOARCHIVELOG mode using O/S utilities requires that the database
instance be shut down.
Oracle archive log backups, copied using an O/S utility, can be added to the RMAN catalog as a backup
set.
Backing up a database in ARCHIVELOG mode using O/S utilities requires that the database instance be
started and the database be in OPEN state.
Answer: C D E

---

## Question #:70
In performance management, which two factors might reduce the ability of an application to scale to a large
number of users? (Choose two.)
poorly written SQL
the number of tablespaces containing tables updated by a transaction
poorly trained users who do not commit transactions
the number of data files containing extents belonging to tables updated by a transaction
issuing multiple savepoints during a transaction
Answer: A B
Oracle - 1z0-083 Dumps Q&A
37 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
G.  
A.

---

## Question #:71
Which three are true about RMAN persistent configuration settings, administration, and their effects? (Choose
three.)
A target database’s persistent RMAN configuration settings are always stored in the target’s control file
Backup older than the recovery window retention policy are always deleted automatically if the backup
location has insufficient space.
Backups written to the fast recovery area (FRA) that are oboslete based on the redundancy retention
policy can be deleted automatically to free space.
The RMAN SHOW ALL command displays only settings with nondefault values.
A target database’s persistent RMAN configuration settings are always synchronized automatically with
the RMAN catalog.
The V$RMAN_CONFIGURATION view displays only settings with values that have been modified.
A DBA must specify either a redundancy retention policy or a recovery window retention policy.
Answer: A C F

---

## Question #:72
Examine these queries and their output:
An online RMAN backup of the CDB was taken an hour before Restore Point R1 was created. You want to
recover PDB1 to Restore Point R1.
How do you achieve this?
Oracle - 1z0-083 Dumps Q&A
38 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  Execute FLASHBACK PLUGGABLE DATABASE PDB1 TO RESTORE POINT R1 by using RMAN
while connected to PDB1.
Execute FLASHBACK PLUGGABLE DATABASE PDB1 TO RESTORE POINT R1 by using SQL
while connected to PDB1.
Execute FLASHBACK PLUGGABLE DATABASE PDB1 TO RESTORE POINT R1 by using SQL
while connected to CDB$ROOT.
Execute FLASHBACK PLUGGABLE DATABASE PDB1 TO RESTORE POINT R1 by using RMAN
while connected to CDB$ROOT.
This cannot be done due to the lack of a clean restore point.
Answer: B

---

## Question #:73
Examine this command:
$ rhpctl move database –sourcehome Oracle_home_path –destinationhome Oracle_home_path
For which two purposes can you use this command? (Choose two.)
to switch an existing Oracle Database home to a newer release of Oracle software on the same server
to switch to a read-only Oracle home
to switch back to the previous Oracle home as part of a rollback operation
to switch the Oracle Database home when using a centralized Rapid Home Provisioning server
to switch to a patched Oracle Database home
Answer: C E
Explanation
You can use rhpctl move gihome command with the same syntax to switch from the current Oracle Grid
Infrastructure home to a patched home. The rhpctl command enables you to switch from your current Oracle
Grid Infrastructure or Oracle Database home to patched Oracle home so that you can provision the new Oracle
home as gold image. You can also use the rhpctl command to switch back to the old Oracle home, if you want
to roll back the operation.

---

## Question #:74
Which two are true about Rapid Home Provisioning (RHP), which has been available since Orcale 18c?
(Choose two.)
Oracle - 1z0-083 Dumps Q&A
39 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  It is an Oracle Database service
It cannot be used to upgrade Oracle Database homes.
It can be used to provision applications.
It can be used to patch Grid Infrastructure homes containing Oracle Restart.
It can be used to provision middleware.
Answer: C E

---

## Question #:75
Which two are true about flashback features in Oracle Database 19c and later releases? (Choose two.)
Flashback logs are automatically purged when DB_FLASHBACK_RETENTION_TARGET is set
lower than the time they have already been retained.
Flashback logs are monitored and proactively deleted when beyond the retention period defined in
DB_FLASHBACK_RETENTION_TARGET only after there is space pressure.
Flashback logs are monitored and proactively deleted when beyond the retention period defined in
DB_FLASHBACK_RETENTION_TARGET before there is space pressure.
Flashback logs are monitored for being older than the retention period defined in
DB_FLASHBACK_RETENTION_TARGET and can be deleted by an administrator written event
trigger.
Flashback logs are automatically purged whenever the value of
DB_FLASHBACK_RETENTION_TARGET is changed.
Answer: A C

---

## Question #:76
Which three are true about RMAN archival backups with the RESTORE POINT clause? (Choose three.)
All archive logs are retained after an archival backup is taken, until the next archival backup is taken of
the
same database.
Oracle - 1z0-083 Dumps Q&A
40 of 84 Success Guaranteed, 100% ValidB.  
C.  
D.  
E.  
F.  
G.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  The SPFILE is included in the archival backup.
They are never considered obsolete by RMAN.
Archive logs are retained if they are necessary to allow the database to be recovered to a consistent state
when an archival backup is restored.
The ARCHIVAL attribute for a backup overrides the RMAN retention policy.
They can optionally be written to a fast recovery area (FRA).
Use of a recovery catalog is always required to support the creation and use of archival backups.
Answer: A B F

---

## Question #:77
Which three are true about block media recovery? (Choose three.)
The data file containing the block being recovered remains online.
To use it, Flashback Database must be enabled.
A block being recovered is not accessible.
It can be performed on noncorrupt blocks.
The target database for which one or more blocks are to be recovered must be in the OPEN state.
It cannot repair logical corruption.
Answer: A B E

---

## Question #:78
Which two are true about Oracle instance recovery? (Choose three.)
Recovery begins from the beginning of the CURRENT redo log group.
Recovery begins from the last checkpoint position that was calculated by the Database Writer before
instance failure.
Recovery begins from the start of any ACTIVE redo log group or the start of the CURRENT log group
if no other group is ACTIVE.
Recovery reads redo until the end of the redo thread. SMON rolls back any dead transactions, and then
Oracle - 1z0-083 Dumps Q&A
41 of 84 Success Guaranteed, 100% ValidD.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  the datanase is opened.
Recovery begins from the last checkpoint position that was recorded in the control file by the checkpoint
process (CKPT).
Recovery reads redo until the end of the redo thread, and then opens the database. SMON then rolls
back any dead transactions.
Answer: B E F

---

## Question #:79
Which three are true about the tools for diagnosing Oracle Database failure situations? (Choose three.)
The ADR command-line utility (ADRCI) can package incident information to send to Oracle Support.
The Automatic Diagnostic Repository (ADR) has a separate home directory for each instance of each
Oracle product that is installed and uses it.
Flashback commands help with repairing physical errors.
RMAN can always repair corrupt blocks.
The ADR can store metadata in an Oracle Database repository.
The Data Recovery Advisor uses the ADR.
Answer: B D E

---

## Question #:80
Which three are true about Automatic Workload Repository (AWR) and Automatic Database Diagnostic
Monitor (ADDM) in an Oracle multitenant environment? (Choose three.)
ADDM can run in a nonroot container.
AWR snapshots can be created in CDB$ROOT.
AWR reports can be generated while connected to any container.
All AWR data is stored in the CDB$ROOT SYSAUX tablespace.
AWR snapshots can be created in a PDB.
No AWR data is stored in the CDB$ROOT SYSAUX tablespace.
Oracle - 1z0-083 Dumps Q&A
42 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  Answer: C E F

---

## Question #:81
Which operating system group is NOT needed to perform an Oracle Database installation?
OSASM
OSKMDBA
OSDBA
OSOPER
OSRACDBA
Answer: E

---

## Question #:82
Which two are true about the Automatic Database Diasnostic Monitor (ADDM)? (Choose two.)
It analyzes a period of time corresponding to the 12 hours of activity.
It runs automatically after each AWR snapshot.
A DBA can run it manually.
Results are written to the alert log.
It analyzes a period of time corresponding to the last day of activity.
Answer: B C

---

## Question #:83
Which two are true about Oracle Optimizer Statistics, their use, and their collection? (Choose two.)
The number of table rows is considered when evaluating the cost of accessing a table using an index.
Index balanced B*Tree height is considered when evaluating the cost of using an index.
The Statistics Advisor can help recommend the best way to gather statistics.
Oracle - 1z0-083 Dumps Q&A
43 of 84 Success Guaranteed, 100% ValidD.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  Statistics collected using DBMS_STATS always yield the best optimizer result.
The Statistics Advisor generates actions for all recommendations.
Answer: C D

---

## Question #:84
Which three are true about managing memory components in an Oracle database instance? (Choose three.)
With Automatic Shared Memory Management, the database instance can increase the Large Pool size by
reducing the Shared Pool size.
With Automatic Memory Management, the database instance can increase the System Global Area size
by reducing the Program Global Area size.
Automatically tuned and resized System Global Area components will always revert to their initial sizes
after an instance restart.
Automatic Memory Management must be used together with locking the System Global Area into
physical memory.
With Automatic Shared Memory Management, the database instance can increase the Program Global
Area size by reducing the System Global Area size.
On Line Transaction Processing systems often use less Program Global Area than Decision Support
Systems.
Answer: A B F

---

## Question #:85
A database is configured in ARCHIVELOG mode.
A full RMAN backup exists but no control file backup to trace has been taken. A media failure has occurred.
In which two scenarios is incomplete recovery required? (Choose two.)
after losing a SYSAUX tablespace data file
after losing all members of an INACTIVE online redo log group
after losing all members of the CURRENT online redo log group
after losing all copies of the control file
after losing an UNDO tablespace that is in use
Oracle - 1z0-083 Dumps Q&A
44 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  Answer: C D

---

## Question #:86
Which three are true about Optimizer Statistics Advisor? (Choose three.)
It can be run only manually.
It is part of the DBMS_ADVISOR package.
It can recommend changes to improve the statistics gathering process.
It always analyzes all schemas in the database.
It runs automatically every night by default.
It is part of the DBMS_STATS package.
Answer: C E F
Explanation
https://mikedietrichde.com/2017/08/22/oracle-optimizer-statistics-advisor-in-oracle-database-12-2-0-1/
https://www.oracle.com/technetwork/database/bi-datawarehousing/twp-bp-for-stats-gather-19c-5324205.pdf

---

## Question #:87
Which two are true about changing the LOCAL_UNDO_ENABLED property to false in a CDB? (Choose
two.)
After the change, only a common user with the required privilege can create an undo tablespace in
CDB&ROOT.
Any new PDB and existing PDBs are automatically configured to use the default undo tablespace in
CDB$ROOT.
After the change, only one undo tablespace can exist in CDB$ROOT.
After the change, any user with the required privilege can create an undo tablespace in the PDBs.
Undo tablespaces existing in PDBs must be dropped before the change.
After the change, each existing PDB has to be reopened for the new undo mode to take effect.
Answer: B C
Oracle - 1z0-083 Dumps Q&A
45 of 84 Success Guaranteed, 100% Valid
A.  
B.  
C.  
D.  
E.  Explanation
You can set a CDB in local UNDO mode either at CDB creation or by altering the CDB property. When the
database property LOCAL_UNDO_ENABLE is FALSE, which is the default, there is only one UNDO
tablespace that is created in the CDB root, and that is shared by all containers. When
LOCAL_UNDO_ENABLE is TRUE, every container in the CDB uses local undo and each PDB must have its
own local UNDO tablespace. To maintain ease of management and provisioning, UNDO tablespace creation
happens automatically and does not require any action from the user. When a PDB is opened and an UNDO
tablespace is not available, its automatically created.

---

## Question #:88
Examine this configuration:
CDB1 is a container database.
PDB1 and PDB2 are pluggable databases in CDB1.
You execute these commands successfully:
Which two are true? (Choose two.)
PDB1 and PDB2 are in MOUNT state.
Redo logs are opened.
PDB1 and PDB2 are in READ ONLY state.
CDB$ROOT is in MOUNT state.
PDB$SEED is in READ ONLY state.
Answer: B E
Oracle - 1z0-083 Dumps Q&A
46 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.

---

## Question #:89
Which two are true about SQL Performance Analyzer (SPA)? (Choose two.)
It is integrated with the SQL Access Advisor.
It predicts the impact of system changes on SQL workload response time.
It provides before and after execution statistics for each SQL statement in the analysis task
It offers fine-grained analysis of all the SQL statements in the analysis task as a group.
SQL statements that were originally run concurrently are run concurrently by SPA.
Answer: B D

---

## Question #:90
Examine the command for creating pluggable database PDB2 in container database CDB2.
Select three options, any one of which is required for it to execute successfully. (Choose three.)
Add the FILE_NAME_CONVERT clause to the statement and set the PDB_FILE_NAME_CONVERT
parameter.
Add only the CREATE_FILE_DEST clause to the statement.
Set only the PDB_FILE_NAME_CONVERT parameter.
Set the PDB_FILE_NAME_CONVERT parameter and enable OMF.
Enable only OMF.
Add the FILE_NAME_CONVERT clause to the statement and enable Oracle Managed Files (OMF)
Answer: B D E

---

## Question #:91
Application PDBs, SALES_APP1 and SALES_APP2, must be created and they must access common tables of
Oracle - 1z0-083 Dumps Q&A
47 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  the SALES_APP application.
Examine these steps:
1. Install the SALES_APP application, including the common tables, in the application root.
2. Install the SALES_APP application in the application root and the common tables in both the CDB root and
the application root.
3. Create an application seed.
4. Install the SALES_APP application in the application seed.
5. Create the SALES_APP1 and SALES_APP2 application PDBs.
6. Sync the SALES_APP1 and SALES_APP2 application PDBs with the application root.
7. Sync the SALES_APP1 and SALES_APP2 application PDBs with the application seed.
8. Sync the application seed with the application root.
Which are the minimum required steps in the correct sequence?
3, 4, 1, 6, 8
2, 5, 6
1, 5, 6
1, 3, 5, 6, 7
1, 3, 5, 7
Answer: C

---

## Question #:92
Which two are true about RMAN Multisection backups when a very large data file is divided into four
sections?
(Choose two.)
Each of the file sections must be processed serially.
The four sections can be created serially.
The four sections must be image copies.
Oracle - 1z0-083 Dumps Q&A
48 of 84 Success Guaranteed, 100% ValidD.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  The four sections can be created in parallel.
The four sections must be contained in backup sets.
Answer: D E

---

## Question #:93
Which two are true about Recovery Manager (RMAN) diagnostic message output? (Choose two.)
Media Management messages for SBT devices are always written to sbtio.log.
RMAN error stacks should be read from the bottom up as that is the order in which errors are generated.
RMAN error stacks should be read from the top down as that is the order in which errors are generated.
The RMAN LOG command line clause causes output issued during RMAN command compilation to be
written to a log file and to standard output.
The RMAN LOG command line clause causes output issued during RMAN command compilation to be
written to a log file only.
Media Management messages for SBT devices are written to an Oracle trace file.
Answer: B E

---

## Question #:94
Which three are true about an application container?
It must have an application root PDB.
It can contain multiple applications.
An application PDB can belong to multiple application containers.
Two application containers can share an application seed PDB.
It can contain a single application.
It must have an application seed PDB.
Answer: B D E

---

## Question #:95
Oracle - 1z0-083 Dumps Q&A
49 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  Which two are true about poorly performing SQL statements and their tuning in Oracle database instances?
(Choose two.)
SQL statements performing many physical I/Os can always have their performance improved by
creating
indexes.
SQL statements doing only logical reads never require tuning because they do no physical I/O.
The solution that best optimizes one SQL statement can degrade the performance of others.
SQL statements doing joins always do more physical I/O than single table queries.
Poorly performing SQL statements can be tuned automatically by the Oracle server.
Answer: B E

---

## Question #:96
Automatic Shared Memory Management is disabled for one of your database instances.
Some SQL statements perform poorly due to excessive hard parse activity, thereby degrading performance.
What would be your next step?
Run the SQL Access Advisor.
Run the Memory Advisor for the shared pool.
Run the SQL Tunning Advisor.
Run the Memory Advisor for the Program Global Area.
Run the Memory Advisor for the System Global Area.
Answer: B

---

## Question #:97
Which three are true about monitoring waits for sessions and services? (Choose three.)
V$SESSION_EVENT displays all waits for all past and existing sessions if the wait has occurred at
least once for a session.
V$SERVICE_EVENT displays all waits for all services if the wait has occurred at least once for a
service.
Oracle - 1z0-083 Dumps Q&A
50 of 84 Success Guaranteed, 100% ValidC.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  V$SESSION_WAIT_CLASS displays waits broken down by wait class only for waiting sessions.
V$SESSION_WAIT and V$SESSION both contain details of the event on which a non-waiting session
last waited.
V$SESSION_EVENT displays all waits for all past sessions if the wait has occurred at least once for a
session.
V$SESSION_WAIT and V$SESSION both contain details of the event on which a session is currently
waiting.
Answer: B C F

---

## Question #:98
Which two are true about the automatic execution of operating system scripts when performing silent mode
installation starting from Oracle Database 19c? (Choose two.)
The response file can specify the root or sudo password.
The installer will prompt for the root or sudo password.
Silent install always runs operating scripts automatically.
The response file must contain the root or sudo password.
The response file can specify the path of the sudo program.
Answer: D E

---

## Question #:99
Which two are true about common objects? (Choose two.)
They can be created only in CDB$ROOT.
They can be only metadata-linked in an application container.
They can exist in user-defined schemas only in application containers.
They can exist in CDB$ROOT and an application root.
They can be extended data-linked in CDB$ROOT.
They can be created only in an application root.
Oracle - 1z0-083 Dumps Q&A
51 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  Answer: D F

---

## Question #:100
Which three are true in Oracle 19c and later releases? (Choose three.)
Tablespaces never remain in read/write mode during transportable tablespace operations.
A transportable data pump import can leave a plugged-in tablespace in read-only mode.
A transportable data pump import can leave a plugged-in tablespace in read/write mode.
Simultaneous data pump jobs can be limited at the pluggable database (PDB) level.
Tablespaces always remain in read/write mode during transportable tablespace operations.
An ordinary data pump export of a table with encrypted columns will always encrypt the same columns
when imported.
Answer: C E F

---

## Question #:101
Which three methods can be used for heap table data migration after upgrading a database? (Choose three.)
using Database Replay
using SQL Developer
using Oracle Data Pump
using operating system file copy utilities
using Database Upgrade Assistant
using the CREATE TABLE AS SELECT SQL statement
Answer: B C F
Explanation
https://www.oracle.com/a/tech/docs/twp-upgrade-oracle-database-19c.pdf

---

## Question #:102
Oracle - 1z0-083 Dumps Q&A
52 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  Which two are true about the Oracle dataabse methodology? (Choose two.)
The Oracle Database time model should be used to find the database and instance areas most in need of
tuning.
Tuning activities should stop once the user is satisfied with performance.
Tuning activities should stop once agreed service levels for performance have been met.
The database instance memory should always be tuned before tuning any file systems.
SQL statements should always be tuned before tuning any file systems.
The alert log should be used to find the database and instance areas most in need of tuning.
Answer: A E

---

## Question #:103
Which three are true about requirements for various FLASHBACK operations? (Choose three.)
FLASHBACK transaction query requires undo to retrieve all versions of a row that existed between two
points in time.
FLASHBACK drop requires that the RECYCLEBIN parameter be set to ON.
FLASHBACK version query requires that the RECYCLEBIN parameter be set to ON.
FLASHBACK DATA ARCHIVE requires undo to store all versions of all rows of a table being tracked.
FLASHBACK drop requires undo to retrieve all versions of a row that existed between two points in
time.
FLASHBACK version query requires undo to retrieve all versions of a row that existed between two
points in time.
Answer: A B F

---

## Question #:104
Which two are true about the execution of operating system scripts starting from Oracle Database 19c?
(Choose two.)
orainstRoot.sh can be executed automatically by the Database installer by using sudo or root
credentials.
Oracle - 1z0-083 Dumps Q&A
53 of 84 Success Guaranteed, 100% ValidB.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  root.sh can be executed automatically by the Database Installer only if it is provided with root
credentials.
The sudo password can be specified in a response file.
root.sh can be executed automatically by the Database installer only by using sudo credentials.
The sudo password must be specified in a response file.
The root password cannot be specified in a response file.
Answer: A F

---

## Question #:105
Which three are true about Oracle Grid Infrastructure for a Standalone Server?
It includes both Oracle Restart and Oracle Automatic Storage Management (ASM) software.
It creates one disk group during installation.
It requires the operating system oracle_base environment variable to be predefined before installation.
It requires Oracle ASM Filter Driver (ASMFD) to manage Automatic Storage Management (ASM)
disks
It requires Oracle ASMLibto manage Automatic Storage Management (ASM) disks.
Automatic Storage Management (ASM) requires that O/S groups OSASM and OSDBA be assigned as
secondary groups for its installation owner.
Answer: A B D

---

## Question #:106
Which three capabilities require the use of the RMAN recovery catalog? (Choose three.)
using the KEEP FOREVER clause with the BACKUP command
using RMAN stored scripts
using the REPORT SCHEMA command to list a database’s current data files and tablespaces
creating customized reports about a single database’s backups
creating encrypted backups
Oracle - 1z0-083 Dumps Q&A
54 of 84 Success Guaranteed, 100% ValidF.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  using the REPORT SCHEMA command to list a database’s data files and tablespaces at times in the
past
Answer: A B C

---

## Question #:107
Which two are true about RMAN backups when using a media manager to write backups to tape when there
are only two tape drives? (Choose two.)
SBT tape compression can be used even if no RMAN compression is configured.
Any backup set written to the SBT device in this configuration can contain a maximum of two backup
pieces.
Any backup written to the SBT device in this configuration can contain a maximum of two backup sets.
SBT tape compression and RMAN backup compression should be used in parallel.
The SBT device should be configured to use PARALLELISM 2 to allow both tape drive to be used
simultaneously.
Answer: D E

---

## Question #:108
While backing up to the Oracle Fast Recovery Area (FRA), you determined the backup is taking too long and
suspect a performance bottleneck.
Which three are true about diagnosing and tuning these problems? (Choose three.)
If an RMAN BACKUP VALIDATE command takes roughly the same time as an actual backup, then
both read and write I/O are likely bottlenecks.
Setting DBWR_IO_SLAVES to a non zero value can improve backup performance when using
synchronous I/O.
If an RMAN BACKUP VALIDATE command takes noticeably less than an actual backup, then write
I/O is a likely bottleneck.
If an RMAN BACKUP VALIDATE command takes roughly the same time as an actual backup, then
read I/O is a likely bottleneck.
Data files with a high value in V$BACKUP_SYNC_IO.DISCRETE_BYTES_PER_SECOND are a
potential performance bottleneck when synchronous I/O is used.
Oracle - 1z0-083 Dumps Q&A
55 of 84 Success Guaranteed, 100% ValidF.  
G.  
A.  
B.  
C.  
D.  
E.  
F.  
Setting DBWR_IO_SLAVES to a non zero value can improve backup performance when using
asynchronous I/O/
Data files with a high value in V$BACKUP_ASYNC_IO.SHORT_WAITS are a potential performance
bottleneck when asynchronous I/O is used.
Answer: B C E

---

## Question #:109
Your container database, CDB1, is in local undo mode.
You successfully execute this command while connected to CDB1:
CREATE PLUGGABLE DATABASE pdb1
ADMIN USER pdb1_admin IDENTIFIED BY pdb123 ROLES=(CONNECT)
CREATE_FILE_DEST='/u01/app/oracle/oradata/cdb1/pdb1';
Which three are true about PDB1? (Choose three.)
Service PDB1 is created for remote logins to PDB1.
It is in mount state after creation.
It has no local users.
It has the same number of roles as CDB1.
It has the same common users defined as does CDB1.
It has only local roles.
Answer: C D E

---

## Question #:110
You are managing this configuration:
CDB1 is a container database.
PDB1 and PDB2 are two pluggable databases in CDB1.
USER1.EMP is a table in PDB1 and USER2.DEPT is a table in PDB2.
CDB1 user SYS executes these commands after connecting successfully to PDB2:
Oracle - 1z0-083 Dumps Q&A
56 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
G.  
A.  
B.  
C.  
D.  
Which two are true? (Choose two.)
The inserts on USER1.EMP remain uncommitted when the session connected to PDB2.
The inserts on USER1.EMP were committed when the session inserted a row into USER2.DEPT.
The insert on USER2.DEPT fails because of the active transaction in the parent container.
The insert on USER2.DEPT is a recursive autonomous transaction by the child session and is
committed.
The inserts on USER1.EMP were rolled back when the session connected to PDB2.
The insert on USER2.DEPT is uncommitted.
The inserts on USER1.EMP were committed when the session connected to PDB2.
Answer: F G

---

## Question #:111
Which two are true about memory advisors? (Choose two.)
If Automatic Shared Memory Management is enabled, both the SGA Advisor and PGA Advisor are
always
available.
If Automatic Memory Management is enabled, no memory advisors are available.
All memory advisors use data from Automatic Workload Repository.
Oracle - 1z0-083 Dumps Q&A
57 of 84 Success Guaranteed, 100% ValidD.  
E.  
A.  
B.  
C.  
D.  
E.  If Manual Shared Memory Management is enabled, only the Shared Pool Advisor and Buffer Cache
Advisor are available.
If Automatic Memory Management is enabled, the Shared Pool Advisor and Buffer Cache Advisor are
available to set the maximum size for these individual System Global Area components.
Answer: A B

---

## Question #:112
A container database called CDB1 is OMF-enabled.
PDB_FILE_NAME_CONVERT is not configured in CDB1. PDB1 was unplugged from CDB1 earlier in the
week. Examine this command, which will be executed in CDB1:
CREATE PLUGGABLE DATABASE pdb1
USING ‘/u01/app/oracle/oradata/pdb1.xml’
SOURCE_FILE_NAME_CONVERT =
(‘/u01/app/oracle/oradata/’, ‘/u02/app/oracle/oradata/’);
Which two are true? (Choose two.)
PDB1 data files already exist in the correct location.
DBMS_PDB.CHECK_PLUG_COMPATIBILITY must be run in CDB1 before executing the command.
PDB_FILE_NAME_CONVERT must be set before executing the command.
/u01/app/oracle/oradata/pdb1.xml does not contain the current locations of data files for PDB1.
PDB1 must be dropped from CDB1.
Answer: A E

---

## Question #:113
Examine these actions:
1.Create a new database for a recovery catalog.
2.Create a tablespace with sufficient space in the catalog database for the recovery catalog.
Oracle - 1z0-083 Dumps Q&A
58 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
A.  3.Configure ARCHIVELOG mode for the catalog database.
4.Create a user to own the recovery catalog schema with quota on the tablespace that will contain the
catalog.
5.Grant the RECOVERY_CATALOG_OWNER role to the recovery catalog schema owner.
6.Grant the SYSBACKUP privilege to the recovery catalog schema owner.
Which are the minimum actions that must be performed before executing the CREATE CATALOG
command?
2, 4, 5, 6
1, 2, 3, 4, 5, 6
1, 2, 4, 5
2, 4, 5
1, 3, 4, 5
Answer: D

---

## Question #:114
Which two are true about Oracle Database Configuration Assistant (DBCA) templates? (Choose two.)
The General Purpose of Transaction Processing templates are most suitable when concurrency and
recoverability are key criteria.
Oracle DBCA templates can store only logical structure and not database files.
New templates can only be created by modifying an existing user-created template.
The Data Warehouse template is most suitable when transaction response time is the key criterion.
Oracle DBCA templates can be used to create new databases and duplicate existing databases.
Answer: A E

---

## Question #:115
Which three are true about the Oracle Optimizer? (Choose three.)
It obeys all hints.
Oracle - 1z0-083 Dumps Q&A
59 of 84 Success Guaranteed, 100% ValidB.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  It considers the filters in WHERE clauses when generating execution plans for SQL statements.
It can re-optimize execution plans after previous executions detect suboptimal plans.
It considers object statistics when generating execution plans for SQL statements.
It updates stale object statistics in the Data Dictionary.
It can only use SQL Plan Directives tied to the SQL statement for which a plan is being generated.
Answer: D E F

---

## Question #:116
Which three are true about using Database Resource Manager in an Oracle multitenant environment?
(Choose three.)
A PDB-level resource plan can limit session PGA memory.
A CDB-level resource plan can limit PDB CPU utilization.
A CDB-level resource plan can limit session CPU utilization.
PDB-level resource plans can limit uncommitted UNDO per consumer group.
A CDB-level resource plan can limit PDB UNDO use.
A CDB-level resource plan is mandatory when using PDB-level resource plans.
Answer: C E F

---

## Question #:117
Which three are true about Recovery Manager (RMAN) in Oracle Database 19c and later releases? (Choose
three.)
It is only possible for RMAN to connect to a pluggable database as a target if an RMAN Virtual Private
Catalog is used.
It is always possible for RMAN to connect to a pluggable database as a target if any RMAN Catalog is
used.
A Virtual Private Catalog used to register a container database must be created in a pluggable database.
A Virtual Private Catalog used to register a container database can be created in a pluggable database.
Oracle - 1z0-083 Dumps Q&A
60 of 84 Success Guaranteed, 100% ValidE.  
F.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  It is always possible for RMAN to connect to a pluggable database as a target.
A Virtual Private Catalog used to register a container database can be created in a non-container
database.
Answer: D E F

---

## Question #:118
Examine this configuration:
1. CDB1 is a container database.
2. APP_ROOT is an application root in CDB1.
3. APP_PDB1 is an application PDB in APP_ROOT.
4. FLASHBACK DATABASE is ON.
You execute these commands:
Which table or set of tables will exist after the Flashback operation has completed?
CDB1_TAB, APP_ROOT_TAB, and APP_PDB1_TAB
CDB1_TAB and APP_PDB1_TAB
none of the tables, because all three tables will be dropped
CDB1_TAB only
CDB1_TAB and APP_ROOT_TAB
Answer: A

---

## Question #:119
Which four are true about RMAN backup sets? (Choose four.)
A backup piece can belong to only one backup set.
A data file can be split into multiple sections stored in different backup sets.
A data file can be split into multiple sections stored in different backup pieces in the same backup set.
Blocks from multiple data files can be contained in one backup piece,
Oracle - 1z0-083 Dumps Q&A
61 of 84 Success Guaranteed, 100% ValidE.  
F.  
G.  
H.  
A.  
B.  
C.  
D.  
E.  A backup set can contain only one backup piece.
A backup set must be written to media.
A backup set must be written to disk.
Blocks from multiple data files can be contained in one backup set,
Answer: B E F H

---

## Question #:120
Which two are true about Oracle Flashback features? (Choose two.)
FLASHBACK QUERY can retrieve REDO records from ONLINE and ARCHIVED REDO LOG files.
FLASHBACK VERSION QUERY can retrieve REDO records from ONLINE and ARCHIVED REDO
LOG files.
FLASHBACK TABLE can undrop a column.
FLASHBACK DROP can undrop an index when undropping a table.
After a database is restored from flashback logs using the FLASHBACK DATABASE command, it is
sometimes rolled forward using redo logs.
Answer: D E

---

## Question #:121
Examine this configuration:
1. CDB1 and CDB2 are two container databases.
2. PDB1 is a pluggable database in CDB1.
3. PDB1_C1_SRV is a service for PDB1.
4. CDB1_LINK is a database link in CDB2 referring to PDB1.
5. CDB2 is also an entry in tnsnames.ora pointing to the CDB2 database default service.
You execute these commands successfully:
$ sqlplus sys/oracle_4U@cdb2 as sysdba
SQL> CREATE PLUGGABLE DATABASE PDB1
Oracle - 1z0-083 Dumps Q&A
62 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
A.  FROM PDB1@CDB1_LINK
SERVICE_NAME_CONVERT=('PDB1_C1_SRV','PDB1_C2_SRV');
Which two are true? (Choose two.)
PDB1 will be created in CDB2 and automatically opened.
PDB1 will be created in CDB2 and left in MOUNT state.
PDB1_C1_SRV in CDB1 will be renamed PDB1_C2_SRV.
PDB1_C2_SRV will be created and started automatically.
PDB1_C2_SRV will be created but not started.
Answer: A C

---

## Question #:122
RMAN has just been connected to a target database and the recovery catalog database.
In which two cases would an automatic full resynchronization occur between this target database’s control file
and the RMAN recovery catalog? (Choose two.)
when control file metadata for archive log backups or image copies has been overwritten in the target
database’s control file due to being older than CONTROL_FILE_RECORD_KEEP_TIME
when control file metadata for data file backups or image copies has been overwritten in the target
database’s control file due to being older than CONTROL_FILE_RECORD_KEEP_TIME
when a new tablespace is added to a registered target database
when a backup of the current control file is created
when the target is first registered
Answer: B D

---

## Question #:123
How do you configure a CDB for local undo mode?
Oracle - 1z0-083 Dumps Q&A
63 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  Open the CDB instance in upgrade mode. In cdb$root, execute alter database local undo on, and then
restart the CDB instance.
Open the CDB in read-only mode. In cdb$root, execute alter database local undo on, and then change
the CDB to read/write mode.
Open the CDB instance in restricted mode. In cdb$root, execute alter database local undo on. create an
undo tablespace in each PDB, and then restart the CDB instance
Open the CDB instance in restricted mode. In cdb$root, drop the undo tablespace. Execute alter
database local undo on in each PDB, and then restart the CDB instance.
Open the CDB instance in upgrade mode. In each PDB, execute alter database local undo on, create an
undo tablespace, and then restart the CDB instance.
Answer: D

---

## Question #:124
Examine this configuration:
1. CDB1 is a container database.
2. COMMON_USER_PREFIX is set to an empty string.
3. PDB1 is a pluggable database in CDB1.
4. APP1_ROOT is an application container in CDB1.
5. APP1_PDB1 is an application PDB in APP1_ROOT.
You execute these commands:
$ sqlplus sys/oracle@localhost:1521/cdb1 as sysdba
SQL> CREATE ROLE role1 CONTAINER=CURRENT;
What is true?
It will return an error because creation of a local role is not allowed in CDB$ROOT.
ROLE1 will be created only in CDB$ROOT and APP1_ROOT.
ROLE1 will be created in CDB$ROOT, PDB1, APP1_ROOT, and APP1_PDB1.
ROLE1 will be created only in CDB$ROOT.
It will return an error because common roles must start with C##.
Answer: D
Oracle - 1z0-083 Dumps Q&A
64 of 84 Success Guaranteed, 100% Valid
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.

---

## Question #:125
Examine this configuration:
CDB1 is a container database.
PDB1 and PDB2 are pluggable databases in CDB1.
PDB1 and PDB2 are OPEN in READ WRITE mode.
You execute these commands successfully:
Which two are true? (Choose two.)
Uncommitted transactions in PDB1 have been rolled back.
PDB1 is closed.
Uncommitted transactions in CDB1 and PDB1 have been rolled back.
CDB1 is shut down.
CDB1 is in MOUNT state
Answer: A B

---

## Question #:126
Which three are true about Rapid Home Provisioning of Oracle software? (Choose three.)
It can be used only on nodes with Oracle Grid Infrastructure installed.
It can be used to patch existing Oracle software installations.
It can be used to create templates of Oracle homes as gold images of only Oracle databases.
It can be used to deploy new homes without disrupting active databases.
Oracle - 1z0-083 Dumps Q&A
65 of 84 Success Guaranteed, 100% ValidE.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  It can be used to create a single-instance Oracle Database in an already-installed Oracle home.
It can be used to upgrade only single-instance databases running on Oracle Restart.
Answer: A B C

---

## Question #:127
Which three are true in Oracle 19c and later releases? (Choose three.)
If the password file location changes, then the new location is used automatically by the Oracle Server.
Schema Only accounts can be granted administrator privileges.
All the Oracle-supplied accounts are Schema Only accounts.
Privilege Analysis is included in Oracle Enterprise Edition and no longer requires Database Vault.
Unified Auditing can be configured to audit only events that are issued indirectly by an audited user.
Unified Auditing can be configured to audit only events that are issued directly by an audited user.
Answer: B C D

---

## Question #:128
Which three are performed by Oracle Automatic Storage Management (ASM) instances? (Choose three.)
mounting disk groups
managing Allocation Units (AUs) for disk group content
managing extent allocation for Oracle database segments
acting as an I/O server to write data file blocks to ASM disks on behalf of Database Writer processes
(DBWn)
managing space allocation for Oracle ASM files
acting as an I/O server to read data file blocks from ASM disks on behalf of database server processes
Answer: A B E
Oracle - 1z0-083 Dumps Q&A
66 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.

---

## Question #:129
Which three actions are performed by the Oracle Preinstallation RPM, oracle-database-server-xxxx- preinstall,
for Oracle Grid Infrastructure, where xxxx is the Oracle version and release? (Choose three.)
performing checks to ensure minimum configuration requirements for Oracle Grid Infrastructure are met
creating the oracle OS user
creating the OSDBA (dba) group
creating thte oraInventory (oinstall) group
creating the grid OS user
configuring the OS for Oracle Automatic Storage Management shared storage access
Answer: B C D

---

## Question #:130
Which three are true about recovery operations done without using Recovery Manager (RMAN)? (Choose
three.)
A lost SPFILE can be recovered from memory using SQL*PLUS.
A lost password file can be re-created with SQL*PLUS.
A lost TEMPFILE must always be re-created manually.
A lost password file can be manually re-created with the orapwd utility.
A lost PFILE can be re-created alert.log using SQL*PLUS.
A lost index tablespace can be re-created without performing any recovery.
Answer: B D E

---

## Question #:131
Which two are true about backup set compression using RMAN default compression? (Choose two.)
Compressed backups can be written only to media.
Binary compression adds CPU overhead to backup operations.
Oracle - 1z0-083 Dumps Q&A
67 of 84 Success Guaranteed, 100% ValidC.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  
G.  
A.  
B.  
C.  
D.  
E.  Unused blocks below the high water mark are backed up.
Compressed backups cannot have a section size defined.
Compression can be done only for locally managed tablespaces.
Answer: B C

---

## Question #:132
Which three can be done using Oracle Database Configuration Assistant (DBCA) starting from Oracle
Database 19c? (Choose three.)
cloning a remote container database in interactive mode
cloning a remote pluggable database in silent mode
relocating a remote pluggable database in interactive mode
relocating a remote container database in silent mode
cloning a remote container database in silent mode
relocating a remote pluggable database in silent mode
relocating a remote container database in interactive mode
Answer: B E F

---

## Question #:133
Which two are true about duplicating pluggable databases (PDBs) with RMAN? (Choose two.)
Two or more PDBs can be duplicated with the same RMAN DUPLICATE command.
All tablespaces belonging to a PDB must be duplicated when duplicating the PDB.
The auxiliary instance is automatically created with ENABLE_PLUGGABLE_DATABASE = TRUE.
A user with SYSDBA or SYSBACKUP must be logged in with RMAN to the PDB to duplicate it.
CDB$ROOT and PDB$SEED are automatically duplicated.
Answer: A E
Oracle - 1z0-083 Dumps Q&A
68 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.

---

## Question #:134
Which three are true about interpreting Recovery Manager (RMAN) error stacks returned to standard output?
(Choose three.)
Some messages in the error stack are not errors.
If an RMAN command fails, the output will only identify the command that failed.
If an RMAN command fails, the output will identify the channel ID where the failure occurred.
Media Management errors appear as a line with “sbtio” and a number.
Media Management errors appear as a line with “sbtio”.
Media Management errors appear as a line with “Additional information” and a number.
Answer: C E F

---

## Question #:135
Which three are true In Oracle 19c and later releases?
Tablespaces always remain In read/write mode during transportable tablespace operations.
Simultaneous data pump jobs can be limited at the pluggable database (PDB) level.
Tablespaces never remain In read/write mode during transportable tablespace operations.
An ordinary data pump export of a table with encrypted columns will always encrypt the same columns
when imported.
A transportable data pump import can leave a plugged-in tablespace in read-only mode.
A transportable data pump import can leave a plugged-in tablespace In read/write mode.
Answer: A D E

---

## Question #:136
Examine this configuration:
1.The ORCL database data files are in Automatic Storage Management (Oracle ASM) disk group +DATA.
2.ORCL uses disk group +FRA for the Fast Recovery Area.
Oracle - 1z0-083 Dumps Q&A
69 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  3.LISTENER is the listener for ORCL.
4.The database, listener, ASM instance, and ASM disk groups are managed by Oracle Restart.
5.All components are currently shut down.
You execute this command:
What is the outcome?
The ORCL database, the Oracle ASM instances, the +DATA and +FRA disk groups, and the
LISTENER
are started.
Only the ORCL database instance is started.
Only the ORCL database and the ASM instances are started.
Only the ORCL database instance, the Oracle ASM instance, and the +DATA and +FRA disk groups
are started.
Only the ORCL database instance and the +DATA and +FRA disk groups are started.
Answer: A
Explanation
https://docs.oracle.com/html/E25494_01/start001.htm

---

## Question #:137
You issued this command:
RMAN> BACKUP RECOVERY FILES;
Which two are true? (Choose two.)
All Oracle recovery files not in the current FRA that have not been backed up already, are backed up.
All non-Oracle files in the current FRA that have not been backed up already, are backed up.
All Oracle recovery files in the current FRA that have not been backed up already, are backed up.
All Oracle recovery files in the current fast recovery area (FRA) are backed up.
These backups can be written to disk or SBT.
Oracle - 1z0-083 Dumps Q&A
70 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  Answer: D E
Explanation
https://blog.toadworld.com/rman_-_using_the_flash_recovery_area

---

## Question #:138
HR_ROOT is an application container with the HR_APP application installed.
No application PDBs and no application seed have yet been created in HR_ROOT.
An application PDB, PDB1, must be created so that the HR_APP application’s common objects are accessible
to it.
Which two methods can be used? (Choose two.)
Create an application seed, and install HR_APP in it.
Create the PDB1 application PDB and install HR_APP in it.
Create an application seed, synchronize it with HR_ROOT, and then create the PDB1 application PDB.
Create the PBD1 application PDB and synchronize it with HR_ROOT.
Create the PBD1 application PDB and synchronize it with PDB$SEED.
Answer: A C

---

## Question #:139
Which three are true? (Choose three.)
Virtual Private Database (VPD) policies on objects in an application root are automatically synchronized
with all application PDBs contained in the application container.
Application-common TSDP policies are always container specific.
Application-common Transparent Security Data Protection (TSDP) policies can be created only within
an application install/patch BEGIN-END block.
Application-common Oracle Label Security (OLS) policies cannot be created in an application root
outside an install/patch BEGIN-END block.
Fine-grained auditing (FGA) policies in an application root are automatically synchronized to all
application PDBs contained in the application container.
Oracle - 1z0-083 Dumps Q&A
71 of 84 Success Guaranteed, 100% ValidF.  
G.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  Application-common OLS policies can be created in an application root inside an install/patch
BEGIN-END
block.
Unified auditing can be automatically synchronized to all application PDBs in an application container.
Answer: B D G

---

## Question #:140
Your database is in ARCHIVELOG mode and you plan to use Flashback Database.
Which two features or parameters manage space availability in the fast recovery area? (Choose two.)
the archived log deletion policy
the backup optimization policy
the backup retention policy
using guaranteed UNDO retention
the DB_CREATE_ONLINE_LOG_DEST_n parameter setting
the DB_RECOVERY_FILE_DEST parameter setting
Answer: C E

---

## Question #:141
Your CDB has two regular PDBs as well as one application container with two application PDBs and an
application seed
No changes have been made to the standard PDB$SEED.
How many default temporary tablespaces can be assigned in the CDB?
three
eight
seven
six
five
Oracle - 1z0-083 Dumps Q&A
72 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  Answer: C

---

## Question #:142
Examine this configuration:
1. CDB1 is a container database running in ARCHIVELOG mode.
2. Multiple uncommitted transactions are running in CDB1.
3. Redo log groups 1 and 2 are INACTIVE.
4. Redo log group 3 is the CURRENT group.
All members of redo log group 3 are lost before it is archived.
Examine these possible steps:
1. SHUTDOWN ABORT
2. STARTUP NOMOUNT
3. STARTUP MOUNT
4. ALTER DATABASE MOUNT
5. RESTORE DATABSE
6. RECOVER DATABASE NOREDO
7. RECOVER DATABASE UNTIL AVAILABLE
8. RESTORE ARCHIVELOG ALL
9. ALTER DATABSE OPEN
10.ALTER DATABASE OPEB RESETLOGS
Choose the minimum required steps in the correct order to recover the database.
1, 3, 5, 8, 6, 10
1, 3, 5, 6, 10
1, 3, 5, 7, 10
1, 2, 5, 7, 4, 10
Oracle - 1z0-083 Dumps Q&A
73 of 84 Success Guaranteed, 100% ValidE.  
A.  
B.  
C.  
D.  
E.  1, 3, 5, 6, 9
Answer: B

---

## Question #:143
Examine this configuration:
1. CDB1 is a container database running in archivelog mode.
2. Multiple uncommitted transactions are running in CDB1.
3. Redo log groups 1 and 2 are inactive.
4. Redo log group 3 is the current group.
All members of redo log group 3 are lost before it is archived. Examine these possible steps:
1. SHUTDOWN ABORT
2. STARTUP NOMOUNT
3. STARTUP MOUNT
4. ALTER DATABASE MOUNT
5. RESTORE DATABASE
6. RECOVER DATABASE NOREDO
7. RECOVER DATABASE UNTIL AVAILABLE
8. RESTORE ARCHIVELOG ALL
9. ALTER DATABASE OPEN
10. ALTER DATABASE OPEN RESETLOGS
Choose the minimum required steps in the correct order to recover the database.
1, 3, 5, 6, 10
1, 3, 5, 8, 6, 10
1, 3, 5, 6, 9
1, 3, 5, 6, 10
1, 2, 5, 7, 4, 10
Oracle - 1z0-083 Dumps Q&A
74 of 84 Success Guaranteed, 100% ValidF.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  1, 3, 5, 7, 10
Answer: D

---

## Question #:144
Oracle Managed Files (OMF) is enabled in a CDB and this command is successfully executed:
Which three are true? (Choose three.)
Application PDBs that are subsequently created in the APP1 application container will be cloned from
APP1$SEED.
An application seed PDB is created for APP1.
An application root PDB is created for APP1.
A default service is created for the application root APP1.
Application PDBs that are subsequently created in the APP1 application container will be cloned from
PDB$SEED.
APP1 can never be unplugged.
Answer: A B E

---

## Question #:145
Which two are true about unplugging an application container from a container database and plugging it into a
different container database?
It requires local undo mode in both container databases.
It requires only local undo mode in the database where the application container will be unplugged.
Plugging the application root into a different CDB plugs In all its application PDBs.
Application PDBs In the application container must be unplugged before the application root Is
unplugged.
Unplugging the application root from a CDB unplugs all its application PDBs.
Oracle - 1z0-083 Dumps Q&A
75 of 84 Success Guaranteed, 100% ValidF.  
A.  
B.  
C.  
D.  
E.  
F.  
The application root of an application container should be plugged Into the other CDB before Its
application PDBs are plugged in.
Answer: D E

---

## Question #:146
Which two are true about the character sets used in an Oracle database? (Choose two.)
Single-byte character sets provide better performance than multibyte character sets.
Unicode enables information from any language to be stored using a single character set.
Unicode is the only supported character set for Oracle databases created using Database Configuration
Assistant (DBCA).
Single-byte character sets always use 7-bit encoding schemes.
Multibyte character sets allow more efficient space utilization than single byte character sets.
Single-byte character sets always use 8-bit encoding schemes.
Answer: A B

---

## Question #:147
Examine this configuration:
CDB1 is a container database.
COMMON_USER_PREFIX is C##.
PDB1 is a pluggable database contained in CDB1.
APP1_ROOT is an application container contained in CDB1.
APP1_PDB1 is an application PDB contained in APP1_ROOT.
You execute these commands successfully:
Oracle - 1z0-083 Dumps Q&A
76 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
Which two are true? (Choose two.)
APP1_USER1 can be created in PDB1.
APP1_USER1 can be created in CDB1.
APP1_USER1 can have different privileges in each Application PDB contained in APP1_ROOT.
C##_APP_USER1 can be created in CDB1.
P1_USER1 can be created in CDB1.
C##_USER1 will have the same privileges and roles granted in all PDBs in CDB1.
Answer: C F

---

## Question #:148
Which three are true about the SQL Tuning Advisor? (Choose three.)
It checks each query being analyzed for stale statistics.
It checks each query being analyzed for missing statistics.
Oracle - 1z0-083 Dumps Q&A
77 of 84 Success Guaranteed, 100% ValidC.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  It only recommends syntactic changes to SQL statements.
It can recommend semantic changes to SQL statements.
It considers all SQL statements being analyzed by the advisor task as a group.
It builds SQL profiles for each poorly performing SQL statement to prevent regressions.
Answer: A B F

---

## Question #:149
Which two are true about instance recovery? (Choose two.)
It is not possible if an archived log is missing.
It is performed automatically after the database is opened; however, blocks requiring recovery are not
available until they are recovered.
Setting FAST_START_MTTR_TARGET to a lower value reduces instance recovery time by causing
dirty buffers to be written to disk more frequently, thereby reducing the number of I/Os needed during
instance recovery.
It is performed by the Recovery Writer (RVWR) background process.
Setting FAST_START_MTTR_TARGET to a higher value reduces instance recovery time by causing
the log writer to write more frquently, thereby reducing the number of I/Os needed during instance
recovery.
It is performed automatically while the database remains in MOUNT state. Then the database is opened.
Answer: E F

---

## Question #:150
Which four are true about performing Tablespace Point -In-Time Recovery (TSPITR) using Recovery
Manager (RMAN)?
It can be performed using an auxiliary instance managed by a DBA.
It can be used to recover a truncated table.
RMAN automatically adds any required tablespaces to the recovery set to make it self-contained.
RMAN always includes tablespaces containing undo segments in the recovery set.
Oracle - 1z0-083 Dumps Q&A
78 of 84 Success Guaranteed, 100% ValidE.  
F.  
G.  
H.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  It can be performed repeatedly until the correct time is found without using an RMAN catalog.
flashback database must be enabled for it to work.
It can be used to recover a dropped tablespace.
It can be performed using an auxiliary instance managed by RMAN.
Answer: A E F H

---

## Question #:151
Which three are true about Automatic Workload Repository (AWR), Automatic Database Diagnostic Monitor
(ADDM), and the Manageability Monitor (MMON) background process? (Choose three.)
ADDM can recommend shrinking the buffer cache.
ADDM can recommend extending the buffer cache.
By default, MMON creates an AWR snapshot every 30 minutes.
ADDM performs its analysis only when a DBA requests it.
By default, AWR snapshots are automatically purged after eight days.
AWR snapshots must be deleted when no longer required by ADDM.
Answer: A B E

---

## Question #:152
In which two situations can you use Database Upgrade Assistant? (Choose two.)
when the operating system (OS) needs to be changed as part of the upgrade
when a character set conversion is required during the upgrade
when multiple pluggable databases in a container database have to be upgraded in a specific sequence
when the target and source database are on the same platform
when the hardware platform needs to be changed as part of the upgrade
Answer: C D
Oracle - 1z0-083 Dumps Q&A
79 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.

---

## Question #:153
Which two are true about Oracle Grid Infrastructure for a Standalone Server? (Choose two.)
It supports volume management, file system, and automatic restart capabilities.
It must be installed before the Oracle database software is installed.
The CSS daemon runs from the Grid Infrastructure home.
It can manage database resources on the server where it is installed or on a different server.
It requires Oracle Automatic Storage Management (ASM) components to be installed separately.
Answer: A B

---

## Question #:154
Examine this configuration:
1. CDB1 is an Oracle Database 12c Release 2 container database (CDB).
2. PDB1 and PDB2 are two pluggable databases (PDBs) in CDB1.
After successfully performing all the preupgrade tasks, you execute these commands from the Oracle
Database 18c environment:
What is the outcome?
It fails because PDB$SEED is in MIGRATE state.
Only CDB$ROOT, PDB$SEED, and PDB2 are upgraded.
Only CDB$ROOT, PDB$SEED, and PDB1 are upgraded.
CDB$ROOT, PDB$SEED, PDB1, and PDB2 are upgraded.
Only CDB$ROOT and PDB$SEED are upgraded.
It fails because PDB2 is not in UPGRADE state.
Answer: E

---

## Question #:155
Which two are true about Oracle Database Configuration Assistant (DBCA)? (Choose two.)
Oracle - 1z0-083 Dumps Q&A
80 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  It can be launched from both the command line and the Universal Installer (OUI) interfaces.
It can be used to change the character set of an existing database.
It can be used to convert a non-container database to a container database.
It can be used to create container databases and non-container databases.
It can only be launched from the command line interface.
Answer: B E

---

## Question #:156
Which two are true about data movement between a non-CDB and a PDB using Data Pump? (Choose two.)
Tablespaces are automatically created as neeed while importing full exports in either a non-CDB or a
PDB.
Oracle attempts to convert conventional database users to local users when moving schemas from a non-
CDB to a PDB.
A new PDB is automatically created when importing a non-CDB into a CDB.
Oracle attempts to convert common users to conventional users when moving schemas from a PDB to a
non-CDB.
Moving data from a PDB to a non-CDB is only possible by using transportable tablespace export and
import.
Moving data from a non-CDB to a PDB is only possible by using conventional export and import.
Answer: B D

---

## Question #:157
Which three are true about using Database Upgrade Assistant (DBUA) to upgrade a database? (Choose three.)
The Pre-Upgrade Information Tool script is executed by DBUA.
DBUA must be launched from the target Oracle Home.
All pluggable databases are automatically upgraded as part of a container database upgrade.
A whole database backup must exist before upgrade
Oracle - 1z0-083 Dumps Q&A
81 of 84 Success Guaranteed, 100% ValidE.  
F.  
A.  
B.  
C.  
D.  
E.  
F.  
A.  
B.  
C.  
D.  
E.  The database must be opened in read-only mode.
Multiple databases with the same ORACLE_HOME can be upgraded simultaneously.
Answer: A C D

---

## Question #:158
The USERS tablespace consists of data files 3 and 4 and must always be online in read/write mode.
Which two are true about using RMAN to perform an open database back up of this tablespace? (Choose two.)
Backups must be done incrementally.
Backups must be contained in backup sets.
Backups can be taken only if the database is in ARCHIVELOG mode.
Backups can be done incrementally.
The database must be registered in an RMAN catalog.
Only consistent backups can be created.
Answer: C D

---

## Question #:159
You plan to install Oracle Grid Infrastructure for a Standalone Server and Oracle Database for the first time on
a server.
Examine this command and its outcome:
Which two are true? (Choose two.)
oracle will be an owner of the Oracle Inventory.
oracle must be the owner of every Oracle Database installation.
oracle can own an Oracle Database installation but not an Oracle Grid Infrastructure installation.
oracle will be granted the SYSASM privilege when installing the Oracle Database software.
Oracle - 1z0-083 Dumps Q&A
82 of 84 Success Guaranteed, 100% ValidE.  
A.  
B.  
C.  
D.  
E.  
A.  
B.  
C.  
D.  
E.  The user account, oracle, and group, oinstall, can be used for all Oracle software installations.
Answer: A E

---

## Question #:160
Which two are true about server-generated alerts? (Choose two.)
Stateful alerts must be created by a DBA after resolving the problem.
Stateless alerts can be purged manually from the alert history.
Stateless alerts can be cleared manually.
Stateless alerts are automatically cleared.
Stateful alerts are purged automatically from the alert history.
Answer: B C
Explanation
Except for the tablespace space usage metric, which is database related, the other metrics are instance related.
Threshold alerts are also referred to as stateful alerts which are automatically cleared when an alert condition
clears. Stateful alert appears in DBA_OUTSTANDING_ALERTS and when cleared go to
DBA_ALERT_HISTORY. Other server-generated alerts correspond to specific database events such as
ORA-* errors, "Snapshot too old" errors, Recovery Area Low on Free Space, Resumable Session Suspended.
These are non threshold based alerts, also referred to as stateless alerts. Stateless alerts go directly to the
History table. +++ Most alerts (such as "Out of Space") are cleared automatically when the cause of the
problem disappears. However, other alerts (such as generic alert log errors) are sent to you for notification and
must be acknowledged by you. After taking the corrective measures, you acknowledge an alert by clearing or
purging it. Clearing an alert sends the alert to the Alert History which is accessible from Monitoring sub menu.
Purging an alert removes it from the Alert History.

---

## Question #:161
Which two are true about RMAN duplexed backup sets? (Choose two.)
They can be written only to disk.
They must be written to media.
They can be created by using the RMAN CONFIGURE command to specify duplexing before taking a
backup.
They can be created only by using the COPIES option of a BACKUP command.
Oracle - 1z0-083 Dumps Q&A
83 of 84 Success Guaranteed, 100% ValidE.  
A.  
B.  
C.  
D.  
E.  They can be written to media.
Answer: D E

---

## Question #:162
You must transport the UNIVERSITY tablespace from one database to another.
The UNIVERSITY tablespace is currently open read/write.
The source and destination platforms have different endian formats. Examine this list of actions:
1.Make the UNIVERSITY tablespace read-only on the source system.
2.Export the UNIVERSITY tablespace metadata using EXPDP.
3.Convert the UNIVERSITY tablespace data fies to the destination platform format using RMAN on the
source
system.
4.Copy the UNIVERSITY tablespace data files to the destination system.
5.Copy the Data Pump dump set to the destination system.
6.Convert the UNIVERSITY tablespace data files to the destination platform format using RMAN on the
destination system.
7.Import the UNIVERSITY tablespace metadata using IMPDP.
8.Make the UNIVERSITY tablespace read/write on the destination system.
Which is the minimum number of actions required, in the correct order, to transport the UNIVERSITY
tablespace?
1, 2, 4, 5, 7, 8
1, 2, 4, 6, 7, 8
1, 2, 3, 4, 5, 7, 8
1, 2, 3, 4, 5, 6, 7, 8
2, 4, 5, 6, 7
Answer: C
Oracle - 1z0-083 Dumps Q&A
84 of 84 Success Guaranteed, 100% ValidA.  
B.  
C.  
D.  
E.

---

## Question #:163
Which two are true about gathering optimizer statistics? (Choose two.)
Executing DBMS_STATS.GATHER_DATABASE_STATS while connected to CDB$ROOT gathers
object statistics in all open PDBs except PDB$SEED.
Executing DBMS_STATS.GATHER_DATABASE_STATS while connected to a PDB opened in
read/write mode gathers object statistics for that PDB.
Executing DBMS_STATS.GATHER_DATABASE_STATS while connected to CDB$ROOT gathers
object statistics only in CDB$ROOT.
System statistics can be gathered only while connected to CDB$ROOT.
Executing DBMS_STATS.GATHER_DATABASE_STATS while connected to CDB$ROOT gathers
object statistics in all open pluggable databases (PDBs)
Answer: B E
Explanation
https://mikedietrichde.com/2016/10/21/gather-fixed-objects-stats-in-pdbs-as-well/#:~:text=Yes%2C%20you'll%20have%20to,independently%20from%20the%20CDB%24ROOT.&text=Oracle%20Database%20automatically%20gathers%20fixed,Automatic%20Optimizer%20Statistics%20Collection%E2%80%9C)
.
About dumpscollection.com
dumpscollection.com  was founded in 2007. We provide latest & high quality IT / Business Certification Training
Exam Questions, Study Guides, Practice Tests.
We help you pass any IT / Business Certification Exams with 100% Pass Guaranteed or Full Refund. Especially
Cisco, CompTIA, Citrix, EMC, HP, Oracle, VMware, Juniper, Check Point, LPI, Nortel, EXIN and so on.
View list of all certification exams: All vendors
We prepare state-of-the art practice tests for certification exams. You can reach us at any of the email addresses listed
below.
Sales: sales@dumpscollection.com
Feedback: feedback@dumpscollection.com
Support: support@dumpscollection.com
Skype ID: crack4sure@gmail.com
Any problems about IT certification or our products, You can write us back and we will get back to you within 24
hours.
15% Discount Coupon Code: 
DC15disc

---

