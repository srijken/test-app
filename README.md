* `polymer build` 

```
info:    Preparing build...
info:    Building application...
info:    Generating build/unbundled...
info:    Generating build/bundled...
error:   Promise rejection: Error: file path is not in root: C:\Sources\Projects\bower_components\script-element\hello-world.js (C:\Sources\Projects\tmp2)
error:   Error: file path is not in root: C:\Sources\Projects\bower_components\script-element\hello-world.js (C:\Sources\Projects\tmp2)
    at Object.urlFromPath (C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\polymer-build\lib\path-transformers.js:41:15)
    at StreamAnalyzer.getFile (C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\polymer-build\lib\analyzer.js:107:39)
    at StreamResolver.accept (C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\polymer-build\lib\analyzer.js:210:34)
    at FileLoader.request (C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\hydrolysis\lib\loader\file-loader.js:64:27)
    at Object.<anonymous> (C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\vulcanize\lib\vulcan.js:318:26)
    at Array.map (native)
    at Object.inlineScripts (C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\vulcanize\lib\vulcan.js:311:34)
    at Object.<anonymous> (C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\vulcanize\lib\vulcan.js:458:21)
    at run (C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\core-js\modules\es6.promise.js:87:22)
    at C:\Users\s.rijken\AppData\Roaming\npm\node_modules\polymer-cli\node_modules\core-js\modules\es6.promise.js:100:28
```
