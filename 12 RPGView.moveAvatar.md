    int x = avatar.x;
    int y = avatar.y;
    switch(direction) {
    case LEFT:
      x--;
      break;
    case UP:
      y--;
      break;
    case DOWN: 
      y++;
      break;
    case RIGHT:
      x++;
      break;
    }
    if (x < 0 || x > this.map.map[0].length() || y < 0 || y > this.map.map.length)
      return;
    RPGTile tile = map.getTile(x, y);
    if (tile==RPGTile.MOUNTAIN || tile==RPGTile.RIVER || tile==RPGTile.ROCK) return; 
    avatar.x = x;
    avatar.y = y;