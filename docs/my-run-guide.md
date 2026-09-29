# My Run Guide

## Prerequisites

- Git 2.23 or later
- JDK 17 or later (both `java` and `javac` on PATH)
- Python 3.9 or later

## Run the demo

From the repository root:

    python3 run.py demo

## What the demo does

The demo runs the small Java library application end to end:
it builds a catalog, registers members, performs loans under
the two-book / 14-day borrowing policy, computes overdue fees
at 100 units per day, and prints the results of a title search.