Like any data structure, you can iterate over dicitonaries. Remember though, the order can be unpredicatable. If you simply iterate over a dicitonary with a `for` loop, then you will only be iterating over the keys.

With the dictionary:

```python
band = {
    'john' : 'rhythm guitar',
    'paul' : 'base guitar',
	'george' : 'lead guitar',
    'ringo' : 'base guitar'
	}
```

You can iterate over it with a `for` loop like this:

```python
for member in band:
    print(member)
```

This will produce:

```python
>>> ringo
john
george
paul
```

If you want to get the keys and values, then you'll need to specifiy this in your `for` loop

```python
for member, instrument in band.items():
    print(member, '-', instrument)
```

```python
>>> ringo - base guitar
john - rhythm guitar
george - lead guitar
paul - base guitar
```
