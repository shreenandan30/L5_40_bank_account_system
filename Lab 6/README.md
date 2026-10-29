# Lab 6: Code and Branch Coverage — Ride Share Fare

**Lab application:** `ride_share_fare.py`

## About

A small Python module that calculates extra-distance fares by cab type, zone, and subscription; checks seat and bag limits; and reports driver pickup status.

## Files

| File | Description |
|------|-------------|
| `ride_share_fare.py` | Application module being tested |
| `test_ride_share_fare.py` | Starter test file supplied with the lab |
| `CodeCoverageTest_40_ride_share_fare.py` | Test suite for code/statement coverage |
| `BranchCoverageTest_40_ride_share_fare.py` | Test suite for branch coverage |
| `screenshots/CodeCoverage_40.png` | Terminal screenshot showing code coverage |
| `screenshots/BranchCoverage_40.png` | Terminal screenshot showing branch coverage |

## Install dependencies

```bash
python -m pip install pytest coverage
```

## Code coverage

Run from this folder:

```bash
coverage erase
coverage run --source=ride_share_fare -m pytest CodeCoverageTest_40_ride_share_fare.py
coverage report -m
```

## Branch coverage

```bash
coverage erase
coverage run --branch --source=ride_share_fare -m pytest BranchCoverageTest_40_ride_share_fare.py
coverage report -m
```

## Results recorded for this submission

- Code coverage suite: 15 tests passed; 97% code coverage.
- Branch coverage suite: 21 tests passed; 100% branch coverage.

These figures are from the local terminal runs captured in the screenshots above.
