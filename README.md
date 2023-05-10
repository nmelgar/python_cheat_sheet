# Python Cheat Sheet
Use this repo as cheat sheet to learn and apply Python concepts.

***
<p>Changes are being made to improve it. You can review the google sheet file <a target="_blank" href="https://docs.google.com/spreadsheets/d/15OsctDhIXPZQIy7XZf5fmtCWbniwCRHD3kmmxfda_sE/edit?usp=sharing">here</a>. Feel free to contact me with suggestions.</p>

***
## Elements covered in this cheat sheet

<ul>
    <a href="#list-methods"><li>List Methods</li></a>
    <a href="#tuple-methods"><li>Tuple Methods</li></a>
    <a href="#set-methods"><li>Set Methods</li></a>
    <a href="#dictionary-methods"><li>Dictionary Methods</li></a>
    <a href="#string-methods"><li>String Methods</li></a>
    <a href="#file-methods"><li>File Methods</li></a>
    <a href="#builtin-functions"><li>Built-in Functions</li></a>
    
</ul>

***

elem. = element(s) | val. = value(s) | pos. = position | dic. = dictionary | # = number(s) |

***

**Lists**
| Element | Description | Example |
|---------|------------ |---------|
| <span id="list-methods">**Lists**</span> | Methods |  |
| List [ ] | Are mutable | Accepts duplicate elements |
|append() | Adds to end list | list.append('dog') |
|clear()| Removes all | list.clear() |
|copy()| Returns copy of list | x=list.copy() |
|count()| Returns # of elems. specified val. | x=list.count('dog') |
|extend()| Add elem. of list (or any iterable), to end of  current list | list.extend(list2) |
| index() | Returns index of first elem. with specified val. | x=list.index('dog') |
| insert() | Adds elem. at specified pos. | list.insert(1, 'cat') |
|pop() | Removes elems. at specified pos. | list.pop(1) |
|remove() | Removes item with specified val. | list.remove('dog') |
|reverse() | Reverses order of list	| list.reverse() |
|sort() | Sorts list | list.sort() |

**Tuples**
| Element | Description | Example |
|---------|------------ |---------|
| <span id="tuple-methods">**Tuples**</span> | Methods |  |
| Tuple () | Are immutable | Accepts duplicate elements |
| count() |	Returns # times a specified val. occurs	|x=tuple.count(5) |
| index() | Searches tuple for specified val.- returns pos.where it was found | x=tuple.index(6) |

**Sets**
| Element | Description | Example |
|---------|------------ |---------|
| <span id="set-methods">**Sets**</span> | Methods |  |
| Sets {} | No mutable | Doesn't accept duplicate elements |
| add() | Adds an elems. | set.add('dog') |
| clear() |	Removes all elems. | fruits.clear() |
| copy() | Returns copy of set | x=fruits.copy() |
| difference() | Returns set containing difference between 2 or more sets | z=x.difference(y) |
| difference_update() | Removes items in this set that are also included in another, specified set | x.difference_update(y) |
| disdicd() | Remove specified item	| fruits.disdicd('dog') |
| intersection() | Returns a set, that is intersection of two or sets | z=x.intersection(y) |
| intersection_update() | Removes items that are not present in or, specified set(s) | x.intersection_update(y) |
| isdisjoint() | Returns whether 2 sets have a intersection or not | z=x.isdisjoint(y) |
| issubset() | Returns wher another set contains this set or not | z=x.issubset(y) |
| issuperset() | Returns whether this set contains another set or not |	z=x.issuperset(y) |
| pop() | Removes an elem. from set | fruits.pop() |
| remove() | Removes specified elems. | fruits.remove('dog') |
| symmetric_difference() | Returns set with symmetric differences of two sets | z=x.symmetric_difference(y) |
| symmetric_difference_update() | inserts symmetric differences from this set and another | x.symmetric_difference_update(y) |
| union() | Return a set containing union of sets | z=x.union(y) |
| update() | Update set with union of this set and others |	x.update(y) |

**Dictionaries**
| Element | Description | Example |
|---------|------------ |---------|
| <span id="dictionary-methods"> **Dictionaries**</span> | Methods |  |
| dicts {key: value} | Are mutable | Not duplicate keys allowed |
| clear() | Removes all  elems. from  dic. | dic.clear() |
| copy() | Returns a copy of  dictionary | x=dic.copy() |
| fromkeys() | Returns a dictionary with specified keys and val. | thisdict = dict.fromkeys(x, y) |
| get() | Returns val. of specified key	| x=dic.get("name") |
| items() | Returns a list containing a tuple for each key val. pair | x=dic.items() |
| keys() | Returns a list containing  dictionary's keys	| x=dic.keys() |
| pop() | Removes elems. with specified key	| dic.pop("name") |
| popitem() | Removes last inserted key-val. pair | dic.popitem() |
| setdefault() | Returns val. of specified key. If key does not exist: insert  key, with  specified val. | x=dic.setdefault("name", "Jun") |
| update() | Updates dictionary with specified key-val. pairs | dic.update({"age": "3"}) |
| values() | Returns a list of all vals in  dictionary | x=dic.values() |

**Strings**
| Element | Description | Example |
|---------|------------ |---------|
| <span id="string-methods"> **Strings**</span> | Methods |  |

**Files**
| Element | Description | Example |
|---------|------------ |---------|
| <span id="file-methods"> **Files**</span> | Methods |  |

**Built-in Functions**
| Element | Description | Example |
|---------|------------ |---------|
| <span id="#builtin-functions"> **Built-in Functions**</span> |  |  |

***

## Author
---
* Nefi Melgar (nefimelgarg@gmail.com)