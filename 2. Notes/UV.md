Created: 2025-02-01 11:18 

--- 
Note:
uv to nowoczesny, ultralekki i szybki menedżer pakietów dla Pythona, który jest alternatywą dla pip i virtualenv. Jest rozwijany przez twórców pipenv i pdm i wyróżnia się wysoką wydajnością dzięki implementacji w Rust.

Kluczowe cechy uv:

✅ Szybkość – działa znacznie szybciej niż pip, zwłaszcza przy instalacji wielu pakietów.
✅ Efektywność – lepiej zarządza zależnościami, minimalizując konflikty.
✅ Samodzielność – działa niezależnie od Pythona, nie wymaga środowisk wirtualnych.
✅ Kompatybilność – może współpracować z pip, requirements.txt i pyproject.toml.

**Commands**
```shell
uv  # lista wszystkich opcji
uv init # tworzy podstawową sktrukturę projektu (bez tworzenia virtual env)
uv run # run a script uv run examples.py
uv run --with requests example.py  # uruchomienie scryptu z instalacją tymczasową paczki

```



--- 
Metadata: 

Status: #pending 
Tags: #pip #virtualenv #python_projects