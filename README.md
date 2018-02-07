# tipnote
This is my personal record for understanding about computer

## Get Start with git

### Make a local repository
`clone` - `CMD` - `mkdir` - `git clone URL`

### Use mark down
- it support imoji!! :laughing: :zap:
- Use underscore by `\` `\__underscore\__`
- If you want new line end a line with two or more spaces

## Python
[Python_record](https://github.com/audrl1010/Python)

```python
def fib(n):
    if n == 1 or n == 2:
        return 1
    else:
        return fib(n-1) + fib(n-2)

k = int(input("입력하시오:"))
result = 0
for n in range(1,k+1):
    a = fib(n)
    if a % 2 == 0:
        result += fib(n)
    else:continue
print(result)

a, b = 1, 1
total = 0
while a <= 4000000:
    if a % 2 == 0:
        total += a
    a, b = b, a+b  # the real formula for Fibonacci sequence
print(total)
```

## Memo

- what's TDD?
- AR WD