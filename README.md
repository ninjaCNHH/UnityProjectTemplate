# UnityProjectTemplate

- Add the file `background.png` to the root of the repo. This is the background image for index.html.
- Text in index.html that appears within square brackets [] should be replaced with actual text
- Add the /Build and /TemplateData from the Unity project
- Modify the variable `unityInstance` to point to the Unity json file for the project

```  
    var unityInstance = UnityLoader.instantiate("unityContainer", "Build/JM-RockkckerGame.json", {onProgress: UnityProgress});
```
