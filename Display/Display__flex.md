## display: flex

Flex로 레이아웃을 만들기 위한 기본적인 HTML 구조는 아래와 같다.

```html
<div class="container"> 
	<div class="item">helloflex</div> 
	<div class="item">abc</div> 
	<div class="item">helloflex</div> 
</div>
```

![[Pasted image 20231021041556.png]]


이 때 container 안에 있는 div 요소들을 마치 inline 요소들처럼 가로 방향으로 배치하고 
container의 높이도 요소들의 높이만큼 늘어나도록 설정하고 싶다면 display:flex를 사용한다.

Flex 아이템들은 가로 방향으로 배치되고, 자신이 가진 내용물의 width 만큼만 차지한다.
이렇게 height가 알아서 늘어나는 특징은 컬럼 레이아웃을 만들 때 아주 편리하다.

```css
.container {
	display: flex;
}
```

![](https://studiomeal.com/wp-content/uploads/2020/01/03.jpg)


## flex에 대해서 좀 더 알고싶다면?
1.[[Flex-direction (배치방향 설정)]]
2.[[Flex-wrap(줄넘김 처리 설정)]]
3.[[Flex-flow (배치방향, 줄넘김 설정을 한번에)]]
4.[[Justify-content(메인축방향 정렬)]]
5.[[Aline-items(수직축방향 정렬)]]



