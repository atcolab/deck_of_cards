# Deck of Cards
> Summary description here.


This file will become your README and also the index of your documentation.

## Install

`pip install your_project_name`

## Using Card

Here's how we create a card and test for valid cards!

```python
Card(suit=2, rank=11)
```




    Jack of Hearts



```python
c = Card(suit=1, rank=3)
assert str(c) == '3 of Diamonds'

c2 = Card(suit=2, rank=11)
assert str(c2) == 'Jack of Hearts'
```
