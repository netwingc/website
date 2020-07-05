This Documentation is about the Mims Oracle database 

Last updated by 
Dinand van Hartingsveldt
on 
23/06/2020

Index

1. [ Description Environment ](#desc)
2. [ Backup ](#backup)
3. [ Maintenance ](#Maintenance)
4. [ Structure ](#Structure)
5. [ Log ](#Log)
6. [ Schemas ](#Schemas)
7. [ Roles ](#Roles)
8. [ Connection ](#Connection)
8. [ Security ](#Security)

<a name="desc"></a>
## 1. Description Environment

**Windows Server** 
* **Server name:**     ML-NDB
* **Gateway address:** ml.magnalabs.co.uk  (81.149.45.236)
* **OS :**             Windows Server 2016 Standard 64bit

**Database server**
* **Version :**  12c Standard Edition Release 12.2.0.1.0 - 64bit 
* **Patch level:** No patches installed

<a name="backup"></a>
## 2. Backup

At the time of the intake (01-07-2020), no RMAN backups can be found.  
There is a daily job that runs at 19:00 every day, which exports the schemas 'LIMS' and 'LIMS_SYS'. (The last successful run was at 28-06-2020)


<a name="Maintenance"></a>
## 3. Maintenance

What maintenance must be done, and what are inspection points. Frequency, and bullet list of work.
### Performance
Describe how to maintain for performance

### Prevent Issues
Describe how to prevent Issues

<a name="Structure"></a>
## 4. Structure

What structure do we use in the Database like.
- Where are scripts stored, how, are there standards, Is there a naming convention, Are there Quality issues

Q Is the existing structure correct and a known system ?

<a name="Log"></a>
## 5. Log
Q On what level is log configured and does it cover.

<a name="Schemas"></a>
## 6. Schemas 

<a name="Roles"></a>
## 7 Roles and Users
- Is the DB connected to a main system for user rights and roles
Q Is the structure of roles and users clear and logical (like groups for common access).

<a name="Connection"></a>
## 8. Connection

### Production database

#### Connect string:
*	**Host name :** ml.magnalabs.co.uk  
*	**Port:** 1521
*	**Service name:** NPROD


### Test database

#### Connect string:

* **Host name:** ml.magnalabs.co.uk
* **Port:** 1521
* **Service name:** NPTEST

<a name="Security"></a>
## 9. Security

- How is the security of the Database and all entries. 

Q Can rights been reduced without losing functionality
