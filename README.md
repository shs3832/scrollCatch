# How to Use

new scrollCatch(".contents_block", ".nav", {
    button: true,
    easing: "easeOutQuad",
    duration: 600
});

- 컨텐츠 블록 클래스 , 네비게이션 클래스, 버튼 활용시 위와같이 객체형태로 사용
- active 클래스로 on off 조절됨
- 버튼이 있을시 세번째 인자는 객체로 위와같이 보냄
- 버튼사용을 하지않거나 jQuery로 커스터마이징 할경우 비워두어도 상관없음
