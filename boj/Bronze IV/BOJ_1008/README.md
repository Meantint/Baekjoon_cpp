# BOJ_1008 - A/B

&nbsp;기본적인 나눗셈...이지만 불안해서 소수점 고정함.

- Baekjoon - [A/B](https://www.acmicpc.net/problem/1008)

- My Baekjoon Code : [https://github.com/Meantint/Baekjoon](https://github.com/Meantint/Baekjoon)

## 풀이

- `cout << fixed`와 `cout.precision(9)`으로 소수점 9자리까지 고정 표현시킨다.

## Code

```cpp
#include <iostream>

using namespace std;

double a, b;

int main()
{
    cin >> a >> b;

    cout << fixed;
    cout.precision(9);
    cout << a / b << '\n';

    return 0;
}
```