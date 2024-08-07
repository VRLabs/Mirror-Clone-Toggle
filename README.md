# MirrorCloneToggle
</b> Forces the mirror clone to be on when requested<br>
<br><br>

<h2>How it works</h2>

There is a camera in the system, which when enabled, always renders the `MirrorReflection` layer to a 1x1 resolution render texture.<br>
This is enough to get VRChat to enable the local Mirror Clone.

<h2>Install guide</h2>

- Drag and drop the `MirrorCloneToggle` prefab onto your avatar
- Merge the `MirrorCloneToggle_FX` FX layer with your avatar's FX layer, using [Av3Manager](https://github.com/VRLabs/Avatars-3.0-Manager)
- Merge the parameter list with your avatar's parameter list
<br>

<h2>Performance stats</h2>
- 1 local bool parameter (0 synced cost)<br>
- 0 material slots (1 texture that doesn't get used in any material)

<h2>Hierarchy layout</h2>
MirrorCloneToggle<br>
|-MirrorCloneCamera

<h2>Contributors</h2>
<ul>
    <li>[WingmanDraws](https://github.com/WingmanDraws)</li>
    <li>[TohruTheDragon](https://github.com/fkrisi11)</li>
</ul>
