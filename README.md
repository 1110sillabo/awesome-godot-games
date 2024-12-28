# awesome-godot-games

A list of Godot games with code and a few notes on their implementation.
Basically a big table you can browse as a reference, looking for ideas and/or peaking at implemented solutions.


| Game name | genre | description | code link | godot version | window size | stretch |	control	|movement axis | player movement | items movement |	assets | mechanics |	UI| layers | autoloads |
| -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| Veneno |	card game |	hearts like game with AI | https://github.com/BananaHolograma/Veneno | 4.1 (compatibility) | 640 x 360 (viewport), 1280 x 780 (override)  | canvas_items | mouse | check axis | check player | check items| check assets | check mechanics | super options resize friendly. See scenes/ui/options.gd and `node name="WindowsModeCheckbox" type="OptionButton"` in options.tscn. `DisplayServer.window_set_mode` does the job | none | 3: GameEvents, DeckManager, GameOptions |
| Alys |	precision platform |	celeste clone |	https://github.com/BananaHolograma/alys | 4.1 (compatibility) | 320 x 180 (viewport), 1280 x 780 (override)  | canvas_items | keys | check axis | check player | check items| check assets | check mechanics | check UI | 6: world, enemies, enviroment, hazard, hitboxes, player | 1: helpers |

# To do:

- Add a file with instructions and criteria for the chosen columns.
- Add more games.
- Add more references to Godot's ecosystem.
