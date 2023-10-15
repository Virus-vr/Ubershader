# Ubershader
<br>
This shader was made for **Onward** by **Virus** and **Argon**
When you encounter problems please *DM* **virus_vr** or **argon_vr** on *Discord*

## Main
**Base Map:**             Select a base texture map for your material
**Base Color:**           Adjust the color of the *Base Map*
<br>
**Specular Map:**         Select a specular map for your material
**Specular Color:**       Adjust the color of the *Specular Map*
<br>
**Metal Value:**          Adjust the metalness of your material
<br>
**Roughness Map:**        Select a roughness map for your material
**Roughness Value:**      Adjust the *Roughness Map* strength
<br>
**Normal Map:**           Select a normal map for your material (gx format)
**Normal Map Strength:**  Adjust the strength of the *Normal Map*
<br>
**Emission Map:**         Select an emission map for your material
**Emission Color:**       Adjust the color of the *Emission Map* (black for no emission)
<br>
**Height Map:**           Select a height map for your material (this is used for the parallax mapping)
<br>
**ARM Texture:**          Enable the ARM texture (overrides *Roughness Map* and *Metal Value*)
**ARM Map:**               Select an ARM map (R: Ambient Occlusion; G: Roughness; B: Metalness)
<br>
## UV Adjustment
**UV Magic:**             Select what UV mode is used
1. Default:           Will use default UVs
2. Parallax Mapping:  Will use UVs based on Height Map and *Parallax* Settings (requires Height Map)
3. No_Tiling:         Will enable No-Tiling (can have a performance impact over default, since Textures have to be sampled twice)
4. <br>
**Tiling and Offset:**    Adjust the tiling (X & Y) and the offset (Z & W) of all maps selected in **Main**
<br>
## Parallax
**Sample Steps:**         Adjust the max sample steps for *Parallax Mapping* (This can impact performance by a lot! Keep it as low as possible)
**Amplitude:**            The depth of Parallax Mapping (expected values above 1)
<br>
## Rain FlipBook
**Rain Normal Map:**      Select a flipbook normal map with your rain effect (expected order: left to right, top to bottom; no empty slots)
**FlipBook Dimensions:**  Input the dimensions of your selected *Rain Normal Map*
**FlipBook Speed:**       Adjust how many times a second the flipbook switches to the next page
<br>
## Rain Settings
**Enable Water:**         This will Enable/Disable **ALL** Water effects
**Enable Rain:**          Enable/Disable rain (requires *Rain Normal Map*)
**Rain Strength:**        Adjust the strength of the rain
**Rain Tiling:**          Adjust tiling of the rain
<br>
## Puddle Settings
**Tiling:**               Adjust tiling of puddles
**Size:**                 Adjust the size of puddles
**Height:**               Adjust the height of puddles on *Height Map* (reqires *Height Map*)
**Edge Wetness:**         Adjust how wet the area around the edge of the puddles is
**Internal Size:**        Adjust how far away from the edge of the puddle the water starts
**Overall Wetness:**      Adjust the wetness for the rest of the material (outside of the puddles)
**Incline Consideration:**On how steep of an incline puddles can still appear (not is degrees)
<br>
## Other Settings
**Specular/Metallic Setup:**   Select if Specular or Metal should be used for the shader
**Additional Lights:**         If disabled, flashlights will not work on the materal
<br>
## Advanced Options
**These are Unity's settings, for information search the Unity documentation**
