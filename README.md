<div align="center">
    
# Mirror Clone Toggle

[![Generic badge](https://img.shields.io/github/downloads/VRLabs/Mirror-Clone-Toggle/total?label=Downloads)](https://github.com/VRLabs/Mirror-Clone-Toggle/releases/latest)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/VRLabs/Mirror-Clone-Toggle/blob/main/LICENSE)
![Generic badge](https://img.shields.io/badge/Quest-Incompatible-red?logo=Meta)](https://img.shields.io/badge/Quest-Incompatible-red?logo=Meta)
[![Generic badge](https://img.shields.io/badge/Unity-2022.3.22f1-lightblue?logo=Unity)](https://unity.com/releases/editor/whats-new/2022.3.22)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-lightblue.svg)](https://vrchat.com/home/download)

[![Generic badge](https://img.shields.io/discord/706913824607043605?color=%237289da&label=DISCORD&logo=Discord&style=for-the-badge)](https://discord.vrlabs.dev/)
[![Generic badge](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dvrlabs%26type%3Dpatrons&style=for-the-badge)](https://patreon.vrlabs.dev/)
    
A system for forcing the mirror clone to be enabled

### ⬇️ [Download Latest Version](https://github.com/VRLabs/Mirror-Clone-Toggle/releases/latest)

### 📦 [Add to VRChat Creator Companion](https://vrlabs.dev/packages?package=dev.vrlabs.mirror-clone-toggle)

</div>

---

## How it works

* There is a camera in the system, which when enabled, always renders the `MirrorReflection` layer to a 1x1 resolution render texture.
* This is enough to get VRChat to enable the local Mirror Clone.

## Install guide

https://github.com/user-attachments/assets/93651823-2b07-45d2-b9cf-87c1a2d8b63c

* Drag and drop the `MirrorCloneToggle` prefab onto your avatar
* Merge the `MirrorCloneToggle_FX` FX layer with your avatar's FX layer, using [Av3Manager](https://github.com/VRLabs/Avatars-3.0-Manager)
* Merge the parameter list with your avatar's parameter list

## How to use

* The `MirrorCloneToggle/Enabled` parameter is a bool, which enables the mirror clone when enabled.

## Performance stats

```c++
FX Animator Layers: 1
```

## Hierarchy layout

```html
MirrorCloneToggle
|-MirrorCloneCamera
```

## Contributors

* [WingmanDraws](https://github.com/WingmanDraws)
* [TohruTheDragon](https://github.com/fkrisi11)

## License

Mirror Clone Toggle is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/Mirror-Clone-Toggle/blob/main/LICENSE).

​

<div align="center">

[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/VRLabs.png" width="50" height="50">](https://vrlabs.dev "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Discord.png" width="50" height="50">](https://discord.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Patreon.png" width="50" height="50">](https://patreon.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Twitter.png" width="50" height="50">](https://twitter.com/vrlabsdev "VRLabs")

</div>
