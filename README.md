# required_DS



Dicts are now ordered, get used to it
Ivan Sagalaev, February 2020
There were several moments over the last few weeks when I heard people discuss differences between Python lists and dicts and one of the first ones mentioned was that lists are ordered and dicts are not.

Well, not anymore. Quoting the docs referenced above:

Changed in version 3.7: Dictionary order is guaranteed to be insertion order. This behavior was an implementation detail of CPython from 3.6.

So if you want to discuss fundamental differences you can pretty much only point out that dict values are accessible by keys, which could be of any immutable type, while list values are indexed with integers. That's it :-)


