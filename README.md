# Scalameter Shaded

This project simply shades the awesome Scalameter's required jackson version so it can be used alongside different Spark versions.

## Why should you use it?

When you have jackson errors when running Scalameter tests at result writing (or at Spark startup if you force an earlier version) due to incompatible versions (2.9.9 from Scalameter 0.19 and >2.13 etc. on Spark).

## What versions are used?

Scalameter 0.19 is the last version with 2.12 support (as used by Spark 3.x in most distributions), but it also introduces 2.13 support allowing Spark 4 to be supported.
