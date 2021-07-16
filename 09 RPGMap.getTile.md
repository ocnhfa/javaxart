        if (y < 0 || y > map.length - 1 ||
              x < 0 || x + 1 > map[y].length() - 1) {
              return RPGTile.MOUNTAIN;
        }
        String type = map[y].substring(x, x + 1);
        return RPGTile.getTile(type);