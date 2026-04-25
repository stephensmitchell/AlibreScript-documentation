**Namespace:** `AlibreScript.API` | **Kind:** Class

The Configuration class provides functionality for managing part and assembly configurations, including activation state and configuration locks.

## Related Classes
- [Part](Part.md) - Contains configurations
- [Assembly](Assembly.md) - Assembly configurations
- [GlobalParameters](GlobalParameters.md) - Configuration parameters
- [LockTypes](LockTypes.md) - Lock type definitions
- [Parameter](Parameter.md) - Configuration parameters

## Quick Navigation
- [Properties](Configuration.md#properties) - Configuration state and identity
- [Methods](Configuration.md#methods) - Configuration operations

## Properties

### IsActive
Type: `Object`
True if the configuration is currently active

### Name
Type: `Object`
The name of the configuration

## Methods


### SetLocks

Sets the locks on the configuration

```python
def SetLocks(locks):
"""
Sets the locks on the configuration

Args:
locks (LockTypes): Locks to set

"""
```
