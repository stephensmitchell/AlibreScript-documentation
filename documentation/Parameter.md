**Namespace:** `AlibreScript.API` | **Kind:** Class

The Parameter class provides functionality for managing individual parameters including equations, units, Excel linkages, and parameter relationships.

## Related Classes
- [GlobalParameters](GlobalParameters.md) - Parameter collections
- [ParameterTypes](ParameterTypes.md) - Parameter type definitions
- [ParameterUnits](ParameterUnits.md) - Unit definitions
- [Configuration](Configuration.md) - Parameter configurations
- [Part](Part.md), [Assembly](Assembly.md) - Use parameters

## Quick Navigation
- [Properties](Parameter.md#properties) - Parameter attributes and linkages
- [Methods](Parameter.md#methods) - Parameter operations

## Properties

### Comment
Type: `Object`
Comment for the parameter

### Equation
Type: `Object`
Equation of the parameter

### ExcelCell
Type: `Object`
Excel cell associated with the parameter, e.g. '$B$3'

### ExcelSheet
Type: `Object`
Excel sheet associated with the parameter, e.g. 'Sheet1'

### ExcelWorkbook
Type: `Object`
Excel workbook associated with the parameter e.g. 'Foo.xlsx'

### Name
Type: `Object`
Name of the parameter

### RawValue
Type: `Object`
Raw value of the parameter

### Type
Type: `Object`
Type of the parameter

### Units
Type: `Object`
Current units of the parameter

### Value
Type: `Object`
Current value of the parameter in script units (for mm, cm, in), or degrees for angles, or raw value for other units

## Methods


### AttachToExcel

Attaches the parameter to a cell in an Ezcel spreadsheet

```python
def AttachToExcel(document, sheet, cell, units):
"""
Attaches the parameter to a cell in an Ezcel spreadsheet

Args:
document (str): Path and name of Excel spreadsheet
sheet (str): Name of sheet to use
cell (str): Cell to use
units (UnitTypes): Units used in the cell

"""
```
