# BMS Reference
BMS Error reference for dashboard

## What are these files?

### BMSErrorList
`BMSErrorList.json` is the database of BMS Errors

## How to use them?

#### Install
```bash
npm install --save-dev git+ssh://git@github.com/ampd-energy/pcs-reference.git
```

#### Import
```javascript
  // importing the whole as one object
  import BMSRef from 'bms-reference'

  // of course you can also do this if you want to direcly reference individual object
  import { list } from 'bms-reference'
```
