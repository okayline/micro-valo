# Changelog

## v1.2 — 2026-10-26 21:55 HST

Faster buying: click gun, shield, gun, shield... and the slots fill in order.

- Changed: clicking a gun now stays on that slot. Clicking a shield finishes the slot and moves to the next one.
- Changed: to skip a shield, click the next gun. It goes into the next slot.
- Added: right-click a slot to undo it. Its gun and shield go back to what it had at the start of the round.
- Changed: your slot buttons show the gun picture and shield picture, like the enemy row. The name under it is the gun only.
- Removed: the "+L" / "+H" text in your slot buttons (the shield picture shows it now). The fight results still use it.
- Changed: your slot pictures keep the same size when a shield is added (space for the shield is always kept). On phone width the gun picture is smaller to make room.
- Changed: the "SLOT 1" to "SLOT 5" labels are now "AGENT 1" to "AGENT 5".
- Changed: the fight box is full size from the start. It shows 5 empty lines that fill in one at a time, and the Next Round button's space is kept, so the box no longer grows.
- Changed: each fight line shows your gun and shield pictures on the left and the enemy's on the right, turned to face yours, in place of the names.
- Removed: the gun names and "+L" / "+H" text from the fight lines.
- Changed: the fight pictures sit tight around "vs": yours lean in from the left, the enemy's from the right.
- Changed: the fight box opens showing the round title, the line numbers, your guns, "vs", the words ROUND and YOU EARNED, and a dim Next Round button. Then one thing shows each second: each enemy side and its %, its WIN or LOSS, the round score, the money, and the button lights up. Enter and clicks do nothing until then.
- Changed: on the last round of a match, the title turns into VICTORY or DEFEAT and the button into PLAY AGAIN when the button lights up.
- Removed: the separate "VICTORY / YOU WIN THE MATCH" result lines.
- Changed: the hint line under the slots mentions right-click.
- Removed: buying a gun no longer jumps straight to the next slot.
- Changed: after picking an agent, clicking the gun it bought this round undoes it (back to its round-start gun). Clicking a shield you bought this round also undoes it.
- Not checked: how it feels to play. Checked in a browser over two rounds, with no console errors.

## v1.1 — 2026-10-26 21:35 HST

New buy screen layout and gun pictures. No change to the rules.

- Added: an enemy row at the top with "ENEMY 1" to "ENEMY 5" labels. Each panel shows the gun the enemy kept in that slot (a Classic if it lost the slot) and, to the right of the gun, a shield icon (plain for light, with the inner cut-out for heavy). The enemy's bank and this round's buy stay hidden.
- Added: PHANTOM, in the Rifles column under the Vandal. It is a copy of the Vandal (¤2,900, power 5), for choice only. The computer picks between the two at random.
- Added: "SLOT 1" to "SLOT 5" labels above your slot buttons, and bigger slot buttons.
- Changed: the buy board is five equal columns: Classic over Ghost, Spectre, Vandal over Phantom, Operator, and the shields (light over heavy) on the right. The enemy row, the score strip and your slots line up with the same five columns.
- Changed: the round score strip sits under the enemy row and shows ENEMY above YOU.
- Changed: all six guns are redrawn from screenshots of the real ones, in the same blocky style (Classic, Ghost, Spectre, Vandal, Phantom, Operator).
- Removed: the "ENEMY GUNS" text line, and the "SLOT n" text inside the slot buttons.
- Not checked: how it feels to play. Checked in a browser at 820 px and 390 px wide, over two rounds, with no console errors.

## v1.0 — 2026-10-26 06:39 HST

First version: a buy-phase game against the computer, first to 13 round wins. One page, no server.

- Added: the buy screen, laid out like the in-game one: five guns (Classic ¤0, Ghost ¤500, Spectre ¤1,600, Vandal ¤2,900, Operator ¤4,700) under their category headers, and an ARMOR column on the right with Light Shields (¤400) above Heavy Shields (¤1,000). No game name or logos.
- Added: 5 slots. You buy a gun and, if you want, a shield for each slot. Slot 1 fights the enemy's slot 1, and so on. Win 3 of 5 fights to win the round.
- Added: fight odds. Each gun has a power (Classic 0, Ghost 1, Spectre 3, Vandal 5, Operator 8) and a shield adds 1 (light) or 2 (heavy). The fight is 50% plus 5 points for each point of power ahead, never below 5% or above 95%.
- Added: money, as in your notes. Round win ¤15,000, loss bonus ¤9,500 / ¤12,000 / ¤14,500 for the first, second and third loss in a row, ¤200 for each fight won, cap ¤45,000. Start with ¤4,000. The money is pooled for the team.
- Added: guns and shields carry over for free when their slot wins its fight, and are lost when it loses. The enemy's guns are always shown, and its bank is hidden.
- Added: pistol rounds (round 1 and round 13, sidearms only, credits and guns reset), halftime after 12 rounds, and overtime at 12-12 (win by 2, ¤25,000 each round, nothing carries over).
- Added: the round scoreboard along the bottom, YOU and ENEMY, with a mark for each round won and a gold marker at halftime.
- Added: a computer opponent. Each round it picks a style at random (spread evenly, stack three slots, or save), buys the best gun it can afford per slot, then shields with what is left. It is not smart.
- Added: after you lock in, the five fights play out one at a time with your odds shown.
- Added: keys 1 to 5 pick a slot, Enter locks in. Buying a gun moves you to the next slot.
- Not in this version: abilities, a second human player, and sides (attack/defense).
- Removed: nothing.
