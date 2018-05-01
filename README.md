# fleXtable

A tiny library for the display of huge tables on mobile devices.

## Project status

**fleXtable is beta and still in developpement.**

Although this version is stable, you may encounter bugs.

## Usage

For now, the library can only use tables id.

``` javascript
fleXtable ( string $tableId, array $columnsToMask, string $windowSize [, bool $debugMode ]);
```

* $tableId: the id of the table;
* $columnsToMask: the number of one or several columns to mask.; 
* maximum width for trigger: if screen width is less than equal to this value fleXtable is triggered;
* debug mode (optional): if set to true, will add different background colors to .

You can find a full [demo here](https://codepen.io/alexisr/pen/e168105c29f9fc8950a4e1150b35c9a3). More details on [my blog](https://alx.design).

## Next features

### 1.0

- fleXtable will be able to use classes to designate multiple tables.
- Automatic detection of a horizontal scroll bar in the wrapper, which will no longer require to indicate a break size when using fleXtable.