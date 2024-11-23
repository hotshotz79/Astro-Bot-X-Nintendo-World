**Day 6 - To URP or Not be URP**

**Unity3D:** Tried to get a different rendering pipeline (URP) to work but no luck... thanks @_SnakePlissken1 for working with me on this
After switching to URP or even HDRP; the project can be built but running on PS5 causes blank screen and then errors out.
One thing to note; if there is a HUD (UI) in your URP project, it will still display on the PS5 until it crashes.

One of the shader error is related to "PSSL.hlsl"

> [!TIP]
> Need to learn how Shaders work ... 
> Possible link; https://docs.unity3d.com/2021.2/Documentation/Manual/SL-ShaderPrograms.html

Already spent close to 2 days trying to make this work, so maybe next time... back to my project

--------------------------------------

**Day 7 & 8 - Vibin'**

Unity3D: Spent a lotta time to implement Vibration / Light change, unfortunately no API for speaker system

Plugin used; [Rewired](https://assetstore.unity.com/packages/tools/utilities/rewired-21676)

Note: not all versions of Rewired will work... See below on the final 'working' results

https://github.com/user-attachments/assets/19ba577b-db73-4807-88cd-384d83a47c0e

