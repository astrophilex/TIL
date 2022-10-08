# Coding-Test-JavaScript

> programmers
> 

정답 / 오답

---

## JavaScript lv.0

정수 `num1` 과 `num2`가 주어질 때, `num1`에서 `num2`를 뺀 값을 return하도록 soltuion 함수를 완성해주세요.

```jsx
using System;

public class Solution {
    public int solution(int num1, int num2) {
        int answer = num1-num2;
        return answer;
    }
}
```

## JavaScript lv.0

정수 `num1`, `num2`가 매개변수로 주어질 때, `num1`를 `num2`로 나눈 나머지를 return 하도록 solution 함수를 완성해주세요.

```jsx
using System;

public class Solution {
    public int solution(int num1, int num2) {
        int answer = num1%num2;
        return answer;
    }
}
```

## JavaScript lv.0

정수 `num1`, `num2`가 매개변수로 주어질 때, `num1`를 `num2`로 나눈 값을 return 하도록 solution 함수를 완성해주세요.

```jsx
using System;

public class Solution {
    public int solution(int num1, int num2) {
        int answer = num1/num2;
        return answer;
    }
}
```

## JavaScript lv.0

정수 `n`이 매개변수로 주어질 때, `n`이하의 홀수가 오름차순으로 담긴 배열을 return하도록 solution 함수를 완성해주세요.

```jsx
function solution(n) {
    const answer = []
    for(let i = 1; i <= n; i++){
        if(i % 2 !== 0){
            answer.push(i)
        }
    }
    return answer;
}
```