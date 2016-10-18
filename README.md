Polymer Element: unit-prefix
============================

Converts values between qualtizations of the same units by looking up multiplication factors from a table.

Installation
------------

```bash
bower install polymer-unit-convert
```

Supported Unit Quantizations
----------------------------

- pico
- nano
- micro
- milli
- centi
- deci
- deca
- hecto
- kilo
- mega
- giga
- terra

Examples
--------

### Distances

```html
<unit-prefix value="500" from="meter" to="kilometer" result="{{result}}" />
<!-- result: 0.5 -->
```

```html
<unit-prefix value="500" from="decimeter" to="millimeter" result="{{result}}" />
<!-- result: 1000 -->
```

### Time

```html
<unit-prefix value="60" from="minute" to="hour" result="{{result}}" />
<!-- result: 1 -->
```
