    import processing.core.*;

    class RPGTile {
  
      static final int WIDTH = 64;
      static final int HEIGHT = 64;
      String image;

      RPGTile(String filename) {
        this.image = filename;
      }

      static RPGTile getTile(String type) {
	    // TODO
      }

      static final RPGTile MOUNTAIN = new RPGTile("mountain.png");
      static final RPGTile RIVER = new RPGTile("river.png");
      static final RPGTile GRASS = new RPGTile("grass.png");
      static final RPGTile ROCK = new RPGTile("rock.png");
      static final RPGTile RIVERSTONE = new RPGTile("riverstone.png");
    }