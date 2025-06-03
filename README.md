 <div>
          <div> 
              <div class={color == "red" ? "red" : ""}> Red </div>
              <div class={color == "yellow" ? "yellow" : ""}> Yellow </div>
              <div class={color == "green" ? "green" : ""}> Green </div>
          </div>
      </div>;
    }








    html,
body {
  border: 0;
  padding: 0;
  margin: 0;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100%;
}

#container {
  display: flex;
  flex-flow: column wrap;
  justify-content: flex-end;
  align-items: center;
  width: 60%;
  height: 100%;
  background: black;
  margin: 0;
  padding: 0;
}

#panel {
  display: flex;
  flex-direction: column;
  /*position: relative;*/
  justify-content: space-around;
  align-items: center;
  /*top: -70px;*/
  width: 30%;
  height: 60%;
  background: black;
  border-radius: 20px;
}

.light {
  width: 100px;
  height: 100px;
  background: lightgrey;
  border-radius: 100%;
  animation-name: colorChange;
  animation-duration: 3s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
  animation-timing-function: linear;
}

#red {
  animation-name: redColor;
  animation-duration: 3s;
  animation-iteration-count: infinite;
}

#yellow {
  animation-name: yellowColor;
}

#green {
  animation-name: greenColor;
}

#bar {
  width: 10%;
  height: 30%;
  background: black;
}
