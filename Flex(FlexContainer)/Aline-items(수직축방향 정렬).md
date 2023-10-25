**“justify”** 는 메인축 방향으로 정렬을 의미하고
**“align”**은 수직축방향으로 정렬을 의미한다

![[Pasted image 20231021041902.png]]
aline-item는 기본적으로 아래와 같은 설정값을 넣어줄 수 있다.

```css
.container { align-items: stretch; 
	/* align-items: flex-start; */ 
	/* align-items: flex-end; */ 
	/* align-items: center; */ 
	/* align-items: baseline; */ 
}
```

### 1. stretch (기본값)

아이템들이 수직축 방향으로 끝까지 쭈욱 늘어난다.
![[Pasted image 20231021043630.png]]

### 2. flex-start

아이템들을 시작점으로 정렬한다.
flex-direction이 row(가로 배치)일 때는 위, column(세로 배치)일 때는 왼쪽이다.
![[Pasted image 20231021043721.png]]

### 3. flex-end
아이템들을 끝으로 정렬한다
flex-direction이 row(가로 배치)일 때는 아래, column(세로 배치)일 때는 오른쪽이다.
![[Pasted image 20231021043815.png]]

### 4. center
아이템들을 가운데로 정렬한다.
![[Pasted image 20231021043903.png]]

