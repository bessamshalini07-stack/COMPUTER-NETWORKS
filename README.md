# Python Break and Continue Statements

## 1. Break Statement

The `break` statement is used to stop a loop immediately when a particular condition is satisfied.

### Syntax
```python
for i in range(1, 10):
    if i == 5:
        break
    print(i)
```

### Output
```text
1
2
3
4
```

**Explanation:**
- The loop starts from 1.
- When `i` becomes 5, the break statement executes.
- The loop stops immediately.

## 2. Continue Statement

The `continue` statement is used to skip the current iteration and move to the next iteration of the loop.

### Syntax
```python
for i in range(1, 6):
    if i == 3:
       continue
    print(i)
```

### Output
```text
1
2
4
5
```

**Explanation:**
- The loop starts from 1.
- When `i` becomes 3, continue skips that iteration.
- The loop continues with 4 and 5.

## 3. Difference Between Break and Continue

| Break | Continue |
|---|---|
| Stops the entire loop. | Skips the current iteration. |
| Control moves outside the loop. | Control moves to the next iteration. |
| Used to terminate a loop. | Used to skip specific values. |

## 4. Real-Life Examples

**Break:** Stop searching when you find the required item.

**Continue:** Skip unavailable items and check the remaining items.

## 5. Key Points

- Both statements are used inside loops.
- Break terminates the loop.
- Continue skips the current iteration.
- Both work with `for` and `while` loops.

## Conclusion

Break and continue are important control statements in Python. They help control how loops execute.
