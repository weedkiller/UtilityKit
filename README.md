# UtilityKit

Mostly static utility classes that are used across multiple projects. This seems like a better place for them than in individual Gists.


#### SerializationUtil

Wrapper for dealing with BinaryFormatter in a way that works on AOT/IL2CPP and regular platforms. Save and load custom class hierarchies in just one line of code and works with Vector2/Vector3 fields.



#### SpriteAnimator

Replacement for having to deal with Mecanim, animation clips and all that crap. Drop it on a GameObject with a SpriteRenderer and you can create animations via drag-and-drop of some sprites. Nice and simple.



#### ObjectInspector

Generic Object Editor that provides the default inspector along with some additional goodies like Vector3 collection editing in the scene view and clickable buttons to call methods. Implement the empty IObjectInspectable interface and the ObjectInspector will be used for your class. You can even provide implementations of OnInspectorGUI and OnSceneGUI right in your class when using the ObjectInspector saving the trouble of making separate classes for inspectors. See the ObjectInspectorExample in the demo scene for usage examples.


#### StripGeneratedSolutionSettings

Fixes the cruft that Unity injects into MonoDevelop solution files. Hopefully won't be needed starting with Unity 5.2 if all goes well...



#### MathHelpers

Various math helpers that I find myself using often



#### AutoSnap

Handy utility that lets you get proper snapping with a 0, 0, 0 origin. Enable it via the Edit -> Auto Snap menu item.



#### ConstantsGeneratorKit

Generates constant classes for Layers, Resources, Scenes, Tags and SortingLayers. No more naked strings all over the place! It has it's own README markdown file with more information.





#### Note

Don't use the images included in this repo. They are copyright some other people. They were foraged from Google and included only for demonstration purposes!