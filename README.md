# Interview HW

## Problem 1: Implement function ToLowerCase() that has a string parameter str, and returns the same string in lowercase.

```
class Solution:
    def toLowerCase(self, str: str) -> str:
        return str.lower()
```        
        
## Problem 2 : You're given strings J representing the types of stones that are jewels, and S representing the stones you have.  Each character in S is a type of stone you have.  You want to know how many of the stones you have are also jewels.The letters in J are guaranteed distinct, and all characters in J and S are letters. Letters are case sensitive, so "a" is considered a different type of stone from "A".
```
class Solution:
    def numJewelsInStones(self, J: str, S: str) -> int:
        numofchars = 0
        for chars in S:
            if chars in J:
                numofchars += 1
        return numofchars    
``` 
