# 2022-12-28

## VO와 Map의 차이

---

> Map
> 

```java
Map<String, Integer> param = new HashMap<String, Integer>();
param.put("num", 1)
param.put("num2", 5)
```

> VO
> 

```java
public class TestVO {
    private Integer num;
    private Integer num2;
}
 
TestVO param = new TestVO ();
param.setNum(1);
param.setNum2(5);
```

Map은 변수명을 바꾸면서 put을 계속할 수 있음

반면에 VO는 지정한 변수에만 set 할 수 있음

따라서 Map 같은 경우에는 DB에 null 값이 들어갈 일이 없지만 VO는 set을 해주지 않는다면 key에 null 값이 들어갈 수가 있음

<aside>
💡 Map이 더 효율적으로 보이지만 Map은 오류가 생겼을 때 어느 부분에서 오류가 생겼는지 확인하기 어려운 단점이 있었음. 변수 값의 변동이 없는 경우는 VO가 더 안정적이라고 생각함.

따라서 유지보수 측면에서는 VO, 변수 값이 자주 변동되는 경우에는 Map이 나은 거 같다.

</aside>