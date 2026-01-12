# Mermaid tasks

## Mobile OS pie chart
```mermaid
pie title Market Share of Mobile OS
    "Android" : 71
    "IOS" : 27
    "Other" : 2
```

## Fizzbuzz
```mermaid
flowchart LR
    A[Enter Number] --> B{Divisible by 3 and 5?}
    B -->|no| C{Divisible by 3?}
    B -->|yes| E[Fizzbuzz]
    C -->|yes| F[buzz]
    C -->|no| D{Divisible by 5?}
    D -->|yes| G[fizz]
    D -->|no| H[print number]
```
