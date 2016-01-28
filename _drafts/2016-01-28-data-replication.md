---
layout: post
tags: null
published: false
title: data replication
---

## A New Post
data replication

When replicating your data offsite, if your primary site is down due to power outage, disaster, or failure, you still have your secondary site with replicated data accessible.

In most cases you need both data backup and data replication depending on how available you need your data to be.  They both address different risks when dealing with data availability.  Replication involves copying data from one machine to another machine, typically in a geographically dispersed fashion, but not always.  

Replication is achieved either synchronously or asynchronously with the only difference being is the way the in which the data is written to the replica.  Synchronous replication is the process of copying data over a storage, local, or wide area network so there are several up to date copies.  Synchronous replication is more expensive and writes data to the primary and secondary site at the same time.  

Asynchronous replication does not always occur in real-time, but is on a scheduled basis.  The data is written to the primary source first, then copied to the secondary storage.  Since Asynchronous replication does not have to occur in real-time it is often better designed to work over a long distance and is less expensive.

Replication is not a replacement for backup.  Corruption is one reason why replication can’t replace backup because the same corruption would likely be replicated to the destination.

Time is another point of separation between data replication and backup.  Replication allows almost immediate accessibility to your current data, where as backup may take you some time to recover.  The longer it takes to restore your data, the more time and money you are likely to lose.
  
Although replication is very expensive, it is worth it if you have vital information you cannot wait for if one of your systems was to fail.
