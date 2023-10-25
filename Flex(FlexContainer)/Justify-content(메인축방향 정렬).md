**“justify”** 는 메인축 방향으로 정렬을 의미하고
**“align”**은 수직축방향으로 정렬을 의미한다

![[Pasted image 20231021041902.png]]
justify-content는 기본적으로 아래와 같은 설정값을 넣어줄 수 있다.
```
.container { 
	justify-content: flex-start; 
	/* justify-content: flex-end; */ 
	/* justify-content: center; */ 
	/* justify-content: space-between; */ 
```

### 1. flex-start (기본값)
아이템들을 메인축의 시작점으로 정렬한다.  
![[Pasted image 20231021042952.png]]

### 2. flex-end
아이템들을 끝점으로 정렬한다.
![[Pasted image 20231021043028.png]]

### 3. center
아이템들을 가운데로 정렬한다.
![[Pasted image 20231021043109.png]]

### 4. space-between
아이템들의 “사이(between)”에 균일한 간격을 만들어 준다
![[Pasted image 20231021043152.png]]