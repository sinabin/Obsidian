## display-block

block은 inine과 반대되는 성질을 갖고 있다.  
**block 요소의 의미는, 이 요소 바로 옆(좌우측)에 다른 요소를 붙여넣을 수 없다는 뜻이다.**  
따라서 display 속성이 block으로 지정된 엘리먼트는 전후 줄바꿈이 들어가 다른 엘리먼트들을 다른 줄로 밀어내고 혼자 한 줄을 차지한다.

대부분의 HTML element(이하 요소)는 block 요소로, header, footer, p, li, table, div, h1 등이 있다.

block 엘리먼트는 inline 엘리먼트와 달리 width, height, margin, padding 속성이 모두 반영이 된다.

ex)  
html

```null
 <h1>H1</h1>
 <div>DIV</div>
 <p>P</p>
```

css

```null
div {
  background: yellow;
  width: 200px;
  height: 50px;
  margin: 20px;
  padding: 10px;
}
```

코드의 결과는 다음과 같다.  
![](https://velog.velcdn.com/images%2Fhoje15v%2Fpost%2F81136fc4-7e3b-4a2b-a280-77da812f2a64%2Fblock.png)

각 block 엘레멘트들은 자동적으로 한 줄 씩 차지하고, 배경색 또한 한 줄 전체를 채운다.