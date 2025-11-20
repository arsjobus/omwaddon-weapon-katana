# OpenMW Weapon: Katana

A sleek katana weapon mod for **The Elder Scrolls III: Morrowind** using **OpenMW**. Add this classic weapon to your game for a fresh combat experience! ⚔️  

### Installation (Manual)

1) Copy the **textures** folder contents into:

`Data Files/textures`

2. Copy the **meshes** folder contents into:  

`Data Files/meshes`

3. Copy the 'weapon-katana.omwaddon' file into:  

`Data Files`

And you’re done! The katana should now be available in-game.

### Enable the Normal / Specular Maps (Optional)

Add the following lines of configuration into the settings.cfg file initialized by OpenMW:

```
auto use object normal maps = true
auto use object specular maps = true
normal map pattern = _n
normal height map pattern = _nh
specular map pattern = _spec
```
Note: [Read more](https://openmw.readthedocs.io/en/latest/reference/modding/texture-modding/texture-basics.html#automatic-use) about Automatic Use technique to use normal and specular maps by OpenMW.

---

## Obtaining it

It can be found in-game and picked-up underneath the long bridge going out of Seyda Neen (Starting area).

Alternatively, spawn a Katana (Basic) weapon into your inventory with console command:

`player->additem katana_basic 1`

---

## Notes
- Make sure OpenMW is installed and running the correct data folder.  
- For best results, back up your game before installing mods.  

---

## Credits
[Katana](https://opengameart.org/content/katana-2) model and texture by [Colorado Stark](https://opengameart.org/users/colorado-stark) from OpenGameArt.