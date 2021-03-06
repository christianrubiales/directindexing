# directindexing
Direct Indexing

Calculates the minimum requirement to roughly mirror an index.

Inputs:

- prices.csv - must contain the first 3 columns: STOCK, PRICE, WEIGHT
- boardlot.csv

Example Output for PSEI:

```
STOCK, PRICE, WEIGHT, LOT SIZE, SHARES, TOTAL PRICE, CALCULATED WEIGHT
[
AC, 930.0, 7.22%, 10, 40, 37,200.00, 5.83%, 
AEV, 60.0, 4.16%, 10, 440, 26,400.00, 4.13%, 
AGI, 13.7, 1.1%, 100, 500, 6,850.00, 1.07%, 
ALI, 43.2, 8.86%, 100, 1,300, 56,160.00, 8.79%, 
AP, 35.0, 1.31%, 100, 200, 7,000.00, 1.10%, 
BDO, 123.7, 6.52%, 10, 330, 40,821.00, 6.39%, 
BLOOM, 11.32, 1.17%, 100, 600, 6,792.00, 1.06%, 
BPI, 84.0, 4.86%, 10, 360, 30,240.00, 4.74%, 
DMC, 11.18, 1.11%, 100, 600, 6,708.00, 1.05%, 
FGEN, 21.3, 0.66%, 100, 100, 2,130.00, 0.33%, 
GLO, 1903.0, 1.49%, 5, 5, 9,515.00, 1.49%, 
GTCAP, 930.0, 2.18%, 10, 10, 9,300.00, 1.46%, 
ICT, 113.0, 3.1%, 10, 170, 19,210.00, 3.01%, 
JFC, 309.0, 3.97%, 10, 80, 24,720.00, 3.87%, 
JGS, 65.8, 5.17%, 10, 500, 32,900.00, 5.15%, 
LTG, 15.24, 1.15%, 100, 400, 6,096.00, 0.95%, 
MBT, 75.2, 3.92%, 10, 330, 24,816.00, 3.89%, 
MEG, 5.15, 1.51%, 100, 1,800, 9,270.00, 1.45%, 
MER, 367.0, 2.32%, 10, 40, 14,680.00, 2.30%, 
MPI, 4.57, 1.62%, 1,000, 2,000, 9,140.00, 1.43%, 
PGOLD, 46.8, 1.14%, 100, 100, 4,680.00, 0.73%, 
RLC, 22.8, 1.24%, 100, 300, 6,840.00, 1.07%, 
RRHI, 86.5, 1.24%, 10, 90, 7,785.00, 1.22%, 
SCC, 21.75, 0.64%, 100, 100, 2,175.00, 0.34%, 
SECB, 162.5, 1.93%, 10, 70, 11,375.00, 1.78%, 
SM, 940.0, 13.33%, 10, 90, 84,600.00, 13.25%, 
SMC, 170.7, 1.63%, 10, 60, 10,242.00, 1.60%, 
SMPH, 37.95, 9.38%, 100, 1,500, 56,925.00, 8.91%, 
TEL, 1030.0, 2.5%, 5, 15, 15,450.00, 2.42%, 
URC, 137.0, 3.56%, 10, 160, 21,920.00, 3.43%]
Total Requirement: 601,940.00
Total Calculated Weight: 94.26%
```
