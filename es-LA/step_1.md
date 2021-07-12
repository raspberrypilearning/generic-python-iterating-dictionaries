Como en cualquier estructura de datos en Python, puedes iterar sobre diccionarios.

- Recuerda que el orden de las llaves en un diccionario puede ser impredecible.

- Si simplemente iteras sobre un diccionario con un bucle `for`, solo estarás iterando sobre las llaves.

Toma este diccionario como ejemplo:

```python
banda = {
  'john': 'guitarra rítmica',
  'paul': 'guitarra base',
  'george': 'guitarra solista',
  'ringo': 'bajo'
}
```

- Puedes iterar sobre él con un bucle `for` como este:

```python
for miembro in banda:
  print(miembro)
```

  Esto producirá:

```python
>>> ringo
john
george
paul
```

- Si deseas obtener las llaves y los valores, deberás especificar esto en tu bucle `for`

```python
for miembro, instrumento in elementos.banda():
  print(miembro, '-', instrumento)
```


    Esto resultará en lo siguiente:

```python
>>> ringo - guitarra base
john - guitarra rítmica
george - guitarra solista
paul - guitarra base
```
