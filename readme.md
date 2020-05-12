# CodeWars Solutions

This Repo is a solution of problems solved by me in the [CodeWars](https://www.codewars.com/) platform. Most of the codes are written in JavaScript.

## Solutions Index

| Problem                 | Description                                                                                                                                                                                                                                                                                                                                                 |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ArrayDiff](#arraydiff) | Your goal in this kata is to implement a difference function, which subtracts one list from another and returns the result. It should remove all values from list a, which are present in list b. `arrayDiff([1, 2], [1]) == [2];` If a value is present in b, all of its occurrences must be removed from the other: `arrayDiff([1,2,2,2,3],[2]) == [1,3]` |

## Solutions

### 1. ArrayDiff

```javascript
const arrayDiff = (a, b) => {
  return a.filter((n) => !b.includes(n));
};
```
