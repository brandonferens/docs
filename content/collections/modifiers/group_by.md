---
types:
  - array
id: a070fabe-c413-4b31-9cb4-ad14bbe1aa4d
---
Format a number with grouped thousands and decimal points. In other words, make it look nice.  

- Parameter 1: precision (number of decimal places before rounding)
- Parameter 2: Decimal point (default `.`)
- Parameter 3: Thousands separator (default: `,`)

```.language-yaml
lucky_number: 130134.109
```

```
{{ lucky_number number_format="1|,|," }}
```

```.language-output
130,134,1
```