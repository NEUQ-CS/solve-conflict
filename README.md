下面是一段计算1到100的和的代码。

```C
int sum_1_to_100(void)
{
    int sum = 0;

    for (int i = 1; i <= 100; i++)
    {
        sum += i;
    }

    return sum;
}
```