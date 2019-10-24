# gen2gen

Basic Scripts to generate Gen2 task Scripts
===========================================

The scripts here are intended to provide support in the Gen2 reprocessing of the DC2 and RC2 datasets until Gen3 Buttler becomes available.

Gen3 is expected in early 2020 and therefore these scripts will become obsolete soon after that.

Therefore the code in this repo should be considered as a **temporary, short-term solution intended only for Gen2 re-processing until Gen3 is available** and not a scalable solution or the be used as the basis for future development.

With that caveat...

To run on RC2:
```
gen2-RC2-generator --DMticket DM-XXXX --week w_2019_38 --rerun2 RC/w_2019_34/DM-YYYY --filepath rerun_scripts/{DMticket}
```
To run on DC2:

```
gen2-DC2-generator --DMticket DM-1234 --week w_2019_38 --filepath rerun_scripts/{DMticket}
```
