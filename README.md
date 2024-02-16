  
<div align="center">
  <h1>sup?</h1>
  <img src="https://github.com/L101111/L101111/blob/main/s.gif" width="600"'><br>
  <br>
  <br>


  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="jupyter logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="linux logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="40" alt="bash logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original.svg" height="40" alt="apache logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" height="40" alt="nginx logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" height="40" alt="windows8 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" height="40" alt="arduino logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/anaconda/anaconda-original.svg" height="40" alt="anaconda logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vim/vim-original.svg" height="40" alt="vim logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />
</div>
<br>
<br>


<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=L101111&theme=midnight-purple&show_icons=true&hide_border=true&count_private=true" alt="L101111's Stats">

<br>
<br>


<div>
function keyDown(e) {
    Podium = {};
    var n = document.createEvent("KeyboardEvent");
    Object.defineProperty(n, "keyCode", {
        get: function () {
            return this.keyCodeVal;
        },
    }),
        n.initKeyboardEvent ? n.initKeyboardEvent("keydown", !0, !0, document.defaultView, e, e, "", "", !1, "") : n.initKeyEvent("keydown", !0, !0, document.defaultView, !1, !1, !1, !1, e, 0),
        (n.keyCodeVal = e),
        document.body.dispatchEvent(n);
}
function keyUp(e) {
    Podium = {};
    var n = document.createEvent("KeyboardEvent");
    Object.defineProperty(n, "keyCode", {
        get: function () {
            return this.keyCodeVal;
        },
    }),
        n.initKeyboardEvent ? n.initKeyboardEvent("keyup", !0, !0, document.defaultView, e, e, "", "", !1, "") : n.initKeyEvent("keyup", !0, !0, document.defaultView, !1, !1, !1, !1, e, 0),
        (n.keyCodeVal = e),
        document.body.dispatchEvent(n);
}
setInterval(function () {
    Runner.instance_.horizon.obstacles.length > 0 &&
        (Runner.instance_.horizon.obstacles[0].xPos < 25 * Runner.instance_.currentSpeed - Runner.instance_.horizon.obstacles[0].width / 2 && Runner.instance_.horizon.obstacles[0].yPos > 75 && (keyUp(40), keyDown(38)),
        Runner.instance_.horizon.obstacles[0].xPos < 30 * Runner.instance_.currentSpeed - Runner.instance_.horizon.obstacles[0].width / 2 && Runner.instance_.horizon.obstacles[0].yPos <= 75 && keyDown(40));
}, 5);

</div>

