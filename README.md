# IFTE0007-SP500-7Day

UCL IFTE0007 Decentralised Finance and Blockchain, Group 14: seven-trading-day forecast of the S&P 500 price index.

**Final forecast (the binding value stated in the report): 7,632.87 index points** for the S&P Dow Jones Indices official close of the S&P 500 price index on Friday 20 November 2026, 16:00 New York (EST) / 21:00 London (GMT).

## Evidence package

**Download: [IFTE0007_Group14_Evidence_review.zip](https://github.com/zzzhil912-cell/IFTE0007-SP500-7Day/raw/main/IFTE0007_Group14_Evidence_review.zip)**
(SHA-256 `813faab51f2401116204faca8de6faa0dd42619494e1d7b66e5b6aae967e23b6`)

The ZIP contains the code (frozen forecast script and independent recomputation script), reproduction steps and clearly labelled **synthetic sample data**.

1. Download and unzip it, then start with the `README.md` inside the ZIP.
2. Run the synthetic sample route first: with Python 3.11, `python3 -m pip install -r 02_reproduce/requirements.txt`, then from `02_reproduce/` run `python3 -I run_rehearsal.py --route sample`. The last line should read `RESULT: PASS`.
3. The synthetic route demonstrates the workflow only; its numbers have no economic meaning. The formal forecast is 7,632.87, as stated in the report. Recomputing it exactly needs the original Yahoo Finance input, which is kept in the group archive and not redistributed (see the ZIP README).
