
Cryptocurrency Software
Miner
T-Rex v0.7.10 miner for NVIDIA ( Linux / Windows )

T-Rex is a miner designed for modern NVIDIA GPUs with Compute Capability 5.0 or greater (Maxwell and Pascal generations).

T-Rex supports Linux and Windows operating systems and currently it supports the following algorithms:

 

✔︎ lyra2z

✔︎ sonoa

✔︎ hsr

✔︎ c11

✔︎ x17

✔︎ phi

✔︎ tribus

✔︎ bitcore

✔︎ x16r

✔︎ x16s

✔︎ hmq1725

✔︎ bcd

✔︎ renesis

✔︎ balloon

✔︎ polytimos

✔︎ skunk

 

According to the devs, new algorithms will be implemented in the future releases as well as performance improvements and new features in order to provide full experience to the users. T-Rex also provides API support (HTTP JSON [preferable] and telnet ccminer compatible).

The miner contains 1% devfee providing the console output when miner starts and stops mining dev fee to provide maximum transparency possible to the users.

 

The latest version is T-Rex v0.7.10 and it contains the following bug fixes, features and improvements:

✔︎ Speed improvements: x16r/s, x17, c11, bitcore, bcd, sonoa - 1-2%

✔︎ Add functionality for setting failover pools in cmd line by specifying -o, -u and -p arguments multiple times

✔︎ New cmd line arguments: --gpu-report-interval: controls how often GPU report stats are displayed (by default every 5th share)

✔︎  --no-color: disable coloured output

✔︎ --time-limit: maximum time [s] to mine before exiting the program

✔︎ --quiet: disable GPU stats output

✔︎ Add ability to change averaging hashrate window, enable protocol dump mode, and change GPU report interval via API or web browser on the fly (without stopping the miner) - see the help file

✔︎ Fix Hung/freeze issuesInvalid shares on x16r

✔︎ Fix Long log path issue on Linux"extranonce subscribe timed out" on suprnova pools

✔︎ Showing configured pools upon start up

✔︎ Displaying colour representation of hashorders for x16r/s

✔︎ Miner uptime is displayed as part of GPU stats report


