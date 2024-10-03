# Proof of Local Development Activity

**Ticket Number**: 3397  
**Domain**: https://www.walletnexus.net


Below are the results of `ls -lt`; `wc`; `ldd` and `stat *` commands executed on the Wallet Nexus project files. This demonstrates active development with detailed timestamps of file modifications, sizes, and metadata.

## Output of `ls -lt`

total 684
-rwxr--r-- 1 dgnpacer dgnpacer   2389 30 sept. 22:34  StatisticWorker.cpp
-rw-r--r-- 1 dgnpacer dgnpacer  16605 27 sept. 17:28  toptraderholder.cpp
-rwxr--r-- 1 dgnpacer dgnpacer  29051 27 sept. 14:58  Utility.cpp
-rwxr--r-- 1 dgnpacer dgnpacer   9756 27 sept. 14:40  walletstats.cpp
-rwxr--r-- 1 dgnpacer dgnpacer   3208 25 sept. 18:10  mainwindow.h
-rw-r--r-- 1 dgnpacer dgnpacer   4564 25 sept. 18:08  toptraderholderworker.cpp
-rw-r--r-- 1 dgnpacer dgnpacer    887 25 sept. 18:06  toptraderholderworker.h
-rwxr--r-- 1 dgnpacer dgnpacer  32340 25 sept. 18:06  mainwindow.cpp
-rwxr--r-- 1 dgnpacer dgnpacer  42907 25 sept. 00:20  mainwindow.ui
-rwxr--r-- 1 dgnpacer dgnpacer   2330 24 sept. 23:40  ScraperWorker.cpp
-rwxr--r-- 1 dgnpacer dgnpacer  45612 24 sept. 23:33  BaseScraper.cpp
-rwxr--r-- 1 dgnpacer dgnpacer   2180 24 sept. 12:26  Utility.h
-rw-r--r-- 1 dgnpacer dgnpacer   1340 24 sept. 01:59  toptraderholder.h
-rwxr--r-- 1 dgnpacer dgnpacer   5377  7 sept. 22:22  subscriptionchecker.cpp
-rwxr--r-- 1 dgnpacer dgnpacer   4251  5 sept. 17:00  CorrelationWorker.cpp
-rwxr--r-- 1 dgnpacer dgnpacer    812  5 sept. 17:00  Correlation.h
-rwxr--r-- 1 dgnpacer dgnpacer   4863  5 sept. 17:00  Correlation.cpp
-rwxr--r-- 1 dgnpacer dgnpacer   2037  5 sept. 17:00  BaseScraper.h
-rwxr--r-- 1 dgnpacer dgnpacer    372  5 sept. 17:00  walletstats.h
-rwxr--r-- 1 dgnpacer dgnpacer   1886  5 sept. 17:00  Wallet_Nexus.pem
-rwxr--r-- 1 dgnpacer dgnpacer      0  5 sept. 17:00 'Wallet Nexus.sig'
-rwxr--r-- 1 dgnpacer dgnpacer    743  5 sept. 17:00  StatisticWorker.h
-rwxr--r-- 1 dgnpacer dgnpacer    793  5 sept. 17:00  ScraperWorker.h
-rwxr--r-- 1 dgnpacer dgnpacer    451  5 sept. 17:00  public_Nexus.pem
-rwxr--r-- 1 dgnpacer dgnpacer    165  5 sept. 17:00  nodebug.h
-rwxr--r-- 1 dgnpacer dgnpacer  71120  5 sept. 17:00  miniz.h
-rwxr--r-- 1 dgnpacer dgnpacer 322549  5 sept. 17:00  miniz.c
-rwxr--r-- 1 dgnpacer dgnpacer    570  5 sept. 17:00  main.cpp
-rwxr--r-- 1 dgnpacer dgnpacer   1393  5 sept. 17:00  CorrelationWorker.h
-rwxr--r-- 1 dgnpacer dgnpacer   1296  5 sept. 17:00  subscriptionchecker.h
-rwxr--r-- 1 dgnpacer dgnpacer    375  5 sept. 17:00  encryption.h
-rwxr--r-- 1 dgnpacer dgnpacer    926  5 sept. 17:00  encryption.cpp

## Output of `stat *`

stat *                                                                                                                                                                                                  
  File: BaseScraper.cpp
  Size: 45612     	Blocks: 96         IO Block: 4096   regular file
Device: 8,1	Inode: 638788658   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-10-03 12:06:49.747932340 +0200
Modify: 2024-09-24 23:33:42.994952394 +0200
Change: 2024-09-24 23:33:42.994952394 +0200
 Birth: 2024-09-23 14:05:20.068750584 +0200
  File: BaseScraper.h
  Size: 2037      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788659   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-10-03 12:04:53.348912438 +0200
Modify: 2024-09-05 17:00:22.734376900 +0200
Change: 2024-09-23 14:05:20.068750584 +0200
 Birth: 2024-09-23 14:05:20.068750584 +0200
  File: Correlation.cpp
  Size: 4863      	Blocks: 16         IO Block: 4096   regular file
Device: 8,1	Inode: 638788631   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.347436936 +0200
Modify: 2024-09-05 17:00:22.750022700 +0200
Change: 2024-09-23 14:05:20.045416987 +0200
 Birth: 2024-09-23 14:05:20.045416987 +0200
  File: Correlation.h
  Size: 812       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788632   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.330769895 +0200
Modify: 2024-09-05 17:00:22.765730800 +0200
Change: 2024-09-23 14:05:20.048750358 +0200
 Birth: 2024-09-23 14:05:20.048750358 +0200
  File: CorrelationWorker.cpp
  Size: 4251      	Blocks: 16         IO Block: 4096   regular file
Device: 8,1	Inode: 638788660   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.367437385 +0200
Modify: 2024-09-05 17:00:22.781362500 +0200
Change: 2024-09-23 14:05:20.068750584 +0200
 Birth: 2024-09-23 14:05:20.068750584 +0200
  File: CorrelationWorker.h
  Size: 1393      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788633   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.327436487 +0200
Modify: 2024-09-05 17:00:22.312718500 +0200
Change: 2024-09-23 14:05:20.048750358 +0200
 Birth: 2024-09-23 14:05:20.048750358 +0200
  File: encryption.cpp
  Size: 926       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788634   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.370770793 +0200
Modify: 2024-09-05 17:00:20.218582600 +0200
Change: 2024-09-23 14:05:20.048750358 +0200
 Birth: 2024-09-23 14:05:20.048750358 +0200
  File: encryption.h
  Size: 375       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788635   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.327436487 +0200
Modify: 2024-09-05 17:00:20.249898100 +0200
Change: 2024-09-23 14:05:20.048750358 +0200
 Birth: 2024-09-23 14:05:20.048750358 +0200
  File: main.cpp
  Size: 570       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788638   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.370770793 +0200
Modify: 2024-09-05 17:00:22.374850200 +0200
Change: 2024-09-23 14:05:20.048750358 +0200
 Birth: 2024-09-23 14:05:20.048750358 +0200
  File: mainwindow.cpp
  Size: 32340     	Blocks: 64         IO Block: 4096   regular file
Device: 8,1	Inode: 638788640   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.390771242 +0200
Modify: 2024-09-25 18:06:04.796450653 +0200
Change: 2024-09-25 18:06:04.796450653 +0200
 Birth: 2024-09-23 14:05:20.048750358 +0200
  File: mainwindow.h
  Size: 3208      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788639   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.344103527 +0200
Modify: 2024-09-25 18:10:01.491111697 +0200
Change: 2024-09-25 18:10:01.491111697 +0200
 Birth: 2024-09-23 14:05:20.048750358 +0200
  File: mainwindow.ui
  Size: 42907     	Blocks: 88         IO Block: 4096   regular file
Device: 8,1	Inode: 638788641   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-27 17:29:08.415009771 +0200
Modify: 2024-09-25 00:20:57.600838488 +0200
Change: 2024-09-25 00:20:57.600838488 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: miniz.c
  Size: 322549    	Blocks: 632        IO Block: 4096   regular file
Device: 8,1	Inode: 638788642   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-27 17:29:08.428343370 +0200
Modify: 2024-09-05 17:00:22.453067200 +0200
Change: 2024-09-23 14:05:20.065417214 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: miniz.h
  Size: 71120     	Blocks: 144        IO Block: 4096   regular file
Device: 8,1	Inode: 638788643   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-27 17:29:08.431676772 +0200
Modify: 2024-09-05 17:00:22.468722600 +0200
Change: 2024-09-23 14:05:20.065417214 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: nodebug.h
  Size: 165       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788644   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-10-03 12:04:53.425582395 +0200
Modify: 2024-09-05 17:00:22.484374100 +0200
Change: 2024-09-23 14:05:20.065417214 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: public_Nexus.pem
  Size: 451       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788645   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-27 17:29:08.435010170 +0200
Modify: 2024-09-05 17:00:22.515717700 +0200
Change: 2024-09-23 14:05:20.065417214 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: ScraperWorker.cpp
  Size: 2330      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788646   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.394104651 +0200
Modify: 2024-09-24 23:40:05.853288729 +0200
Change: 2024-09-24 23:40:05.853288729 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: ScraperWorker.h
  Size: 793       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788647   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.324103078 +0200
Modify: 2024-09-05 17:00:22.547023700 +0200
Change: 2024-09-23 14:05:20.065417214 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: StatisticWorker.cpp
  Size: 2389      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788648   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-10-03 12:03:31.045744326 +0200
Modify: 2024-09-30 22:34:29.520190253 +0200
Change: 2024-09-30 22:34:29.520190253 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: StatisticWorker.h
  Size: 743       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788649   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-10-03 12:04:53.245574672 +0200
Modify: 2024-09-05 17:00:22.578323300 +0200
Change: 2024-09-23 14:05:20.065417214 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: subscriptionchecker.cpp
  Size: 5377      	Blocks: 16         IO Block: 4096   regular file
Device: 8,1	Inode: 638788650   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.370770793 +0200
Modify: 2024-09-07 22:22:29.451003700 +0200
Change: 2024-09-23 14:05:20.065417214 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: subscriptionchecker.h
  Size: 1296      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788651   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.324103078 +0200
Modify: 2024-09-05 17:00:20.359492600 +0200
Change: 2024-09-23 14:05:20.065417214 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: toptraderholder.cpp
  Size: 16605     	Blocks: 40         IO Block: 4096   regular file
Device: 8,1	Inode: 638691080   Links: 1
Access: (0644/-rw-r--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.390771242 +0200
Modify: 2024-09-27 17:28:21.600736161 +0200
Change: 2024-09-27 17:28:21.600736161 +0200
 Birth: 2024-09-23 17:47:56.814523320 +0200
  File: toptraderholder.h
  Size: 1340      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638691079   Links: 1
Access: (0644/-rw-r--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.344103527 +0200
Modify: 2024-09-24 01:59:48.877912963 +0200
Change: 2024-09-24 01:59:48.877912963 +0200
 Birth: 2024-09-23 17:47:41.344171361 +0200
  File: toptraderholderworker.cpp
  Size: 4564      	Blocks: 16         IO Block: 4096   regular file
Device: 8,1	Inode: 638691078   Links: 1
Access: (0644/-rw-r--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.404104874 +0200
Modify: 2024-09-25 18:08:30.622662934 +0200
Change: 2024-09-25 18:08:30.622662934 +0200
 Birth: 2024-09-23 17:47:18.063641640 +0200
  File: toptraderholderworker.h
  Size: 887       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638691077   Links: 1
Access: (0644/-rw-r--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.347436936 +0200
Modify: 2024-09-25 18:06:59.307529908 +0200
Change: 2024-09-25 18:06:59.307529908 +0200
 Birth: 2024-09-23 17:46:53.569750866 +0200
  File: Utility.cpp
  Size: 29051     	Blocks: 64         IO Block: 4096   regular file
Device: 8,1	Inode: 638788652   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-30 22:34:55.370770793 +0200
Modify: 2024-09-27 14:58:30.137807681 +0200
Change: 2024-09-27 14:58:30.137807681 +0200
 Birth: 2024-09-23 14:05:20.065417214 +0200
  File: Utility.h
  Size: 2180      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788653   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-10-03 12:04:53.692260502 +0200
Modify: 2024-09-24 12:26:36.576511733 +0200
Change: 2024-09-24 12:26:36.576511733 +0200
 Birth: 2024-09-23 14:05:20.068750584 +0200
  File: Wallet_Nexus.pem
  Size: 1886      	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788657   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-27 17:29:08.455010572 +0200
Modify: 2024-09-05 17:00:22.656117300 +0200
Change: 2024-09-23 14:05:20.068750584 +0200
 Birth: 2024-09-23 14:05:20.068750584 +0200
  File: Wallet Nexus.sig
  Size: 0         	Blocks: 0          IO Block: 4096   regular empty file
Device: 8,1	Inode: 638788654   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-09-27 17:29:08.448343772 +0200
Modify: 2024-09-05 17:00:22.640460900 +0200
Change: 2024-09-23 14:05:20.068750584 +0200
 Birth: 2024-09-23 14:05:20.068750584 +0200
  File: walletstats.cpp
  Size: 9756      	Blocks: 24         IO Block: 4096   regular file
Device: 8,1	Inode: 638788655   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-10-03 12:03:31.039077468 +0200
Modify: 2024-09-27 14:40:58.113330934 +0200
Change: 2024-09-27 14:40:58.113330934 +0200
 Birth: 2024-09-23 14:05:20.068750584 +0200
  File: walletstats.h
  Size: 372       	Blocks: 8          IO Block: 4096   regular file
Device: 8,1	Inode: 638788656   Links: 1
Access: (0744/-rwxr--r--)  Uid: ( 1000/dgnpacer)   Gid: ( 1000/dgnpacer)
Access: 2024-10-03 12:04:53.255575100 +0200
Modify: 2024-09-05 17:00:22.703061000 +0200
Change: 2024-09-23 14:05:20.068750584 +0200
 Birth: 2024-09-23 14:05:20.068750584 +0200

## Lines of Code per files 

 find . -name '*.cpp' -or -name '*.h' | xargs wc -l                                                                                                                                                     
   151 ./Correlation.cpp
    22 ./Correlation.h
    50 ./CorrelationWorker.h
    29 ./encryption.cpp
    13 ./encryption.h
    36 ./main.cpp
   101 ./mainwindow.h
   857 ./mainwindow.cpp
  1422 ./miniz.h
    11 ./nodebug.h
    69 ./ScraperWorker.cpp
    41 ./ScraperWorker.h
    57 ./StatisticWorker.cpp
    34 ./StatisticWorker.h
   151 ./subscriptionchecker.cpp
    44 ./subscriptionchecker.h
   662 ./Utility.cpp
    69 ./Utility.h
   223 ./walletstats.cpp
    22 ./walletstats.h
  1115 ./BaseScraper.cpp
    63 ./BaseScraper.h
    93 ./CorrelationWorker.cpp
   133 ./toptraderholderworker.cpp
    42 ./toptraderholder.h
   400 ./toptraderholder.cpp
    39 ./toptraderholderworker.h
  5949 total

##  Linked Libraries 

ldd ./Wallet_Nexus                                                                                                                                                                                   
	linux-vdso.so.1 (0x00007e5f95bfe000)
	libQt5Widgets.so.5 => /usr/lib/libQt5Widgets.so.5 (0x00007e5f95000000)
	libQt5Network.so.5 => /usr/lib/libQt5Network.so.5 (0x00007e5f94e93000)
	libcurl.so.4 => /usr/lib/libcurl.so.4 (0x00007e5f95af9000)
	libz.so.1 => /usr/local/lib/libz.so.1 (0x00007e5f95acd000)
	libQt5Gui.so.5 => /usr/lib/libQt5Gui.so.5 (0x00007e5f94800000)
	libQt5Core.so.5 => /usr/lib/libQt5Core.so.5 (0x00007e5f94200000)
	libssl.so.3 => /usr/lib/libssl.so.3 (0x00007e5f95725000)
	libcrypto.so.3 => /usr/lib/libcrypto.so.3 (0x00007e5f93c00000)
	libstdc++.so.6 => /usr/lib/libstdc++.so.6 (0x00007e5f93800000)
	libm.so.6 => /usr/lib/libm.so.6 (0x00007e5f94111000)
	libgcc_s.so.1 => /usr/lib/libgcc_s.so.1 (0x00007e5f956f7000)
	libc.so.6 => /usr/lib/libc.so.6 (0x00007e5f9360f000)
	/lib64/ld-linux-x86-64.so.2 => /usr/lib64/ld-linux-x86-64.so.2 (0x00007e5f95c00000)
	libgssapi_krb5.so.2 => /usr/lib/libgssapi_krb5.so.2 (0x00007e5f956a4000)
	libproxy.so.1 => /usr/lib/libproxy.so.1 (0x00007e5f95ac4000)
	libnghttp3.so.9 => /usr/lib/libnghttp3.so.9 (0x00007e5f947dd000)
	libnghttp2.so.14 => /usr/lib/libnghttp2.so.14 (0x00007e5f947b3000)
	libidn2.so.0 => /usr/lib/libidn2.so.0 (0x00007e5f94791000)
	libssh2.so.1 => /usr/lib/libssh2.so.1 (0x00007e5f94748000)
	libpsl.so.5 => /usr/lib/libpsl.so.5 (0x00007e5f940fd000)
	libzstd.so.1 => /usr/lib/libzstd.so.1 (0x00007e5f93b21000)
	libbrotlidec.so.1 => /usr/lib/libbrotlidec.so.1 (0x00007e5f940ee000)
	libGL.so.1 => /usr/lib/libGL.so.1 (0x00007e5f93a9b000)
	libpng16.so.16 => /usr/lib/libpng16.so.16 (0x00007e5f935d4000)
	libharfbuzz.so.0 => /usr/lib/libharfbuzz.so.0 (0x00007e5f934b5000)
	libmd4c.so.0 => /usr/lib/libmd4c.so.0 (0x00007e5f940d8000)
	libsystemd.so.0 => /usr/lib/libsystemd.so.0 (0x00007e5f933c1000)
	libdouble-conversion.so.3 => /usr/lib/libdouble-conversion.so.3 (0x00007e5f933aa000)
	libicui18n.so.75 => /usr/lib/libicui18n.so.75 (0x00007e5f93000000)
	libicuuc.so.75 => /usr/lib/libicuuc.so.75 (0x00007e5f92e06000)
	libpcre2-16.so.0 => /usr/lib/libpcre2-16.so.0 (0x00007e5f92d74000)
	libglib-2.0.so.0 => /usr/lib/libglib-2.0.so.0 (0x00007e5f92c24000)
	libkrb5.so.3 => /usr/lib/libkrb5.so.3 (0x00007e5f92b5f000)
	libk5crypto.so.3 => /usr/lib/libk5crypto.so.3 (0x00007e5f9337d000)
	libcom_err.so.2 => /usr/lib/libcom_err.so.2 (0x00007e5f94e8d000)
	libkrb5support.so.0 => /usr/lib/libkrb5support.so.0 (0x00007e5f93a8d000)
	libkeyutils.so.1 => /usr/lib/libkeyutils.so.1 (0x00007e5f94741000)
	libresolv.so.2 => /usr/lib/libresolv.so.2 (0x00007e5f92b4d000)
	libpxbackend-1.0.so => /usr/lib/libproxy/libpxbackend-1.0.so (0x00007e5f92b3e000)
	libgobject-2.0.so.0 => /usr/lib/libgobject-2.0.so.0 (0x00007e5f92ade000)
	libunistring.so.5 => /usr/lib/libunistring.so.5 (0x00007e5f9292e000)
	libbrotlicommon.so.1 => /usr/lib/libbrotlicommon.so.1 (0x00007e5f9290b000)
	libGLdispatch.so.0 => /usr/lib/libGLdispatch.so.0 (0x00007e5f92853000)
	libGLX.so.0 => /usr/lib/libGLX.so.0 (0x00007e5f92821000)
	libfreetype.so.6 => /usr/lib/libfreetype.so.6 (0x00007e5f92757000)
	libgraphite2.so.3 => /usr/lib/libgraphite2.so.3 (0x00007e5f92735000)
	libcap.so.2 => /usr/lib/libcap.so.2 (0x00007e5f92729000)
	libicudata.so.75 => /usr/lib/libicudata.so.75 (0x00007e5f90800000)
	libpcre2-8.so.0 => /usr/lib/libpcre2-8.so.0 (0x00007e5f9268a000)
	libgio-2.0.so.0 => /usr/lib/libgio-2.0.so.0 (0x00007e5f90631000)
	libduktape.so.207 => /usr/lib/libduktape.so.207 (0x00007e5f9263e000)
	libffi.so.8 => /usr/lib/libffi.so.8 (0x00007e5f92633000)
	libX11.so.6 => /usr/lib/libX11.so.6 (0x00007e5f904f0000)
	libbz2.so.1.0 => /usr/lib/libbz2.so.1.0 (0x00007e5f92620000)
	libgmodule-2.0.so.0 => /usr/lib/libgmodule-2.0.so.0 (0x00007e5f93a86000)
	libmount.so.1 => /usr/lib/libmount.so.1 (0x00007e5f925d1000)
	libxcb.so.1 => /usr/lib/libxcb.so.1 (0x00007e5f925a6000)
	libblkid.so.1 => /usr/lib/libblkid.so.1 (0x00007e5f9256d000)
	libXau.so.6 => /usr/lib/libXau.so.6 (0x00007e5f92568000)
	libXdmcp.so.6 => /usr/lib/libXdmcp.so.6 (0x00007e5f92560000)
