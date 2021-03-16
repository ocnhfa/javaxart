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

  static RPGTile MOUNTAIN = new RPGTile("mountain.png");
  static RPGTile RIVER = new RPGTile("river.png");
  static RPGTile GRASS = new RPGTile("grass.png");
  static RPGTile ROCK = new RPGTile("rock.png");
  static RPGTile RIVERSTONE = new RPGTile("riverstone.png");
}