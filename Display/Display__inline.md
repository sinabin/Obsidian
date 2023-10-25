## display: inline
**inline이란 이라는 말 그대로 inline 요소는 요소끼리 서로 한 줄에, 바로 옆에 위치할 수 있다는 뜻이다.**

대표적인 inline 엘리먼트로 span이나 a, em 태그 등을 들 수 있다.
<strong><span style="background-color:fff5b1; color:2D3748">inline 엘리먼트은 width와 height 속성을 지정해도 효과가 적용되지 않는다. </span></strong>
👉 해당 태그가 마크업하고 있는 컨텐츠의 크기 만큼만 공간을 차지하도록 되어 있기 때문이다.

또한, margin과 padding 속성은 좌우 간격만 반영이 되고, 상하 간격은 반영이 되지 않는다.

ex)  
html

```null
<a>A</a>
<span>SPAN</span>
<em>EM</em>
```

css

```null
span {
  background: yellow;
  width: 200px;
  height: 50px;
  margin: 20px;
  padding: 10px;
}
```

위 코드의 결과는 아래와 같다.

![](https://velog.velcdn.com/images%2Fhoje15v%2Fpost%2Fd6afd4c8-872b-4295-891b-08f468cc40a0%2Finine.png)

inline 성질을 가진 세 태그가 한 줄이 나와있는 것을 볼 수 있다. 또한 span의 배경색은 콘텐츠 크기만큼 칠해졌다. width, height의 값들은 무시 되었다.

## inline 과 반대되는 속성 : block
-[[Display__block]]
## inline에서 height, width를 지정하고 싶다면 : inline-block
[[Display__inline-block]]