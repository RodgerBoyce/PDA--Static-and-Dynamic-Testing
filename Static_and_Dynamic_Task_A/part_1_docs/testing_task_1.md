### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1:
# Error 1: Should use a double equal sign for comparison to check value
      return True
    else
#Error 2: should have : after else
      return False
   

  dif highest_card(self, card1 card2):
# Error 3: Typo in the method name, it should be "def" instead of "dif"
# Error 4: Missing a comma to separate parameters card1 and card2
  if card1.value > card2.value:
    return card
# Error 5: Should return card1
  else:
    return card2


def cards_total(self, cards):
  total
# Error 6: Should set total to 0
  for card in cards:
    total += card.value
    return "You have a total of" + total
# Error 7: Return should be outside of the loop
# Error 8: Needs to convert the int into a string 
  
```
