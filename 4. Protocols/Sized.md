Created: 2025-02-01 14:25 

--- 
Note:
Zwraca liczbę elementów *len(sized)*
Nie może zużywać ani modyfikować kolekcji (np. czyli nie może przelecieć po wszystkich next)

**Command**

```python
class X:
	def __len__(self) -> int:
		return 42
x = X()
len(x) == 42


```

--- 
Metadata: 

Status: #pending 
Tags: #empty