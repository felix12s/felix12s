// ==UserScript==
// @name         ! S Client v6.2 (Public)
// @creator      InsanityMon, Ueheua
// @description  u guys stop hating me f r :)
// @version      v6.2
// @match        *://sandbox.moomoo.io/*
// @match        *://*.moomoo.io/*
// @require      https://rawgit.com/kawanet/msgpack-lite/master/dist/msgpack.min.js
// @icon        https://moomoo.io/img/favicon.png?v=1
// @grant        none
// ==/UserScript==
// PLEASE CREDIT S (InsanityMon, Ueheua) for skidding or editing this script thanks!


// NAME ON MAIN MENU:
document.getElementById("gameName").innerHTML = "S Client";

// SCRIPT MENU:
let modMenus = document.createElement("div");
modMenus.id = "modMenus";
document.body.append(modMenus);
modMenus.style.display = "block";
modMenus.style.padding = "10px";
modMenus.style.backgroundColor = "rgba(0, 0, 0, 0.25)";
modMenus.style.borderRadius = "4px";
modMenus.style.position = "absolute";
modMenus.style.left = "20px";
modMenus.style.top = "20px";
modMenus.style.minWidth = "300px";
modMenus.style.maxWidth = "290px";
modMenus.style.minHeight = "400";
modMenus.style.maxHeight = "700";

function updateInnerHTML() {
    modMenus.innerHTML = `<div id = "headline" style = "
font-size: 30px;
color: rgb(255, 255, 255);
">
<script>
function rickRolling() {
    window.open("https://www.youtube.com/watch?v=dQw4w9WgXcQ");
};
function toggleUI() {
    $("#gameUI").toggle();
};
</script>

Settings:
<br>
<button id = "uifr?" onclick = "toggleUI()">
UI
</button>
<br>
<label for="ggezCh">AutoGG </label>
        <input value="gg - S Client autoGG" input="text" minlength="0" maxlength="30" id="ggezCh"><br>
<hr>
<div style = "
font-size: 12px;
overflow-y: scroll;
max-height: 150px;
">
<br>
Toggles:
<br>
Visual:
<select id = "visualtype">
<option value = "1">FZ</option>
<option value = "2">AE86</option>
</select><br>

<input type = "checkbox" checked id = "plc1">
Auto Placer
<br>

<input type = "checkbox" checked id = "plc2">
Auto Replacer
<br>

<input type = "checkbox" id = "grind">
Auto Grinder
<br>

<input type = "checkbox" id = "autoq">
Auto q (Broken)
<br>

<input type = "checkbox" id = "realanimtexterpls">
Animation Text
<br>

<input type = "checkbox" id = "spiketick">
Spike Tick
<br>

<input type = "checkbox" checked id = "tickbase">
Tick Base
<br>

<input type = "checkbox" id = "stop">
Stop Bots
... (729 KB left)
