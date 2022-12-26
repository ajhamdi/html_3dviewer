# Light 3D Viewer ( HTML component)
An html component to view your 3D files of types: `obj`, `3ds`, `stl`, `ply`, `gltf`, `3dm`, `fbx`. 

1- pload your 3D file to any server ( e.g. on github).

2- Use the following html component with replacing `MODEL_URL` with your 3D file url.

```
<iframe
width="250" height="250" style="border:1px solid #eeeeee;"
src="https://3dviewer.net/embed.html#model=MODEL_URL$camera=169.48379,370.18722,427.39485,255.46234,255.54915,255.43774,0.00000,1.00000,0.00000,45.00000$cameramode=perspective$envsettings=fishermans_bastion,off$backgroundcolor=255,255,255,255$defaultcolor=200,200,200$edgesettings=off,0,0,0,1">
</iframe>
```
You can modify the viewer size, the object color, background, ...etc by changing the attributes above: `height`, `width`, `backgroundcolor`, `defaultcolor`. Otherwise remove them for default settings.

## That's it. Enjoy!
![qay66-jsbrv](https://user-images.githubusercontent.com/26301932/209533463-43d2c736-eb44-4781-ac3e-39e66bbdd950.gif)

### 
* This html coponent utlizes the great [online3dviewer](https://3dviewer.net/) framework.
