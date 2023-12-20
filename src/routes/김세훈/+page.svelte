<div id="layer">
  <div id="grid">
    <img src="https://avatars.githubusercontent.com/u/106385007?v=4" alt="사진" />
    <h3>
      안녕하세요. 저는 웹개발 동아리 부장을 맡고있는 김세훈이라고 합니다.
      프로그래밍에 관심이 많으며 이번에 좋은 기회를 가져 다른 친구들이 코딩의
      재미를 느껴볼 수 있게 도와주었습니다. 친구들이 잘 따라오지 못할까봐
      걱정을 많이 했었는데 생각 외로 잘 이해하는 모습을 보여 순탄하게 흘러갔던
      것 같습니다. 정말 시간 가는 줄 모르게 즐거웠던 동아리였습니다.
    </h3>
  </div>
    <h1>Contact</h1>
    <ul>
      <li><a href="https://github.com/cyantr09">GITHUB</a></li>
      <li><a href="https://instagram.com/_cyantree">Instagram</a></li>
      <li><a href="https://toss.me/cyantree">Toss</a></li>
      <li><a href="https://cyantr.vercel.app">My Portfolio</a></li>
    </ul>
</div>

<style>
#layer {
  color: black;
  width: 100vw;
  background:linear-gradient(45deg,skyblue,cyan);
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}
#grid {
  width: 70vw;
  height: 50vh;
  display: grid;
  align-items: center;
  grid-template-columns: 1fr 2fr;
  grid-gap: 2vw;
}
img {
  width: 100%;
}
ul {
  margin-top: 5vh;
  width: 30vw;
  list-style-type: none;
  display: flex;
  justify-content: space-between;
}
a {
  text-decoration: none;
  font-size: 1vw;
}
h3 {
  font-size: 1.5vw;
}
h1 {
  font-size: 3vw;
  text-align: center;
}

</style>