# C39-Debug-Part-1

INDEX.HTML- added files game.js and attached it to firebase database 

GAME.JS - line 104 code added - to destroy and update score
                
                for (var i = 0; i < fruitGroup.length; i++) {
                     if (fruitGroup.get(i).isTouching(players)) {
                        fruitGroup.get(i).destroy();
                        player.score =player.score+1;
                        player.update();
                     }
