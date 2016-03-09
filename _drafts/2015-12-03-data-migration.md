---
layout: post
tags: 
  - "null"
published: false
title: Data Migration
---


Data migration is the process of transferring data between storage types, formats, or computer systems. It is a key consideration for any system implementation, upgrade, or consolidation. Data migration is usually performed programmatically to achieve an automated migration, freeing up human resources from tedious tasks. Data migration occurs for a variety of reasons:
- Server or storage equipment replacements, maintenance or upgrades, 
- Application migration
- Website consolidation
- Datacenter relocation

Data growth is often times the catalyst for migration.  Other times it is performance, or the lack of it, that drives the migration effort.  Maybe it is something as simple as a missing functionality that plays a role in the migration decision.  In some cases version 1 of a storage file or system has a certain functionality, but version 2 has functionality that you might rather need or want.  Perhaps the format of the data is different with a new version of the overriding software consumer.  Often, a new version of the software will require a new format of the underlying data.  This may or may not require a migration of formats.

Lastly, Data center relocation rounds our our list of reason to migrate data.  Perhaps to consolidate geographically dispersed storage locations.  Maybe you want to perform the opposite and move your data to geographically dispersed locations; so as to not put all your eggs in one basket. Lastly, maybe it is data redundancy that initiates the data migration effort.

Data migration may impact business operations when it creates extended downtime, compatibility and performance issues.  Although migrating data can be a fairly time-consuming process, the benefits can be worth the cost.

Factors to consider in a data migration project include how long the migration will take; the amount of downtime required; and the risk to the business from technical compatibility issues, data corruption, application performance issues, and missed data or data loss.

Data migration can involve entering the data manually, moving disk files from one folder (or computer) to another, database insert queries, developing custom software, or other methods. The specific method used for any particular system depends entirely on the systems involved and the nature and state of the data being migrated.

There are three broad categories of data movers:

- Host-based software is best for application-specific migrations such as platform upgrades and for database replication and file copying.
- Array-based software is primarily used to migrate data between like systems.
- Network appliances migrate volumes, files or blocks of data depending on their configuration.

The following best practices should be used to protect data during a migration
- Backups - Before migration process make sure have backups in case your data migrations fail allowing you to roll back your systems to a known good state.  
- Testing - Perform data migration testing.  Test your data migration process within a test enviorment completely isolated from your production enviornment. Extract, transform and deduplicate data before moving it.  Validate the migrated data to ensure it is accurate.
- Understand what data you are migrating, where it lives, what form it's in and the form it will take at its new destination.
- Implement data migration policies so data is moved in an orderly manner.  With any process or documentation, audit the entire data migration process.
