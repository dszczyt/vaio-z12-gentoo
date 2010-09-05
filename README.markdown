How to install Gentoo on your Z12
=================================

This tutorial should help you for installing a Gentoo Linux system on your Z12. I based this tutorial on a Z12Z9E/X.

Prepare partitions
------------------

First thing to do is to resize windows 7 partition. I used an Ubuntu livecd, in order to have a graphical tool to do this. Open a terminal, sudo su and run gparted /dev/mapper/isw\_....0 . And you can resize your partitions. Reduce only the Windows partition. Create an extended volume on the free space. Add 200M partition at start, and another partition with no file system (I'm using LVM).


_To be completed..._

