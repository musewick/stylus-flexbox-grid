# Stylus Flexbox Grid

Customizable grid for web pages based on flexbox and written in stylus

## Getting started

### Usage

### Configuration

Touch `config.styl` in root with content

```
grid = {
  //output css class name
  name: 'grid',
  columns: 12,
  gutters: {
    column: 30px,
    row: 0
  },
  //precision of output values
  precision: 4,
  breakpoints: {
      t: 0,
      xs: 375px,
      sm: 480px,
      md: 850px,
      lg: 1200px,
      xlg: 1440px
  },
}
```

### Tasks

- [x] Configuration file
- [ ] Defalut config inside grid
- [ ] Media query min-witdth\max-width option in settings

---

Generate functions based on fork [s-grid](https://github.com/juliancwirko/s-grid)
