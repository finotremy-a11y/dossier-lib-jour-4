# Jour 4 - Ruby Exercises

This directory contains two Ruby scripts for data processing exercises.

## Files

### 00_journalists.rb

This script analyzes a list of Twitter handles (@journalists).

It performs the following operations:
- Cleans the handles by removing '@' symbols.
- Calculates total number of handles.
- Finds the shortest handles.
- Counts handles with exactly 5 characters (excluding '@').
- Counts handles starting with an uppercase letter.
- Sorts handles alphabetically and by length.
- Finds the position of '@epenser'.
- Provides distribution of handles by length.

### 01_cryptocurrencies.rb

This script analyzes a list of cryptocurrencies and their prices.

It performs the following operations:
- Cleans price strings by removing commas and spaces.
- Pairs names with prices.
- Finds the cryptocurrency with the highest price.
- Finds the cryptocurrency with the lowest price.
- Finds cryptocurrencies with prices below 6000.

## How to Run

To run the scripts, use Ruby:

```bash
ruby 00_journalists.rb
ruby 01_cryptocurrencies.rb
```

## Requirements

- Ruby installed on your system.