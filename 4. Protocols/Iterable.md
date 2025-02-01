Created: 2025-02-01 15:08 

--- 
Note:
Metoda specjalna *`__iter__`* musi zwrócić obiekt iteratora. Istnieje alternatywna implementacja tego protokołu *`__getitem__`* ale dla niego *isistance(obiekt, Iterable)* daje false 

**Commands**

```python

def __iter__(self):
	for item in self._items:
		yield item * 2

```
--- 
Metadata: 

Status: #pending 
Tags: #empty