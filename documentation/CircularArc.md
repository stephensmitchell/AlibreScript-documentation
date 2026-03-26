**[[Home]] | [[Classes]] | [[Methods-Index|Methods]] | [[Properties-Index|Properties]] | [[Members-Index|Members]]**

**Location:** [[Classes#geometry|Geometry & Shapes]] CircularArc

**Namespace:** `AlibreScript.API` | **Kind:** Class

The CircularArc class provides functionality for creating and manipulating circular arc geometry within 2D sketches.

## Related Classes
- [[CircularArc3D]] - 3D circular arcs
- [[CircularArc.ArcType]] - Arc type definitions
- [[Circle]] - Full circular geometry
- [[Sketch]] - Contains arc geometry
- [[EllipticalArc]] - Elliptical arc geometry

## Quick Navigation
- [[CircularArc#properties|Properties]] - Arc properties and dimensions
- [[CircularArc#methods|Methods]] - Available operations

## Properties

### Angle
Type: `Object`
Angle of arc

### Center
Type: `Object`
The center of the arc [x, y]

### CenterPoint
Type: `Object`
The center point as a sketchpoint object

### End
Type: `Object`
The end point as a sketchpoint object

### EndPoint
Type: `Object`
The end point of the arc [x, y]

### IsReference
Type: `Object`
True if the arc is a reference arc, false if it is a regular arc

### Radius
Type: `Object`
Radius of arc

### Start
Type: `Object`
The start point as a sketchpoint object

### StartPoint
Type: `Object`
The start point of the arc [x, y]

### Type
Type: `Object`
Type of arc

## Methods


### CircularArc

Creates an arc using the center, start point and end point

**Overload 1:**

```python
def CircularArc(center, start, end, is_reference):
"""
Creates an arc using the center, start point and end point

Args:
center (list): Center of the arc
start (list): Start point of the arc
end (list): End point of the arc
is_reference (bool): True to create a reference arc, false to create a regular arc

"""
```

**Overload 2:**

```python
def CircularArc(center, start, angle, is_reference):
"""
Creates an arc using the center, start point and an angle

Args:
center (list): Location of center of arc
start (list): Location of start of arc
angle (float): Angle of arc
is_reference (bool): True if a reference arc, false if a regular arc

"""
```

---
**[[CircularArc#circulararc|⬆ Back to Top]]**
