---
date_created: "2026-10-21 15:23"
type:
status:
tags:
---
# Core Python

## Overview 

Core python concepts

---

## Notes & Content

### Strings

```python
message = "Hello {}"

# String formatting. {} used as place holder.
message= message.format("world");

# To count occurence of given arg
print(message.count('world'))

# To print charachter at given index
print(message[2])

# To print characters from given index to but not including the final index
print(message[2:5])

print(message);

# To replace the first argument with second in the given string.
print(message.replace('world','universe'))

# Gives list of available methods and attributes for given object in python.
print(dir(message))

print(help())

```

---
## Related / Links
* Related: