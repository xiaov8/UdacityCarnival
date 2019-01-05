# Udacity Carnival
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: Introduction to Virtual Reality
- Project: Udacity Carnival
- Submitted by: Virginia Liu


### Versions Used
- [Unity LTS Release 2017.4.15](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.170.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.170.0)
- [TextMesh Pro](https://assetstore.unity.com/packages/essentials/beta-projects/textmesh-pro-84126) v1.2.2


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is not included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.

## VR Developer Nanodegree | Unity Gitignore Rules          Revision 02/14/2018 ##

* Assumes the Unity project folder is an immediate child of the repository root directory.                                               
* Assumes miscellaneous folders such as, for example, a manually created folder for storing builds are created in the repository root directory and not inside the Unity project folder.
* Includes OS generated ignore rules for macOS and Windows typically defined within the global ignore rules.                             

## OS Generated ##
.DS_Store
._*
.Spotlight-V100
.Trashes
Icon?
ehthumbs.db
[Tt]humbs.db
[Dd]esktop.ini

## Unity Generated ##
*/[Tt]emp/
*/[Ll]ibrary/
*/[Oo]bj/
*/sysinfo.txt
*/*.stackdump

## Unity3D generated meta files ##
*.pidb.meta
*.pdb.meta

## Visual Studio / MonoDevelop Generated                                        ##
*/.vs/
[Ee]xported[Oo]bj/
*.userprefs
*.csproj
*.pidb
*.suo
*.sln
*.user
*.unityproj
*.booproj

## Common Repository Child Directories                                          ##
/[Bb]uild/
/[Bb]uilds/

