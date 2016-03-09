---
layout: post
tags: 
  - "null"
published: false
title: data deduplication
---


## A New Post

data deduplication - specifically as it applies to backup
 
Data redundancy can occur by accident or done purposely for backup and recovery plans.  Repetition of data can cause distortion and corruption of files.  Having redundant data makes your backup process more pricey and tedious, while operating less efficient.
 
One of the earliest approaches to data reduction was data compression.  Compression and data deduplication operate very differently.
Compression uses an algorithm to minimize the size of the data by reducing the number of bits needed to represent data. Compression  reduces the bits by identifying and eliminating redundancy.   You are able to uncompress the data through a lossless process.  Lossless compression enables restoration to the original state of the file.
 
 
 
Data deduplication is the newest technique for reducing data.
Data deduplication involves looking for redundancy of sequences and removing duplication within data.  Deduplication eliminates extra data by saving an original copy and then replaces the other copies with pointers that lead back to the original.  Deduplication looks for redundant blocks of data across a system and replaces each duplicate block with a pointer to the original.
 
Several companies use deduplication to free up space in storage, they also use it often in backup and disaster recovery applications.
 
Reducing the amount of duplicate data benefits maintenance, effectively increases network bandwidth, and reduces storage allocation which helps disk cost and also reduces the amount of data that needs to be moved making your data more managable.  Deduplication improves performance and benefits maintenance ensuring the backup runs proficiently.  The obvious and probably most beneficial is the decrease in storage cost.  These savings can be achieved by backup and other data management application savings and equipment savings in disk purchases.
