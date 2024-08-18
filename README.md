# Graphical Settings

### Disable PostFX
[Link To Original Post](https://discord.com/channels/1099468797410283540/1150655466830041128)
```json
{
    "FFlagDisablePostFx": true
}
```

### Change Rendering Mode
[Link To Original Post](https://discord.com/channels/1099468797410283540/1173220043266457660)

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

[Link To Original Post](https://discord.com/channels/1099468797410283540/1165003069814226964)
```json
{
    "FFlagNewLightAttenuation": true
}
```

### Disable Baked Shadows

[Link To Original Post](https://discord.com/channels/1099468797410283540/1173308420133232750)
```json
{
    "DFFlagDebugPauseVoxelizer": true
}
```

### Force LOD For All Meshes
[Link To Original Post](https://discord.com/channels/1099468797410283540/1146963091775553536)
```json
{
    "DFIntCSGLevelOfDetailSwitchingDistance":0,
    "DFIntCSGLevelOfDetailSwitchingDistanceL12":0,
    "DFIntCSGLevelOfDetailSwitchingDistanceL23":0,
    "DFIntCSGLevelOfDetailSwitchingDistanceL34":0
}
```

### Remove Player Clothing Textures
[Link To Original Post](https://discord.com/channels/1099468797410283540/1207722310195486720)
```json
{
    "DFIntTextureCompositorActiveJobs": 0
}
```

### Skip MipMaps
> [!NOTE]  
>
> Set to anything below 0 to basically delete all textures.

[Link To Original Post](https://discord.com/channels/1099468797410283540/1247944649822441634)

```json
{
  "FIntDebugTextureManagerSkipMips": 0
}
```

### Force Texture Quality
> [!NOTE]  
>
> Set to any value from 0 to 3.

[Link To Original Post](https://discord.com/channels/1099468797410283540/1150312397274357871)

```json
{
    "DFFlagTextureQualityOverrideEnabled": true,
    "DFIntTextureQualityOverride": 3
}
```

### Uncap FPS
[Link To Original Post](https://discord.com/channels/1099468797410283540/1245740082841780224)
```json
{
    "DFIntTaskSchedulerTargetFps": 9999,
    "FFlagTaskSchedulerLimitTargetFpsTo2402": false
}
```

### FRM Quality Level Override
> [!NOTE]
>
> Forces graphics quality. Render distance will still incerase however. Values range from 1 - 10 and 1 - 21 if using 21 bars.

[Link To Original Post](https://discord.com/channels/1099468797410283540/1184157587562823780)

```json
{
    "DFIntDebugFRMQualityLevelOverride": 1
}
```

### Enable MSAA
> [!CAUTION]
>
> Values over 4 will cause viewports (3D Models) to be invisible.

[Link To Original Post](https://discord.com/channels/1099468797410283540/1145231575173316608)

```json
{
    "FIntDebugForceMSAASamples": 0
}
```

### Low Poly Terrain
[Link To Original Post](https://discord.com/channels/1099468797410283540/1194889014981967932)
```json
{
    "FIntTerrainArraySliceSize": 8
}
```


### Remove Player Shadows
[Link To Original Post](https://discord.com/channels/1099468797410283540/1147409993302282240)
```json
{
    "FIntRenderShadowIntensity": 0
}
```

### ShadowMap Bias
[Link To Original Post](https://discord.com/channels/1099468797410283540/1152409274933317712)
```json
{
    "FIntRenderShadowmapBias": 75
}
```

# UI/UX (User Interface)

### Rename Charts Tab Back To Discover
[Link To Original Post](https://discord.com/channels/1099468797410283540/1254997424116863048)
```json
{
    "FFlagLuaAppChartsPageRenameIXP": false
}
```

### Rainbow UI / Viewport
[Link To Original Post](https://discord.com/channels/1099468797410283540/1183833667945103421)
```json
{
    "FFlagDebugDisplayUnthemedInstances": true
}
```

### Position Update UI/UX
[Link To Original Post](https://discord.com/channels/1099468797410283540/1267153647033384980)
```json
{
    "FFlagAccessoryAdjustmentEnabled2":true,
    "FFlagHumanoidDescriptionUseInstances5":true,
    "FFlagHumanoidDescriptionFallback":true,
    "FFlagEnableNonUAPAccessoryAdjustment":true,
    "FFlagAXAccessoryAdjustment": true,
    "FFlagAXAccessoryAdjustmentIXPEnabled": true,
    "FFlagAXAccessoryAdjustmentIXPEnabledForAll": true,
    "FFlagAXAvatarFetchResultCamelCase": true,
    "FFlagAccessoryAdjustmentEnabled3": true
}
```

### Chrome FTUX (First Time User Experience)
[Link To Original Post](https://discord.com/channels/1099468797410283540/1271975274719875104)
```json
{
    "FFlagDebugEnableVRFTUXExperienceInStudio": true,
    "FFlagEnableChromeFTUX": true,
    "FFlagEnableVRFTUXExperienceV2": true
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

### Disable Chat Translation
[Link To Original Post](https://discord.com/channels/1099468797410283540/1204335548160938025)
```json
{
    "FFlagChatTranslationSettingEnabled3": false
}
```

### Fix Beta Badge Dupe
[Link To Original Post](https://discord.com/channels/1099468797410283540/1194581451857997844)
```json
{
    "FFlagFixDupeBetaBadge": true
}
```

### Disable Haptics Toggle
[Link To Original Post](https://discord.com/channels/1099468797410283540/1268891182302494772)
```json
{
    "FFlagAddHapticsToggle": false
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
[Link To Original Post](https://discord.com/channels/1099468797410283540/1171224254352732201)
```json
{
    "FFlagInGameMenuHomeButton": false
}
```

### Chrome Pin Chat
[Link To Original Post](https://discord.com/channels/1099468797410283540/1177942263100362792)
```json
{
    "FFlagEnableChromePinnedChat": true
}
```

### Hide GUI
> [!NOTE]  
>
> Set to a id of a group you are in.

[Link To Original Post](https://discord.com/channels/1099468797410283540/1149975417818722314)

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

### Cleaner ESC Settings Menu
[Link To Original Post](https://discord.com/channels/1099468797410283540/1189607691849564230)
```json
{
    "FFlagEnableAudioOutputDevice": false,
    "FIntV1MenuLanguageSelectionFeaturePerMillageRollout": 0,
    "FFlagChatTranslationSettingEnabled3": false
}
```

### Disable "Output device" UI from Escape Menu
[Link To Original Post](https://discord.com/channels/1099468797410283540/1184771500558012416)
```json
{
    "FFlagEnableAudioOutputDevice": false
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
> [!CAUTION]
>
> May cause the game to not load in certain games.

[Link To Original Post](https://discord.com/channels/1099468797410283540/1156809517883985960)
```json
{
    "FFlagEnableInGameMenuChrome": true
}
```

# QOL (Quality Of Life)

### Disable VR Collision Fade
[Link To Original Post](https://discord.com/channels/1099468797410283540/1258459675314360493)
```json
{
  "FFlagViewCollisionFadeToBlackInVR": "False"
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
> [!NOTE]  
>
> Does not disable all telemetry.

[Link To Original Post](https://discord.com/channels/1099468797410283540/1155133604389728396)

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

# Voice Chat

### Voice Chat Volume
[Link To Original Post](https://discord.com/channels/1099468797410283540/1208100665138745424)
> [!NOTE]
>
> Default value is 1000 (in thousandths).
```json
{
    "DFIntVoiceChatVolumeThousandths": 1000
}
```

### Return Old Voice Chat Bubble [WARNING: DISABLES AVATAR CHAT]
[Link To Original Post](https://discord.com/channels/1099468797410283540/1139960093132210227)
```json
{
    "DFFlagFacialAnimationStreaming2": false
}
```

# Misc 

### Enable New Camera Mode
[Link To Original Post](https://discord.com/channels/1099468797410283540/1237065400315805789)
```json
{
    "FFlagNewCameraControls": true
}
```

### Enable Audio Occlusion
[Link To Original Post](https://discord.com/channels/1099468797410283540/1239510612577620039)
```json
{
    "FFlagDebugEnableDirectAudioOcclusion2": true
}
```

### Make Your Flags Work On Certain Games Only
[Link To Original Post](https://discord.com/channels/1099468797410283540/1239329199404355584)


### Sky's Flag Collection
[Link To Original Post](https://discord.com/channels/1099468797410283540/1139962301991104582)

### Surfing The Web Inside of Roblox
[Link To Original Post](https://discord.com/channels/1099468797410283540/1165211319583117443)
```json
{
    "FFlagTopBarUseNewBadge": true,
    "FStringTopBarBadgeLearnMoreLink": "https://example.com",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://example.com"
}
```

### Notes
> Roblox was supposed to kill fastflags like 6 months ago. Now here I am updating this collection again. Roblox really trolled me with this one.