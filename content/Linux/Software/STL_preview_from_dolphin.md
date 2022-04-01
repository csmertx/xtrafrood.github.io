![Screenshot of opening view3dscene with Dolphin](Screenshot_20220401_000441.png "Screenshot of opening view3dscene with Dolphin")
![Screenshot of view3dscene](Screenshot_20220401_000521.png "Screenshot of view3dscene")

#### View3dscene installation

- Download link: https://castle-engine.io/view3dscene.php
- Or if you prefer: https://github.com/castle-engine/view3dscene
- Extract w/Dolphin > Right Click > Extract > Extract Archive Here
```
vim $HOME/.local/share/applications/view3dscene.desktop

```
```
[Desktop Entry]
Comment[en_US]=A graphical frontend for viewing 3D meshes
Comment=A graphical frontend for viewing 3D meshes
Exec=/home/chris/.sources/view3dscene/view3dscene
GenericName[en_US]=View3dscene
GenericName=View3dscene
Icon=/home/chris/Pictures/Icons/3dview.png
Name[en_US]=View3dscene
Name=View3dscene
StartupNotify=false
Terminal=false
Type=Application
Categories=Utility
```

```
sudoc /home/chris/.sources/view3dscene/view3dscene
```

- Right Click .stl file in Dolphin, open with view3dscene (check box to remember)

- Icon used: https://www.freepngimg.com/png/32221-3d-image