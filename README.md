# ewbf-miner
zcash cuda miner

Writen for pascal gpus but works on cards with at least 1Gb memory, and Compute Capability 3 and higher.
Miner contain dev fee 2%.

History:

Version 0.1.0b
Speed increase 2 - 5%
For old cards compute capabilities 2.x 3.x try version 0.0.6b it can be faster.

Version 0.0.9b
- Speed increase to 10%.
- NOTE this version can be unstable.
- For old cards compute capabilities 2.x 3.x try version 0.0.6b it can be faster.

Version 0.0.8b
- "Cosmetic" optimizations of solver. Increased speed around 2%
- Reduced amount of rejected shares.
- New dynamic intensity system.

Version 0.0.7b
- Performance improvements. Old cards may be slower than with version 0.0.6b.
- I wanted release it as fast as possible. So new solver can be less stable.

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
