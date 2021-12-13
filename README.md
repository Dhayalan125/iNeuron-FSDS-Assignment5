# iNeuron-FSDS-Assignment5

1. What does an empty dictionary's code look like?

Ans: {}

2. What is the value of a dictionary value with the key 'foo' and the value 42?

Ans: 42

3. What is the most significant distinction between a dictionary and a list?

Ans: A list is an ordered sequence of objects, whereas dictionaries are unordered sets. However, the main difference is that items in dictionaries are accessed via keys and not via their position. Dictionaries don't support the sequence operation of the sequence data types like strings, tuples and lists.

4. What happens if you try to access spam['foo'] if spam is {'bar': 100}?

Ans: KeyError: 'foo'

5. If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.keys()?

Ans: There is no difference. The in operator checks whether a value exists as a key in the dictionary. 'cat' in spam checks whether there is a 'cat' key in the dictionary, while 'cat' in spam. values() checks whether there is a value 'cat' for one of the keys in spam .

6. If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.values()?

Ans: There is no difference. The in operator checks whether a value exists as a key in the dictionary. 'cat' in spam checks whether there is a 'cat' key in the dictionary, while 'cat' in spam. values() checks whether there is a value 'cat' for one of the keys in spam .

7. What is a shortcut for the following code?
if 'color' not in spam:
spam['color'] = 'black'

Ans: spam.setdefault('color', 'black')

8. How do you "pretty print" dictionary values using which module and function?

Ans: pprint
This module also supports pretty-printing dictionary. Within the pprint module there is a function with the same name pprint() , which is the function used to pretty-print the given string or object.
