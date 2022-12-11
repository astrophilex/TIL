# JavaScript04

## 프로그램의 작성법과 실행법

---

### 간단한 예제

팩토리얼을 계산하고 표시하기

```javascript
function fact(n){
    if(n<=1) return n;
    return n*fact(n-1);
}
for(var i=1; i<10;i++){
    cnosole.log(i+"!="+fact(i));
}
```