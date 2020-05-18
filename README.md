# UnityIBL
Toolkit for Image- and Video-Based Lighting and Shadowing from 360° Panoramic Images/Videos in Unity.

To use this algorithm for static image-based scenes, you need to add a GameObject with the *LightDetectionStatic* script to your scene and put in a panoramic image into the *Panoramic Image* field. A prefab for a GameObject like that can be found under */Prefabs/StaticScenePrefab* and full static scene can be found in */Scenes/StaticScene*.

For dynamic video-based scenes, there is a precomputational and a runtime version. Both need a GameObject with a VideoPlayer component that plays the 360° panoramic video. The GameObject also needs *LightDetection* or *LightDetectionPrecomputed* scripts attached respectively. Example prefabs and scenes for the precomputational version can be found under */Prefabs/PrecomputedDynamicScenePrefab* and */Scenes/PrecomputedDynamicScene*, while examples for the runtime version can be found under *Prefabs/DynamicScenePrefab* and */Scenes/DynamicScene*.
