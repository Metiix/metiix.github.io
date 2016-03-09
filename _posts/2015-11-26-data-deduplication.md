---
layout: post
tags: 
  - "null"
published: false
title: data deduplication
---


Data redundancy can occur by accident or done purposely for backup and recovery plans.  Repetition of data can cause distortion and corruption of files.  Having redundant data makes your backup process more pricey and tedious, while operating less efficient.
 
One of the earliest approaches to data reduction was data compression.  Compression and data deduplication operate somewhat differently.  Compression uses an algorithm to minimize the size of the data by reducing the number of bits needed to represent data. Compression  reduces the bits by identifying and eliminating redundancy.   You are typically able to uncompress the data through a lossless process.  Lossless compression enables restoration to the original state of the file.

Data deduplication, one of the newest techniques for reducing data, involves looking for redundancy of sequences and removing duplication within data.  Deduplication eliminates extra data by saving an original copy and then replaces the other copies with pointers that lead back to the original.  Deduplication looks for redundant blocks of data across a system, or even multiple systems, and replaces each duplicate block with a pointer to the original block of data.
 
Reducing the amount of redudant blocks of data benefits maintenance, effectively increases network bandwidth, and reduces storage allocation which helps disk cost and also reduces the amount of data that needs to be moved making your data more managable.  

Deduplication improves performance and benefits maintenance ensuring the backup runs proficiently.  The obvious and probably most beneficial is the decrease in backup storage cost.  These savings can be achieved reducing the capacity needed to protect large sums of online data.

[Metiix](http://www.metiix.com "Metiix data deduplication software") is very proficient in data deduplication techniques and employs this process accross almost all of its data protection services.  [Let us help you](http://www.metiix.com/contact-us "Contact Metiix") understand the benefits of data deduplication.
