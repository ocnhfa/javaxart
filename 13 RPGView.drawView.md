
        int x_min = avatar.x - RADIUS;
        int y_min = avatar.y - RADIUS;
        for (int x = 0; x < SIZE; x++) {
            for (int y = 0; y < SIZE; y++) {
                  RPGTile tile = map.getTile(x + x_min, y + y_min);
                  PImage image = loadImage(tile.image);
                  image(image, MARGIN_X + RPGTile.WIDTH * x, MARGIN_Y + RPGTile.HEIGHT * y);
            }
        }
        image(avatar.image, MARGIN_X + RADIUS * RPGTile.WIDTH, MARGIN_Y +RADIUS * RPGTile.HEIGHT);