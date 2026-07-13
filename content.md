When importing from a module or package in Python, we have a few options of how to import and use content from that module or package. Which one is best to use depends on the specific use case and coding style preferences. In this page, we'll use the `pi` value from the `math` module as an example to illustrate different import methods.

# Import Entire Module

We can import an entire module, and then access its contents using the module name as a prefix. For example:

```pycell
import math
print(math.pi)
```

# Import Specific Elements

We can import specific elements from a module, which allows us to use them directly without the module name prefix. For example:

```pycell
from math import pi
print(pi)
```

# Import with an Alias

We can import an entire module and give them an alias, which can be useful for shortening long module names or avoiding naming conflicts. For example:

```pycell
import math as m
print(m.pi)
```

We can also import specific elements with an alias:

```pycell
from math import pi as p
print(p)
```

# Import All Elements

We can also import all elements from a module using the `*` wildcard. However, this is generally discouraged as it can lead to naming conflicts and make the code less readable. For example:

```pycell
from math import *
print(pi)
```