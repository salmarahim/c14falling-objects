# c14falling-objects

# create two groups..one of friends and other one for the enemies
### -every 60 frames at random the friends or enemies should be created(refer to space shooter game how you create random enemies)
### -add the friends to friendsgroup and enemies to enemies group
### -when mouse is clicked over each sprite it should disappear..for this we need to extract the sprite that was clicked 

# how to extract a sprite from a group
### use the for loop to span through the group
### for (var i = 0; i < enemygroup.maxDepth(); i++) {
###    }
### inside the for loop select each sprite using the group.get(i)
### if the mouse was pressed over it, it should get destroyed
### increase the score for the friendsgroup and decrease it for the enemy group
### also set a timer variable that starts at 0 and when it becomes 60, then gameover

# the for loop for you to refer
### apply this and make changes according to your game and variables
### for (var i = 0; i < enemygroup.maxDepth(); i++) {
   ### if(enemygroup.get(i)!=null && mousePressedOver(enemygroup.get(i))){
  ###   enemygroup.get(i).destroy();
   ###   score--;
  ### }
https://salmarahim.github.io/c14falling-objects/
