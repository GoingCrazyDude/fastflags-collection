> [!NOTE]
> Local Fast Flags are being patched out. Expect your flags to not work soon enough.

# Rendering and Graphics

### Prefer Direct3D 11
```json
{
    "FFlagDebugGraphicsPreferD3D11": true
}
```

### Prefer the Direct3D 10 Features List for Direct3D 11
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

### Enables Voxel Lighting
```json
{
    "DFFlagDebugRenderForceTechnologyVoxel": true
}
```

### Enables ShadowMap Lighting
```json
{
    "FFlagDebugForceFutureIsBrightPhase2": true
}
```

### Enables Future Lighting
```json
{
    "FFlagDebugForceFutureIsBrightPhase3": true
}
```

### Remove shadows (ShadowMap Lighting)
> [!NOTE]
> Will not turn off player or mesh shadows.
```json
{
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": 2147483647
}
```

### Better Light Attenuation
> [!WARNING]
> May cause lighting artifacts.
```json
{
    "FFlagNewLightAttenuation": true
}
```

### Remove Player Shadows
```json
{
    "FIntRenderShadowIntensity": 0
}
```

### Disable PostFX
```json
{
    "FFlagDisablePostFx": true
}
```

### Disable Baked Shadows
```json
{
    "DFFlagDebugPauseVoxelizer": true
}
```

### Uncapped FPS
```json
{
    "DFIntTaskSchedulerTargetFps": 9999,
    "FFlagTaskSchedulerLimitTargetFpsTo2402": false
}
```

### Force LOD For All Meshes
```json
{
    "DFIntCSGLevelOfDetailSwitchingDistance":1,
    "DFIntCSGLevelOfDetailSwitchingDistanceL12":2,
    "DFIntCSGLevelOfDetailSwitchingDistanceL23":3,
    "DFIntCSGLevelOfDetailSwitchingDistanceL34":4
}
```

### Remove Player Clothing Textures
```json
{
    "DFIntTextureCompositorActiveJobs": 0
}
```

### Force Texture Quality
> [!NOTE]
> The max visibly-changing value is 3.
```json
{
    "DFFlagTextureQualityOverrideEnabled": true,
    "DFIntTextureQualityOverride": 3
}
```

### FRM Quality Level Override
> [!NOTE]
> Forces graphics quality to the set level. Rendering Distance will still be controlled by the graphics quality slider.
```json
{
    "DFIntDebugFRMQualityLevelOverride": 1
}
```

### Enable MSAA
> [!WARNING]
> Do **_NOT_** set a value above 4 (This will cause viewports (3D Models) to become invisible.)
```json
{
    "FIntDebugForceMSAASamples": 1
}
```

### No Terrain Textures
```json
{
    "FIntTerrainArraySliceSize": 0
}
```

### ShadowMap Bias
```json
{
    "FIntRenderShadowmapBias": 10
}
```

### ShadowMap Bias
```json
{
    "FIntFRMMaxGrassDistance": 0,
    "FIntFRMMinGrassDistance": 0
}
```

# User Interface and Layout

### Rainbow UI / Viewport
```json
{
    "FFlagDebugDisplayUnthemedInstances": true
}
```

### Revert To Old Report Menu
```json
{
    "FFlagEnableReportAbuseMenuRoactABTest2": false,
    "FFlagEnableReportAbuseMenuRoact2": false,
    "FFlagEnableReportAbuseMenuLayerOnV3": false
}
```

### Disable Self View
```json
{
    "FFlagCoreGuiTypeSelfViewPresent": false
}
```

### Chat Keylogger
```json
{
    "FFlagDebugTextBoxServiceShowOverlay": true
}
```

### Return Old Voice Chat Bubble
> [!WARNING]
> This disables avatar chat.
```json
{
    "DFFlagFacialAnimationStreaming2": false
}
```

### Hide GUI
> [!NOTE]
> Set to a id of a group you are in.
```json
{
    "DFIntCanHideGuiGroupId": 0
}
```

### Set Custom Font Size
```json
{
    "FIntFontSizePadding": 1
}
```

### Disable Translation settings
> [!NOTE]
> For some reason the "Give Translation Feedback" button stays.
```json
{
    "FFlagChatTranslationSettingEnabled3": false
}
```


### Disable VR toggle
```json
{
    "FFlagAlwaysShowVRToggleV3": false
}
```

### Disable Fullscreen Titlebar
```json
{
    "FIntFullscreenTitleBarTriggerDelayMillis": -1
}
```

### Chrome UI
> [!CAUTION]
> May cause the game to not load in certain games.
```json
{
    "FFlagEnableInGameMenuChrome": true
}
```

### Chrome Pin Chat
```json
{
    "FFlagEnableChromePinnedChat": true
}
```

# QOL (Quality Of Life)

### Voice Chat Volume
> [!NOTE]
> Default value is 1000 (in thousandths).
```json
{
    "DFIntVoiceChatVolumeThousandths": 1000
}
```

### Disable AD Portals
```json
{
    "FFlagAdServiceEnabled": false
}
```

### Scroll Speed
```json
{
    "FIntScrollWheelDeltaAmount": 0
}
```

### Disable Telemetry
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
- You can make any flag, place (game) specific by putting "_PlaceFilter" at the end of the flag. In the Value section, the value for the flag then put a semi-colon (;) and the place ID after. (You can add more by putting another ID after another semi-colon (;))

xample:
```json
{
    "DFIntTaskSchedulerTargetFps_PlaceFilter": "0;12345;246810"
}
```
