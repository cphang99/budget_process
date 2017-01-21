#process-budget

##Usage

```
Usage: process-budget-exe (-i|--input FILE.csv) [-o|--output FILE.csv]
  Outputs a breakdown of monthly spending by category

Available options:
-h,--help                Show this help text
-i,--input FILE.csv      input file
-o,--output FILE.csv     output file
```

Csv files should have columns in the following order:
- 1) date
- 2) transaction type
- 3) description
- 4) amount
- 5) category
- 6) note


##Installation
Stack is required for building.

```
stack build
stack exec -- process-budget-exe -i FILE.csv -o FILE.csv
```


