# ewbf-miner
zcash cuda miner

Writen for pascal gpus but works on cards with at least 1Gb memory, and Compute Capability 3 and higher.
Miner contain dev fee 2%.

History:

Version 0.0.6b
- For some older cards performance improvements up to 10%
- Bug fixes

Version 0.0.5b
- Speed improvement up to 20%
- Fixed stratum compatibility (works better with many pools)
- Fixed 1Gb card bug
- Added statistic (counter of shares and ping)

Version 0.0.4b
- Completely new watchdog system.
- Fixed a bug in the solver
- Binary linux version compiled and tested in debian.
