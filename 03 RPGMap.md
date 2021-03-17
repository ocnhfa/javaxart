    class RPGMap {

      String[] map;
      int x_start, y_start;

      RPGMap(String filename) {
  	    map = loadStrings(filename);
        x_start = map[0].length() / 2;
        y_start = map.length / 2;
      }

      RPGTile getTile(int x, int y) {
	    // TODO: RPGMap.getTile
      }
    }