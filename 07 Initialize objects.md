  fullScreen();
  
  map = new RPGMap("default.map");
  avatar = new RPGAvatar(map.x_start, map.y_start);
  view = new RPGView(map, avatar);
  
  frameRate(10);
  background(0);
  view.drawView();