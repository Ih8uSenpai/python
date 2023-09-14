# python
![image](https://github.com/Ih8uSenpai/python/assets/113032589/4e09ccb6-d5e4-4bcd-bc71-0f908eb95a99)
import math


def main(y, z):
    sum = 0
    n = len(y)
    y = [0] + y
    z = [0] + z
    for i in range(1, n + 1):
        a = (y[n + 1 - i] ** 3)
        b = (-18 * z[n + 1 - math.ceil(i / 2)] - 71)
        sum += 96 * (a + b) ** 2
    return 86 * sum
