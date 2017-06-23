Like any data structure in Python, you can iterate over dictionaries.

Remember, the order of keys in a dictionary can be unpredictable.

If you simply iterate over a dictionary with a `for` loop, you will only be iterating over the keys.

Take this dictionary for example:

	```python
	band = {
		'john' : 'rhythm guitar',
		'paul' : 'base guitar',
		'george' : 'lead guitar',
		'ringo' : 'base guitar'
		}
	```

- You can iterate over it with a `for` loop like this:

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

- If you want to get the keys and values, you'll need to specify this in your `for` loop

	```python
	for member, instrument in band.items():
		print(member, '-', instrument)
	```
	
	This will give the following:
	
	```python
	>>> ringo - base guitar
	john - rhythm guitar
	george - lead guitar
	paul - base guitar
	```
