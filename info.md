# 20x9 Configuration

> 2400 x 1080px @ 30fps

## Scenes

![image](https://user-images.githubusercontent.com/1159091/140032040-fbf91e7d-fc52-424c-a85d-5dd4374e9ef6.png)

## Side Bar (480x1080px)

![image](https://user-images.githubusercontent.com/1159091/140032084-c18293c7-24f6-4971-9c12-4ee3aeeeff14.png)

## Audio

* Inputs: MIC
* Outputs: APP, BGM, VOX

Audio ducking of APP and BGM when MIC is active.  
MIC and VOX have compression (4:1)

![image](https://user-images.githubusercontent.com/1159091/140032270-883f508d-1763-4a6e-8716-c7728f1bd400.png)


## NDI Sources

![image](https://user-images.githubusercontent.com/1159091/140032153-9946f9cf-190e-40c1-af33-df6b37ac6282.png)

---

# Required

* Vertical Monitor Scroll Script - https://github.com/featherbear/obs-zoom-and-follow
  * Manually configure script to target scene
* Advanced Scene Switcher
* obs-ndi
  * Set main OBS Output NDI name to `OBS Output 20x9`
* infowriter

---

Optional

* https://github.com/featherbear/obs-mv-stat
* fullscreen clock (in repo)
