# typing 包使用练习

练习题 1：

编写一个函数 calculate_sum，接受两个整数参数 a 和 b，并返回它们的和。

练习题 2：

编写一个函数 is_palindrome，接受一个字符串参数 text，判断该字符串是否为回文字符串（正序和倒序相同），并返回布尔值。

练习题 3：

编写一个函数 get_average，接受一个整数列表参数 numbers，计算列表中所有整数的平均值，并返回结果作为浮点数。

对于每个练习题，您需要使用typing包添加类型注解，并确保代码通过类型检查

## 练习脚本

```python
def calculate_sum(a:int,b:int) -> int:
    return a + b
```

```python
def is_palindrome(text:str) -> bool:
    text == text[::-1]
```

```python
from typing from List
def get_average(numbers:List[int]) -> float:
    return sum(numbers)/len(numbers)

```
