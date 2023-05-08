# Python Cheat Sheet
Use this repo as cheat sheet to learn and apply Python concepts.

***

elem. = element(s) | val. = value(s) | pos. = position | dic. = dictionary | # = number(s) |


| Element | Description | Example |
|---------|------------ |---------|
| List | Methods |  |
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
| --- | --- | --- |
| Tuples | Methods |  |
| Tuple () | Are immutable | Accepts duplicate elements |
| count() |	Returns # times a specified val. occurs	|x=tuple.count(5) |
| index() | Searches tuple for specified val.- returns pos.where it was found | x=tuple.index(6) |
| --- | --- | --- |
| Sets | Methods |  |
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

