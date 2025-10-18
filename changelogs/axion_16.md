# 20251017
- Switch default kernel to Nurture-R4 with KernelSU and bpf 5.10 backports
- Switch to `user` build, with fixed AxionAOSP Recovery to make it actually usable with it
- dropped GrapheneOS Camera
- include Aperture Camera by default
- Sync to latest AxionAOSP sources
- Revert "fog: props: Move input surface to CCodec" (causes screen record (and possibly video recording) lagging due to use of c2 swcodec as input source instead of OMX hwcodec)
- fog: props: Make SurfaceFlinger latch all buffers unsignaled

# 20250823
- Updated prebuilt kernel
- Sync to latest AxionAOSP sources
### Personal changes:
- Changed default font to Roboto (Rookery font still available as option on Wallpapers & Style -> Fonts
- Dropped SFProDisplay and Fifa2018 font
- Added Inter (version 4.1) font

# 20250820
- Include Camera app from GrapheneOS
- Sync to latest AxionAOSP sources
### Personal changes:
- Launcher3/Pulse Launcher: Revert old Circle to Search commit [personal change]
> That commit is redudant, since AOSP Launcher3 literally has a code for Contextual Search feature since Android 15 QPR2+. It only needs ACCESS_CONTEXTUAL_SEARCH permission on Launcher3 manifest xml sources, overlay configs on vendor, and sysconfig xml for enabling contextual search feature on GMS. That commit also breaks vibration effect during press-and-hold the navigation gesture pill when invoking Circle to Search.

# 20250819_hotfix
- Sync source to latest (fixed issue with clock size in lock screen)

# 20250819
- Initial build
