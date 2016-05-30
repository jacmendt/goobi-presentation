This is a custom build of OpenLayers 3. For rebuilding it use the OpenLayers 3 building system together with the file "ol3-dlf.json".

From the ol3 root folder the command for building the library looks like this:

```
node tasks/build.js ~/goobi-presentation/dlf/lib/OpenLayers/ol3-dlf.json ~/goobi-presentation/dlf/lib/OpenLayers/ol3-dlf.js
```

Run `npm install` before building an ol3 custom build. Right now the build is based on the [kitodo-presentation](https://github.com/slub/ol3) 
of ol3 slub fork. This is due to the fact that it uses small custom modifications of the ol.source.Zoomify. 