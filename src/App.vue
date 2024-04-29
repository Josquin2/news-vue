<template>
  <div class="container">
    <div class="header">
      <div class="header-logo">Learn</div>
      <div class="header-other">
        <p class="font">React</p>
        <p class="font">Vue</p>
        <p class="font">jQuery</p>
      </div>
      <div class="header-other" style="margin-left: 54vw">
        <p class="font">About</p>
      </div>
    </div>
    <div class="body">
      <div class="left">
        <h4>ON THIS PAGE</h4>
        <div class="on-page-info">
          <p class="common-info">1. You do not talk about fight club</p>
          <p class="common-info">2. You do not talk about fight club</p>
          <p class="common-info">
            3. If someone says stop or goes limp, taps out, the fight is over
          </p>
          <p class="common-info">4. Only two guys to a fight</p>
          <p class="common-info">5. One fight at a time</p>
          <p class="common-info">6. No shirts, no shoes</p>
          <p class="common-info">7. Fights will go on as long as they have to</p>
          <p class="common-info">8. If this is your first night at fight club, you have to fight</p>
        </div>
      </div>
      <div class="middle">
        <h1 class="main-head">Rules</h1>
        <h2 class="head-of-theme">1. You do not talk about fight club</h2>
        <p class="theme-info">
          In fact, rule one's code of silence perpetuated many of Fight Club's complications, and
          the club echoes Tyler Durden himself in this manner. Tyler makes the Narrator promise not
          to talk about him to Marla (Helena Bonham Carter), mirroring the first of the Fight Club
          rules. If the Narrator had talked about Tyler (or Fight Club),​​​​ to Marla or at one of
          his many support groups, Tyler's true identity would have been revealed much sooner.
        </p>
        <p class="theme-info">
          The first rule of Fight Club dictates that members must not discuss the club and should
          maintain the club's secretive nature. This is particularly ironic considering that Tyler
          Durden is a figment of the Narrator's psyche. In deciding rule one, Tyler/the Narrator is
          expressing concern over members speaking to other people, all while he is talking
          exclusively to himself and his second personality.
        </p>
        <h2 class="head-of-theme">2. You do not talk about fight club</h2>
        <p class="theme-info">
          The repetition of rule one is one of the most famous moments from Fight Club. As remarked
          on by Tyler, obviously certain members have broken rules one and two as the attendance has
          swelled considerably. As the club evolved into a political movement, talking about Fight
          Club became necessary, or at least their presence was repeatedly declared through highly
          public acts of domestic terrorism. Following the revelation that the Narrator is Tyler
          Durden, it becomes apparent that the new members the Narrator is jealous of, were actually
          recruited by the Narrator himself, who therefore broke Fight Club rules one and two. 3
        </p>
        <h2 class="head-of-theme">
          3. If someone says stop or goes limp, taps out, the fight is over
        </h2>
        <p class="theme-info">
          The third of the Fight Club rules states that a fight ends when a fighter decides so or is
          unable to continue. It infuses a sense of propriety to the violence and honor among the
          club members, which builds upon the proposition that there's some emotional wisdom or
          mental enlightenment available in the violence. Rule three is broken most notably by the
          Narrator himself when he brutally beats Angel Face (played by Jared Leto) long after he's
          limp because he "wanted to destroy something beautiful." Angel Face is ultimately maimed
          by the fight, and the club members observe their leader break another of his own rules.
        </p>
      </div>
    </div>
  </div>
</template>

<style>
.container {
  display: flex;
  flex-direction: column;
}
.header {
  width: 100vw;
  height: 9vh;
  background-color: #1a1f23;
  border-bottom: 1px solid #333943;
  padding: 0 10vw 0 10vw;
  display: flex;
}
.header-logo {
  margin-top: 2.5vh;
  background-color: #1a1f23;
  font-size: 24px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  cursor: pointer;
}
.header-other {
  display: flex;
  margin-left: 6vw;
  margin-top: 3.5vh;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 16px;
  background-color: #1a1f23;
}
.font {
  background-color: #1a1f23;
  margin-left: 2vw;
  cursor: pointer;
}

/* 


*/

.body {
  margin: auto;
  display: flex;
  margin-top: 6vh;
  width: 80vw;
  height: max-content;
}
.left {
  width: 14vw;
  opacity: 70%;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial,
    sans-serif;
}
.on-page-info {
  margin-top: 2vh;
  padding-right: 2vw;
}
.common-info {
  margin-top: 2vh;
  font-size: 14px;
}
/* 

*/
.middle {
  background-color: #1a1f23;
  border: 1px solid #333943;
  border-radius: 2vw;
  width: 70vw;
  padding: 3vw;
  font-family: Arial, Helvetica, sans-serif;
}
.main-head {
  text-align: center;
  font-size: 48px;
  background-color: #1a1f23;
}
.head-of-theme {
  margin-top: 4vh;
  font-size: 28px;
  background-color: #1a1f23;
}
.theme-info {
  margin-top: 3vh;
  font-size: 18px;
  opacity: 70%;
  background-color: #1a1f23;
  line-height: 28px;
}
</style>
