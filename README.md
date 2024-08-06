> [!NOTE]
> Local Fast Flags are being patched out. Expect your flags to not work soon enough.

![drake](https://github.com/pizzaboxer/bloxstrap/assets/67791946/303dfde5-1968-435e-8660-249e8b6001c6) 

# Change Rendering Mode

[Link To Original Post](https://discord.com/channels/1099468797410283540/1173220043266457660)

### Prefer Direct3D 11
```json
{
	"FFlagDebugGraphicsPreferD3D11": true
}
```

### Prefer Direct3D 11 w/ D3D10 Feature List
```json
{
	"FFlagDebugGraphicsPreferD3D11FL10": true
}
```

### Prefer Vulkan
> [!CAUTION]
> Performance may vary (Worse on nvidia cards). Expect visual bugs and crashes.
```json
{
	"FFlagDebugGraphicsPreferVulkan": true
}
```

### Prefer OpenGL
```json
{
	"FFlagDebugGraphicsPreferOpenGL": true
}
```
### Prefer Metal
> [!IMPORTANT]
> Only for MacOS.
```json
{
	"FFlagDebugGraphicsPreferMetal": true
}
```

# Rendering & Graphics

### Force Voxel Lighting
```json
{
	"DFFlagDebugRenderForceTechnologyVoxel": true
}
```

### Force ShadowMap Lighting
```json
{
	"FFlagDebugForceFutureIsBrightPhase2": true
}
```

### Force Future Lighting
```json
{
	"FFlagDebugForceFutureIsBrightPhase3": true
}
```

### Remove shadows (ShadowMap Lighting)
[Link To Original Post](https://discord.com/channels/1099468797410283540/1239502863206580245/1239502863206580245)
> [!NOTE]
> Will not turn off player or mesh shadows.
```json
{
	"DFIntCullFactorPixelThresholdShadowMapHighQuality": 2147483647
}
```

### Better Light Attenuation
[Link To Original Post](https://discord.com/channels/1099468797410283540/1165003069814226964)
> [!WARNING]
> May cause lighting artifacts.
```json
{
	"FFlagNewLightAttenuation": true
}
```

### Remove Player Shadows
[Link To Original Post](https://discord.com/channels/1099468797410283540/1147409993302282240)
```json
{
	"FIntRenderShadowIntensity": 0
}
```

### Disable PostFX
[Link To Original Post](https://discord.com/channels/1099468797410283540/1150655466830041128)
```json
{
	"FFlagDisablePostFx": true
}
```

### Disable Baked Shadows
[Link To Original Post](https://discord.com/channels/1099468797410283540/1173308420133232750)
```json
{
	"DFFlagDebugPauseVoxelizer": true
}
```

### Uncap FPS
```json
{
	"DFIntTaskSchedulerTargetFps": 9999,
	"FFlagTaskSchedulerLimitTargetFpsTo2402": false
}
```

### Force LOD For All Meshes
[Link To Original Post](https://discord.com/channels/1099468797410283540/1146963091775553536)
```json
{
	"DFIntCSGLevelOfDetailSwitchingDistance": 1,
	"DFIntCSGLevelOfDetailSwitchingDistanceL12": 2,
	"DFIntCSGLevelOfDetailSwitchingDistanceL23": 3,
	"DFIntCSGLevelOfDetailSwitchingDistanceL34": 4
}
```

### Remove Player Clothing Textures
[Link To Original Post](https://discord.com/channels/1099468797410283540/1207722310195486720)
```json
{
	"DFIntTextureCompositorActiveJobs": 0
}
```

### Force Texture Quality
[Link To Original Post](https://discord.com/channels/1099468797410283540/1150312397274357871)
> [!NOTE]
> The max visibly-changing value is 3.
```json
{
	"DFFlagTextureQualityOverrideEnabled": true,
	"DFIntTextureQualityOverride": 3
}
```

### FRM Quality Level Override
[Link To Original Post](https://discord.com/channels/1099468797410283540/1184157587562823780)
> [!NOTE]
> Forces graphics quality to the set level. Rendering Distance will still be controlled by the graphics quality slider.
```json
{
	"DFIntDebugFRMQualityLevelOverride": 1
}
```

### Enable MSAA
[Link To Original Post](https://discord.com/channels/1099468797410283540/1145231575173316608)
> [!WARNING]
> Do **_NOT_** set a value above 4 (This will cause viewports (3D Models) to become invisible.)
```json
{
	"FIntDebugForceMSAASamples": 1
}
```

### No Terrain Textures
[Link To Original Post](https://discord.com/channels/1099468797410283540/1194889014981967932)
```json
{
	"FIntTerrainArraySliceSize": 0
}
```

### ShadowMap Bias
[Link To Original Post](https://discord.com/channels/1099468797410283540/1152409274933317712)
```json
{
	"FIntRenderShadowmapBias": 10
}
```

### Remove FRM Grass
```json
{
	"FIntFRMMaxGrassDistance": 0,
	"FIntFRMMinGrassDistance": 0
}
```

# User Interface and Layout

### Rainbow UI / Viewport
[Link To Original Post](https://discord.com/channels/1099468797410283540/1183833667945103421)
```json
{
	"FFlagDebugDisplayUnthemedInstances": true
}
```

### Revert To Old Report Menu
[Link To Original Post](https://discord.com/channels/1099468797410283540/1204420123260092436)
```json
{
	"FFlagEnableReportAbuseMenuRoactABTest2": false,
	"FFlagEnableReportAbuseMenuRoact2": false,
	"FFlagEnableReportAbuseMenuLayerOnV3": false
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

### Return Old Voice Chat Bubble
[Link To Original Post](https://discord.com/channels/1099468797410283540/1139960093132210227)
> [!WARNING]
> This disables avatar chat.
```json
{
	"DFFlagFacialAnimationStreaming2": false
}
```

### Hide GUI
[Link To Original Post](https://discord.com/channels/1099468797410283540/1149975417818722314)
> [!NOTE]
> Set to a ID of a group you are in.
```json
{
	"DFIntCanHideGuiGroupId": 0
}
```

### Set Custom Font Size
[Link To Original Post](https://discord.com/channels/1099468797410283540/1170204803025088512)
```json
{
	"FIntFontSizePadding": 1
}
```

### Disable Translation settings
[Link To Original Post](https://discord.com/channels/1099468797410283540/1204335548160938025)
> [!NOTE]
> For some reason the "Give Translation Feedback" button stays.
```json
{
	"FFlagChatTranslationSettingEnabled3": false
}
```


### Disable VR toggle
[Link To Original Post](https://discord.com/channels/1099468797410283540/1238434506818588682/1238434506818588682)
```json
{
	"FFlagAlwaysShowVRToggleV3": false
}
```

### Disable Fullscreen Titlebar
[Link To Original Post](https://discord.com/channels/1099468797410283540/1198606462226792468)
```json
{
	"FIntFullscreenTitleBarTriggerDelayMillis": 3600000
}
```

### Chrome UI
[Link To Original Post](https://discord.com/channels/1099468797410283540/1156809517883985960)
> [!CAUTION]
> May cause the game to not load in certain games.
```json
{
	"FFlagEnableInGameMenuChrome": true
}
```

### Chrome Pin Chat
[Link To Original Post](https://discord.com/channels/1099468797410283540/1177942263100362792)
```json
{
	"FFlagEnableChromePinnedChat": true
}
```

# QOL (Quality Of Life)

### Voice Chat Volume
[Link To Original Post](https://discord.com/channels/1099468797410283540/1208100665138745424)
> [!NOTE]
> Default value is 1000 (in thousandths).
```json
{
	"DFIntVoiceChatVolumeThousandths": 1000
}
```

### Disable AD Portals
[Link To Original Post](https://discord.com/channels/1099468797410283540/1179502701118230529)
```json
{
	"FFlagAdServiceEnabled": false
}
```

### Scroll Speed
[Link To Original Post](https://discord.com/channels/1099468797410283540/1142226024281690132)
```json
{
	"FIntScrollWheelDeltaAmount": 0
}
```

### Disable Telemetry
[Link To Original Post](https://discord.com/channels/1099468797410283540/1155133604389728396)
> [!NOTE]
> Does not disable all telemetry.
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

# Misc 

### Place Specific Filter
[Link To Original Post](https://discord.com/channels/1099468797410283540/1239329199404355584/1239329199404355584)
- You can make any flag, place (game) specific by putting "_PlaceFilter" at the end of the flag. In the Value section, the value for the flag then put a semi-colon (;) and the place ID after. (You can add more by putting another ID after another semi-colon (;))

Example:
```json
{
	"DFIntTaskSchedulerTargetFps_PlaceFilter": "0;12345;246810"
}
```
