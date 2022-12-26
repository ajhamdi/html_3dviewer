# obj_html_3dviewer
an html component to view your 3D `.obj` files 

First , upload your `.obj` file to any server ( e.g. on github). Now use this html coponent with replacing `MODEL_URL` with your `.obj` file url

```
<iframe
width="250" height="250" style="border:1px solid #eeeeee;"
src="https://3dviewer.net/embed.html#model=MODEL_URL$camera=169.48379,370.18722,427.39485,255.46234,255.54915,255.43774,0.00000,1.00000,0.00000,45.00000$cameramode=perspective$envsettings=fishermans_bastion,off$backgroundcolor=255,255,255,255$defaultcolor=200,200,200$edgesettings=off,0,0,0,1">
</iframe>
```
