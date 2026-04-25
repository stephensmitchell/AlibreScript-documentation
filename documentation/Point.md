**Namespace:** `AlibreScript.API` | **Kind:** Class

The Point class provides fundamental functionality for creating and manipulating 3D point geometry throughout the AlibreScript API.

## Related Classes
- [IPoint](IPoint.md) - Point interface definition
- [SketchPoint](SketchPoint.md) - 2D sketch points
- [SketchPoint3D](SketchPoint3D.md) - 3D sketch points
- [PolylinePoint](PolylinePoint.md) - Polyline points
- [Axis](Axis.md), [Plane](Plane.md) - Related geometric elements

## Quick Navigation
- [Properties](Point.md#properties) - Point coordinates and attributes
- [Methods](Point.md#methods) - Point operations

## Properties

### Name
Type: `Object`
Name of the point

### X
Type: `Object`
Point X coordinate

### Y
Type: `Object`
Point Y coordinate

### Z
Type: `Object`
Point Z coordinate

## Methods

### GetCoordinates
Gets the coordiates of the point as a list [X, Y, Z]

```python
Object GetCoordinates()
```

### GetPart
Gets the part that the point is defined in

```python
Object GetPart()
```

### GetSelectionAssembly
The assembly that the edge was selected on
Only valid when a selection has been made

```python
Object GetSelectionAssembly()
```

### Hide
Hides the point

```python
Object Hide()
```

### Show
Shows the point

```python
Object Show()
```
