# What's this chapter about?

It is defacto standard that `SQLite` database is default databases for 
almost every mobile platforms including Android and iOS (although
there are some move to change default database). 

SQLite provides two journal modes `RBJ (Rollback Journal)` and `WAL(Write Ahead Log)`.
[SQLite summary](summary.md) describes two journal modes. 

## Simple Optimization of SQLite with BtrFS
This optimization technique that I implemented 
decreases ***write amplification*** by SQLite on `BtrFS` filesystems.

[BtrFS's Opportunity](opportunity.md) describes the details of
opportunity in BtrFS and the optimization technique.

SQLite `WAL` mode has already changed. 
<br>SQLite `RBJ` mode is still in progress. 
<br>You can find the source
codes from [Github: SQLite](https://github.com/wurikiji/SQLite-on-BtrFS).




