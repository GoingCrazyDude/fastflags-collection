<h1 style="align: center;">Graphical Settings</h1>

### Disable PostFX
[Link to Original Post](https://discord.com/channels/1099468797410283540/1150655466830041128)
```json
{
    "FFlagDisablePostFx": true
}
```

### Change Rendering Mode
[Link to Original Post](https://discord.com/channels/1099468797410283540/1173220043266457660)
For D3D11 (DirectX 11):
```json
{
    "FFlagDebugGraphicsPreferD3D11": true
}
```
For D3D11FL10 (DirectX 11 but with the feature list of DirectX 10):
```json
{
    "FFlagDebugGraphicsPreferD3D11FL10": true
}
```
For Vulkan:
> [!CAUTION]
>
> Performance may vary (Worse on nvidia cards). Expect visual bugs and crashes.
```json
{
    "FFlagDebugGraphicsPreferVulkan": true
}
```
For OpenGL:
```json
{
    "FFlagDebugGraphicsPreferOpenGL": true
}
```
For Metal:
> [!IMPORTANT]
>
>Only for MacOS.

```json
{
    "FFlagDebugGraphicsPreferMetal": true
}
```

### Better Light Attenuation
> [!WARNING]
>
> May cause lighting artifacts.<br>

[Link to Original Post](https://discord.com/channels/1099468797410283540/1165003069814226964)
```json
{
    "FFlagNewLightAttenuation": true
}
```

### Disable Baked Shadows

[Link to Original Post](https://discord.com/channels/1099468797410283540/1173308420133232750)
```json
{
    "DFFlagDebugPauseVoxelizer": true
}
```

### Force LOD For All Meshes
[Link to Original Post](https://discord.com/channels/1099468797410283540/1146963091775553536)
```json
{
    "DFIntCSGLevelOfDetailSwitchingDistance":1,
    "DFIntCSGLevelOfDetailSwitchingDistanceL12":2,
    "DFIntCSGLevelOfDetailSwitchingDistanceL23":3,
    "DFIntCSGLevelOfDetailSwitchingDistanceL34":4
}
```

### Force Texture Quality
> [!NOTE]  
>
> Set to any value from 0 to 3.

[Link to Original Post](https://discord.com/channels/1099468797410283540/1150312397274357871)

```json
{
    "DFFlagTextureQualityOverrideEnabled": true,
    "DFIntTextureQualityOverride": 3
}
```

### FRM Quality Level Override
> [!NOTE]
>
> Forces graphics quality. Render distance will still incerase however. Values range from 1 - 10 and 1 - 21 if using 21 bars.

[Link to Original Post](https://discord.com/channels/1099468797410283540/1184157587562823780)

```json
{
    "DFIntDebugFRMQualityLevelOverride": 1
}
```

### Enable MSAA
> [!CAUTION]
>
> Values over 4 will cause viewports (3D Models) to be invisible.

[Link to Original Post](https://discord.com/channels/1099468797410283540/1145231575173316608)

```json
{
    "FIntDebugForceMSAASamples": 0
}
```

### Dark Textures
[Link to Original Post](https://discord.com/channels/1099468797410283540/1150375711631212604)
```json
{
    "FStringPartTexturePackTable2022": "{foil:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},asphalt:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},basalt:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},brick:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},cobblestone:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},concrete:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},crackedlava:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},diamondplate:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},fabric:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},glacier:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},glass:{ids:[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],color:[55, 55, 55, 255]},granite:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},grass:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},ground:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},ice:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},leafygrass:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},limestone:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},marble:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},metal:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},mud:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},pavement:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},pebble:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},plastic:{ids:[,rbxassetid://0],color:[55, 55, 55, 255]},rock:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},corrodedmetal:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},salt:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},sand:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},sandstone:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},slate:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},snow:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},wood:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},woodplanks:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]}}",
    "FStringPartTexturePackTablePre2022": "{foil:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},brick:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},cobblestone:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},concrete:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},diamondplate:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},fabric:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},glass:{ids:[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],color:[55, 55, 55, 255]},granite:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},grass:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},ice:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},marble:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},metal:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},pebble:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},corrodedmetal:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},sand:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},slate:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},wood:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},woodplanks:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},asphalt:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},basalt:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},crackedlava:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},glacier:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},ground:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},leafygrass:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},limestone:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},mud:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},pavement:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},rock:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},salt:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},sandstone:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]},snow:{ids:[rbxassetid://0,rbxassetid://0],color:[55, 55, 55, 255]}}"
}
```

### Low Poly Terrain
[Link To Original Post](https://discord.com/channels/1099468797410283540/1194889014981967932)
```json
{
    "FIntTerrainArraySliceSize": 8
}
```

### Minecraft Textures
[Link to Original Post](https://discord.com/channels/1099468797410283540/1153901513295527956)
```json
{
    "FStringPartTexturePackTablePre2022": "{\"foil\":{\"ids\":[\"rbxassetid://9873266399\",\"rbxassetid://9438410239\"],\"color\":[238,238,238,255]},\"asphalt\":{\"ids\":[\"rbxassetid://9867974823\",\"rbxassetid://9844502433\"],\"color\":[227,227,228,234]},\"basalt\":{\"ids\":[\"rbxassetid://11545552824\",\"rbxassetid://11545440462\"],\"color\":[160,160,158,238]},\"brick\":{\"ids\":[\"rbxassetid://9924770651\",\"rbxassetid://9924770538\"],\"color\":[229,214,205,227]},\"cobblestone\":{\"ids\":[\"rbxassetid://9919719550\",\"rbxassetid://9438453972\"],\"color\":[218,219,219,243]},\"concrete\":{\"ids\":[\"rbxassetid://9924775913\",\"rbxassetid://9924775826\"],\"color\":[225,225,224,255]},\"crackedlava\":{\"ids\":[\"rbxassetid://9920485426\",\"rbxassetid://9438453972\"],\"color\":[76,79,81,156]},\"diamondplate\":{\"ids\":[\"rbxassetid://10237721036\",\"rbxassetid://9438453972\"],\"color\":[210,210,210,255]},\"fabric\":{\"ids\":[\"rbxassetid://9920517963\",\"rbxassetid://9438453972\"],\"color\":[221,221,221,255]},\"glacier\":{\"ids\":[\"rbxassetid://9920518995\",\"rbxassetid://9438453972\"],\"color\":[225,229,229,243]},\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]},\"granite\":{\"ids\":[\"rbxassetid://9920550720\",\"rbxassetid://9438453972\"],\"color\":[210,206,200,255]},\"grass\":{\"ids\":[\"rbxassetid://11152995545\",\"rbxassetid://9267183930\"],\"color\":[196,196,189,241]},\"ground\":{\"ids\":[\"rbxassetid://11546360009\",\"rbxassetid://11545533676\"],\"color\":[165,165,160,240]},\"ice\":{\"ids\":[\"rbxassetid://9920556429\",\"rbxassetid://9438453972\"],\"color\":[235,239,241,248]},\"leafygrass\":{\"ids\":[\"rbxassetid://11152995545\",\"rbxassetid://9267183930\"],\"color\":[182,178,175,234]},\"limestone\":{\"ids\":[\"rbxassetid://9920561624\",\"rbxassetid://9438453972\"],\"color\":[250,248,243,250]},\"marble\":{\"ids\":[\"rbxassetid://9873292869\",\"rbxassetid://9438453972\"],\"color\":[181,183,193,249]},\"metal\":{\"ids\":[\"rbxassetid://11546526557\",\"rbxassetid://11546431794\"],\"color\":[226,226,226,255]},\"mud\":{\"ids\":[\"rbxassetid://9920578676\",\"rbxassetid://9438453972\"],\"color\":[193,192,193,252]},\"pavement\":{\"ids\":[\"rbxassetid://11546539560\",\"rbxassetid://11546440685\"],\"color\":[218,218,219,236]},\"pebble\":{\"ids\":[\"rbxassetid://9920581197\",\"rbxassetid://9438453972\"],\"color\":[204,203,201,234]},\"plastic\":{\"ids\":[\"\",\"rbxassetid://9868015012\"],\"color\":[255,255,255,255]},\"rock\":{\"ids\":[\"rbxassetid://11546570730\",\"rbxassetid://11546456858\"],\"color\":[211,211,210,248]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://11545623165\",\"rbxassetid://11545476330\"],\"color\":[206,177,163,180]},\"salt\":{\"ids\":[\"rbxassetid://9920590478\",\"rbxassetid://9438453972\"],\"color\":[249,249,249,255]},\"sand\":{\"ids\":[\"rbxassetid://11546588111\",\"rbxassetid://11546468464\"],\"color\":[218,216,210,240]},\"sandstone\":{\"ids\":[\"rbxassetid://9920596353\",\"rbxassetid://9438453972\"],\"color\":[241,234,230,246]},\"slate\":{\"ids\":[\"rbxassetid://9867974823\",\"rbxassetid://9844502433\"],\"color\":[235,234,235,254]},\"snow\":{\"ids\":[\"rbxassetid://11536062048\",\"rbxassetid://11108916253\"],\"color\":[239,240,240,255]},\"wood\":{\"ids\":[\"rbxassetid://9867974813\",\"rbxassetid://9844454989\"],\"color\":[217,209,208,255]},\"woodplanks\":{\"ids\":[\"rbxassetid://9867974813\",\"rbxassetid://9844454989\"],\"color\":[207,208,206,254]}}"
}
```

### Remove Textures
> [!IMPORTANT]
>
> Does not disable textures made by the game devs.

[Link to Original Post](https://discord.com/channels/1099468797410283540/1145767763005165700)

```json
{
    "FStringPartTexturePackTable2022": "{\"foil\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[238,238,238,255]},\"asphalt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[227,227,228,234]},\"basalt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[160,160,158,238]},\"brick\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[229,214,205,227]},\"cobblestone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[218,219,219,243]},\"concrete\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[225,225,224,255]},\"crackedlava\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[76,79,81,156]},\"diamondplate\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[210,210,210,255]},\"fabric\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[221,221,221,255]},\"glacier\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[225,229,229,243]},\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]},\"granite\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[210,206,200,255]},\"grass\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[196,196,189,241]},\"ground\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[165,165,160,240]},\"ice\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[235,239,241,248]},\"leafygrass\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[182,178,175,234]},\"limestone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[250,248,243,250]},\"marble\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[181,183,193,249]},\"metal\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[226,226,226,255]},\"mud\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[193,192,193,252]},\"pavement\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[218,218,219,236]},\"pebble\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[204,203,201,234]},\"plastic\":{\"ids\":[\"\",\"rbxassetid://0\"],\"color\":[255,255,255,255]},\"rock\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[211,211,210,248]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[206,177,163,180]},\"salt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[249,249,249,255]},\"sand\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[218,216,210,240]},\"sandstone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[241,234,230,246]},\"slate\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[235,234,235,254]},\"snow\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[239,240,240,255]},\"wood\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[217,209,208,255]},\"woodplanks\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[207,208,206,254]}}",
    "FStringPartTexturePackTablePre2022": "{\"foil\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[255,255,255,255]},\"brick\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[204,201,200,232]},\"cobblestone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[212,200,187,250]},\"concrete\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[208,208,208,255]},\"diamondplate\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[170,170,170,255]},\"fabric\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[105,104,102,244]},\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]},\"granite\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[113,113,113,255]},\"grass\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[165,165,159,255]},\"ice\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[255,255,255,255]},\"marble\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[199,199,199,255]},\"metal\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[199,199,199,255]},\"pebble\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[208,208,208,255]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[159,119,95,200]},\"sand\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[220,220,220,255]},\"slate\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[193,193,193,255]},\"wood\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[227,227,227,255]},\"woodplanks\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[212,209,203,255]},\"asphalt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[123,123,123,234]},\"basalt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[154,154,153,238]},\"crackedlava\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[74,78,80,156]},\"glacier\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[226,229,229,243]},\"ground\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[114,114,112,240]},\"leafygrass\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[121,117,113,234]},\"limestone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[235,234,230,250]},\"mud\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[130,130,130,252]},\"pavement\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[142,142,144,236]},\"rock\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[154,154,154,248]},\"salt\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[220,220,221,255]},\"sandstone\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[174,171,169,246]},\"snow\":{\"ids\":[\"rbxassetid://0\",\"rbxassetid://0\"],\"color\":[218,218,218,255]}}",
    "FStringTerrainMaterialTable2022": "",
    "FStringTerrainMaterialTablePre2022": ""
}
```

### Remove Player Shadows
[Link to Original Post](https://discord.com/channels/1099468797410283540/1147409993302282240)
```json
{
    "FIntRenderShadowIntensity": 0
}
```

### ShadowMap Bias
[Link to Original Post](https://discord.com/channels/1099468797410283540/1152409274933317712)
```json
{
    "FIntRenderShadowmapBias": 75
}
```

<h1 style="align: center;">UI (User Interface)</h1>

### Rainbow UI / Viewport
[Link To Original Post](https://discord.com/channels/1099468797410283540/1183833667945103421)
```json
{
    "FFlagDebugDisplayUnthemedInstances": true
}
```

### Disable Beta Badge
[Link To Original Post](https://discord.com/channels/1099468797410283540/1194581451857997844)
```json
{
    "FFlagVoiceBetaBadge": false,
    "FFlagTopBarUseNewBadge": false,
    "FFlagEnableBetaBadgeLearnMore": false,
    "FFlagBetaBadgeLearnMoreLinkFormview": false,
    "FFlagControlBetaBadgeWithGuac": false,
    "FStringVoiceBetaBadgeLearnMoreLink": ""
}
```

### Fix Beta Badge Dupe
[Link To Original Post](https://discord.com/channels/1099468797410283540/1194581451857997844)
```json
{
    "FFlagFixDupeBetaBadge": true
}
```

### Disable Self View
[Link To original Post](https://discord.com/channels/1099468797410283540/1183081644614226012)
```json
{
    "FFlagCoreGuiTypeSelfViewPresent": false
}
```

### Chat Keylogger
[Link To Original Post](https://discord.com/channels/1099468797410283540/1193962531128102955)
```json
{
    "FFlagDebugTextBoxServiceShowOverlay": true
}
```

### Remove Home Button
[Link to Original Post](https://discord.com/channels/1099468797410283540/1171224254352732201)
```json
{
    "FFlagInGameMenuHomeButton": false
}
```

### Chrome Pin Chat
[Link to Original Post](https://discord.com/channels/1099468797410283540/1177942263100362792)
```json
{
    "FFlagEnableChromePinnedChat": true
}
```

### Return Old Voice Chat Bubble [WARNING: DISABLES AVATAR CHAT]
[Link to Original Post](https://discord.com/channels/1099468797410283540/1139960093132210227)
```json
{
    "DFFlagFacialAnimationStreaming2": false
}
```

### Hide GUI
> [!NOTE]  
>
> Set to a id of a group you are in.

[Link to Original Post](https://discord.com/channels/1099468797410283540/1149975417818722314)

```json
{
    "DFIntCanHideGuiGroupId": 0
}
```

### Set Custom Font Size
[Link to Original Post](https://discord.com/channels/1099468797410283540/1170204803025088512)
```json
{
    "FIntFontSizePadding": 1
}
```

### Disable "Output device" UI from Escape Menu
[Link to Original Post](https://discord.com/channels/1099468797410283540/1184771500558012416)
```json
{
    "FFlagEnableAudioOutputDevice": false
}
```

### Disable Fullscreen Titlebar
[Link to Original Post](https://discord.com/channels/1099468797410283540/1198606462226792468)
```json
{
    "FIntFullscreenTitleBarTriggerDelayMillis": 3600000
}
```

### Chrome UI
> [!CAUTION]
>
> May cause the game to not load in certain games.

[Link to Original Post](https://discord.com/channels/1099468797410283540/1156809517883985960)
```json
{
    "FFlagEnableInGameMenuChrome": true
}
```

<h1 style="align: center;">QOL (Quality Of Life)</h1>

### Disable AD Portals
[Link to Original Post](https://discord.com/channels/1099468797410283540/1179502701118230529)
```json
{
    "FFlagAdServiceEnabled": false
}
```

### Scroll Speed
[Link to Original Post](https://discord.com/channels/1099468797410283540/1142226024281690132)
```json
{
    "FIntScrollWheelDeltaAmount": 0
}
```

### Disable Telemetry
> [!NOTE]  
>
> Does not disable all telemetry.

[Link to Original Post](https://discord.com/channels/1099468797410283540/1155133604389728396)

```json
{
    "FFlagDebugDisableTelemetryEphemeralCounter": true,
	"FFlagDebugDisableTelemetryEphemeralStat": true,
	"FFlagDebugDisableTelemetryEventIngest": true,
	"FFlagDebugDisableTelemetryPoint": true,
	"FFlagDebugDisableTelemetryV2Counter": true,
	"FFlagDebugDisableTelemetryV2Event": true,
	"FFlagDebugDisableTelemetryV2Stat": true
}
```

<h1 style="align: center;"> Misc </h1>

### Sky's Flag Collection
[Link to Original Post](https://discord.com/channels/1099468797410283540/1139962301991104582)

### Surfing The Web Inside of Roblox
[Link to Original Post](https://discord.com/channels/1099468797410283540/1165211319583117443)
```json
{
    "FFlagTopBarUseNewBadge": true,
    "FStringTopBarBadgeLearnMoreLink": "https://example.com",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://example.com"
}
```

<h1 style="align: center;"> Tutorials </h1>

### Make Your Own Custom Roblox Textures
[Link to Original Post](https://discord.com/channels/1099468797410283540/1178672676416536657)

[Link to Tutorial](https://discord.com/channels/1099468797410283540/1178672676416536657)

### Custom Weapon Skins In Phantom Forces
[Link to Original Post](https://discord.com/channels/1099468797410283540/1179092910252240966)