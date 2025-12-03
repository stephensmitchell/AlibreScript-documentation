# Configuration

**[[Home]] | [[Classes]] | [[Methods-Index|Methods]] | [[Properties-Index|Properties]] | [[Members-Index|Members]]**

** Location:**[[Classes#configuration|Configuration & Parameters]] Configuration

**Namespace:** `AlibreScript.API` | **Kind:** Class

The Configuration class provides functionality for managing part and assembly configurations, including activation state and configuration locks.

## Related Classes
- [[Part]] - Contains configurations
- [[Assembly]] - Assembly configurations
- [[GlobalParameters]] - Configuration parameters
- [[LockTypes]] - Lock type definitions
- [[Parameter]] - Configuration parameters

## Quick Navigation
- [[Configuration#properties|Properties]] - Configuration state and identity
- [[Configuration#methods|Methods]] - Configuration operations

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

---
**[[Configuration#configuration|⬆ Back to Top]]**
