## flex-flow

flex-direction과 flex-wrap을 한꺼번에 지정할 수 있는 단축 속성이다.
flex-direction, flex-wrap의 순으로 한 칸 떼고 써주면된다.

```
.container {
	flex-flow: row wrap;
	/* 아래의 두 줄을 줄여 쓴 것 */
	/* flex-direction: row; */
	/* flex-wrap: wrap; */
}
```