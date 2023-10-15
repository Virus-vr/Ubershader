# Ubershader
This shader was made for **Onward** by **Virus** and **Argon**. <br>
If you encounter problems please, *DM* **virus_vr** or **argon_vr** on *Discord*

## Main
**Base Map:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;           Select a base texture map for your material <br>
**Base Color:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;               Adjust the color of the *Base Map* <br>
<br>
**Specular Map:**  &emsp;&emsp;&emsp;&emsp;&emsp;                         Select a specular map for your material <br>
**Specular Color:**  &emsp;&emsp;&emsp;&emsp;&ensp;                       Adjust the color of the *Specular Map* <br>
<br>
**Metal Value:** &emsp;&nbsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;         Adjust the metalness of your material <br>
<br>
**Roughness Map:**  &emsp;&emsp;&emsp;&emsp;                              Select a roughness map for your material <br>
**Roughness Value:** &emsp;&emsp;&emsp;&ensp;                             Adjust the *Roughness Map* strength <br>
<br>
**Normal Map:**  &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;                     Select a normal map for your material (gx format) <br>
**Normal Map Strength:** &emsp;&nbsp;                                     Adjust the strength of the *Normal Map* <br>
<br>
**Emission Map:**  &emsp;&emsp;&emsp;&emsp;&emsp;                         Select an emission map for your material <br>
**Emission Color:** &emsp;&emsp;&emsp;&emsp;&ensp;                        Adjust the color of the *Emission Map* (black for no emission) <br>
<br>
**Height Map:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;                     Select a height map for your material (this is used for the parallax mapping) <br>
<br>
**ARM Texture:** &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;                     Enable the ARM texture (overrides *Roughness Map* and *Metal Value*) <br>
**ARM Map:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;            Select an ARM map (R: Ambient Occlusion; G: Roughness; B: Metalness) <br>
<br>
## UV Adjustment
**UV Magic:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;                 Select what UV mode is used
1. Default: &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;                  Will use default UVs
2. Parallax Mapping: &emsp;&ensp;&nbsp;                                 Will use UVs based on Height Map and *Parallax* Settings (requires Height Map)
3. No_Tiling: &emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;                      Will enable No-Tiling (can have a performance impact over default, since Textures have to be sampled twice)  <br>

**Tiling and Offset:**  &emsp;&emsp;&emsp;&ensp;&nbsp;                    Adjust the tiling (X & Y) and the offset (Z & W) of all maps selected in **Main** <br>
<br>

## Parallax
**Sample Steps:**  &emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;                   Adjust the max sample steps for *Parallax Mapping* (This can impact performance by a lot! Keep it as low as possible) <br>
**Amplitude:**     &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;             The depth of Parallax Mapping (expected values above 1) <br>
<br>
## Rain FlipBook
**Rain Normal Map:**  &emsp;&emsp;&emsp;&nbsp;                            Select a flipbook normal map with your rain effect (expected order: left to right, top to bottom; no empty slots) <br>
**FlipBook Dimensions:**  &emsp;&ensp;&nbsp;                              Input the dimensions of your selected *Rain Normal Map* <br>
**FlipBook Speed:**  &emsp;&emsp;&emsp;&emsp;&nbsp;                       Adjust how many times a second the flipbook switches to the next page <br>
<br>
## Rain Settings
**Enable Water:**  &emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;                   This will Enable/Disable **ALL** Water effects <br>
**Enable Rain:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;                    Enable/Disable rain (requires *Rain Normal Map*) <br>
**Rain Strength:**  &emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;&nbsp;            Adjust the strength of the rain <br>
**Rain Tiling:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;              Adjust tiling of the rain <br>
<br>
## Puddle Settings
**Tiling:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;       Adjust tiling of puddles <br>
**Size:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;   Adjust the size of puddles <br>
**Height:**  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;             Adjust the height of puddles on *Height Map* (reqires *Height Map*) <br>
**Edge Wetness:**  &emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;                   Adjust how wet the area around the edge of the puddles is <br>
**Internal Size:**  &emsp;&emsp;&emsp;&emsp;&emsp;&ensp;                  Adjust how far away from the edge of the puddle the water starts <br>
**Overall Wetness:**  &emsp;&emsp;&emsp;&ensp;&nbsp;                      Adjust the wetness for the rest of the material (outside of the puddles) <br>
**Incline Consideration:**  &emsp;&ensp;                                  On how steep of an incline puddles can still appear (not is degrees) <br>
<br>
## Other Settings
**Specular/Metallic Setup:** &nbsp;                                       Select if Specular or Metal should be used for the shader <br>
**Additional Lights:**  &emsp;&emsp;&emsp;&nbsp;                          If disabled, flashlights will not work on the materal <br>
<br>
## Advanced Options
**These are Unity's settings, for information search the Unity documentation**
