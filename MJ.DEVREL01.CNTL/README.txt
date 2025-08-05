MJ.DEVREL01.CNTL 

This folder represents the partition dataset where I keep my JCL Utility Jobs such as

Allocating Partition Datasets
Allocation Sequential Files
SORT
SORT / Merge

For GDG Generation:
  1) DEFGDG - The Generational Dataset Base Definition. Only works with VOL=SER=TSO001 as the user catalog seems to go there.
  2) DEFGEN - The Generational Dataset Generation Definition. This is how to allocate Generation Data set based off of your GDGBase.

To use this in MVS 3.8 simply allocated yourself a Partition Dataset and copy and paste the files into the members. 

