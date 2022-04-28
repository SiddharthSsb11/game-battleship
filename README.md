# Battleship Game

>Multiplayer Game

A multiplyaer game where you can always switch for the sngleplayer mode too and rage a war against the computer's battleships.

Its easy to understand and fun to kill your not so precious time.


```
This game is still work in progress.
```

### Few Screenshots

![Homepage](/screenshots/1.png "Homepage")
![Singleplayer](/screenshots/3.png "Singleplayer")
![Multiplayer](/screenshots/2.png "Multiplayer Multiple windows ")

### Features
- 5 draggable ships
- Rotable ships prior to dragging
- Computer take random goes
- Display results based on who has sunk whos ship
- Display the winner
- Multiplayer feature powered by __Socket.io__

### Rules

- Start with starring this repo.
- Start with your fice ships: __Destroyer, Cruiser, Submarine, Battleship, Carrier__
- Drag & Drop and position your ship on your side box (left side) accordingly.
- Vertically or horizontally thats upto you to rotate the ship before placing in your left box.
- Place each ship in any horizontal or vertical postion, but not diagonally.
- Do not place a ship so tha nay part of it overlaps another ship or go beyond edges of the box.
- Once you have finished placing ship, press the start button.
- Player One always goes first.  
- You and your enemy will alternate turns, firing out one shot per turn to try and hit each other's ship.
- Now the game has started - If you are playing in __Singleplayer__ mode against cpu, singleplayer mode allows the cpu to take it goes/turn against you; where cpu has already generated random ships.
- __Multiplayer__ mode: start button show the other player that Player 1(user) are ready ; Player 2 must also place his ship on his board and press the ready button to start the game.
- Your goal is to sink enemies ship before they sink yours.
- To sink their ships try to guess the coordinate of enemy's ship and fire(click) on it to launch an attack.
- If you are the first player to sink your opponent's entire fleet of 5 ships, you win the game.

### Tech Stack


<table width="1000">
	<tr>
        <td align="center"><a href="https://www.javascript.com/"><img src="https://cdn.worldvectorlogo.com/logos/logo-javascript.svg" width="110px;" height="75px;" alt="Javascript"/><br /><b><font color="#777">JavaScript</font></b></a></td>
        <td align="center"><a href="https://nodejs.org/en/"><img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" width="75px;" height="75px;" alt="NodeJS"/><br /><b><font color="#777">NodeJS</font></b></a></td>
		<td align="center"><a href="https://www.apollographql.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/6/64/Expressjs.png" width="75px;"  alt="Express JS"/><br /><b><font color="#777">ExpressJS</font></b></a></td>
		<td align="center"><a href="https://socket.io/"><img src="https://cdn.worldvectorlogo.com/logos/socket-io.svg" width="75px;" height="75px;" alt="Socket.IO"/><br /><b><font color="#777">Socket.IO</font></b></a></td>
	</tr>	
</table>