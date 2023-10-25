## display: gird

Flex는 한 방향 레이아웃 시스템인 반면에 (1차원)
Grid는 두 방향(가로-세로) 레이아웃 시스템이다. (2차원) 

![[Pasted image 20231021044833.png]]


그리드 레이아웃을 만들기 위한 기본적인 HTML 구조는 아래와 같다.

```html
<div class="container">
	<div class="item">A</div> 
	<div class="item">B</div>
	<div class="item">C</div>
	<div class="item">D</div> 
	<div class="item">E</div> 
	<div class="item">F</div> 
	<div class="item">G</div> 
	<div class="item">H</div> 
	<div class="item">I</div> 
</div>
```

flex 속성과 마찬가지로 display:grid를 설정하는 것으로 시작한다.

```css
.container {
	display: grid; 
}
```


## 그리드 형태 정의  
컨테이너에 Grid의 트랙의 크기를 정해주는 속성들은 아래와 같다.
grid-template-rows   (행배치)
grid-template-columns (열배치)

```css
.container {
	grid-template-columns: 200px 200px 500px; 
	/* grid-template-columns: 1fr 1fr 1fr */ 
	/* grid-template-columns: repeat(3, 1fr) */ 
	/* grid-template-columns: 200px 1fr */ 
	/* grid-template-columns: 100px 200px auto */

	grid-template-rows: 200px 200px 500px; 
	/* grid-template-rows: 1fr 1fr 1fr */
	/* grid-template-rows: repeat(3, 1fr) */
	/* grid-template-rows: 200px 1fr */ 
	/* grid-template-rows: 100px 200px auto */ 
}
```

위와 같이 설정하면 아래의 이미지와 같이 
3x3 형태에 1,2번째 column에오는 row들은 가로,세로 200px에 
3번째 column에 오는 row들은 가로,세로 500px인 표 모양 형태의 그리드가 생성된다.
![[Pasted image 20231021050422.png]]

