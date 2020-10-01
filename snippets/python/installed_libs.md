---
title: Python installed libraries
tags: pip,python
---

Fetch runtime python version
- `pip` built in module help managing the installed packages.

```python
import pip

# Code snippet
installed_packages = pip.get_installed_distributions()
installed_packages_list = sorted(["%s==%s" % (i.key, i.version)
     for i in installed_packages])
print(installed_packages_list)

# From the python command prompt
>>> pip freeze
```

