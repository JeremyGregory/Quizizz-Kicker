# Getting Started
First paste this code into bookmark bar
```js
javascript:(function()%7Bfetch(%22https%3A%2F%2Fraw.githubusercontent.com%2Fseanv999%2FQuizizz-Kicker%2Fmain%2FBundle.js%22)%0A.then((res)%20%3D%3E%20res.text()%0A.then((t)%20%3D%3E%20eval(t)))%7D)()%3B
```
Or Paste this code into console
```js
fetch("https://raw.githubusercontent.com/seanv999/Quizizz-Kicker/main/Bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
# Kicking Players
Either run the bookmarklet or enter the code into console and you will see a prompt asking for the player name,
type the player name(case sensitive) and hit ok,
when the player answers a question they will immediately be removed from the game without getting points for that question

# Requirements
1: You must be in the same quiz as the player you are kicking.<br/>
2: The script needs to be ran when you see the questions or will not work at all<br/>
3: This will not work on if ran on quizizz live starting screen were u see the players since were ending there game<br/>

# How it works
im simply posting a request to (url) with room hash and player id (name)
do not get this request confused with the request sent when you manually kick a player on the host side those are competly different
the request that is sent is ending there game not kicking them<br/>

with this info you should be able to build your own :D, credit me if ur not gay<br/>


