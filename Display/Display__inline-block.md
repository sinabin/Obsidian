display 속성이 inline-block으로 지정된 엘리먼트는 기본적으로 **inline 엘리먼트처럼 한 줄에 다른 엘리먼트들과 배치**된다. 하지만 inline 엘리먼트에서 불가능하던 
**width와 height 속성 지정 및 margin과 padding 속성의 상하 간격 지정이 가능**해진다.  
👉 즉 inline의 성질을 가지면서 동시에 사용자가 원하는 대로 모형을 꾸밀 수 있다.

button, input, select 태그 등이 대표적인 inine-block elment이다.

inline-block 엘리먼트는 명시적으로 해당 엘리먼트의 스타일을 display: inline-block로 지정해주어야 한다.

ex)
```null
span {
  display: inline-block;
  background: yellow;
  width: 200px;
  height: 50px;
  margin: 20px;
  padding: 10px;
}
```

![](https://velog.velcdn.com/images%2Fhoje15v%2Fpost%2Fc3a9d07c-0800-469a-b4a2-10732de0a8c6%2Finline-block.png)

inline 의 성질을 갖고 있으면서도 margin등이 적용된 것을 볼 수 있다.