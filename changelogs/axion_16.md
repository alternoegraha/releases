# 20250820
- Include Camera app from GrapheneOS
- Sync to latest AxionAOSP sources
- Launcher3/Pulse Launcher: Revert old Circle to Search commit [personal change]
> That commit is redudant, since AOSP Launcher3 literally has a code for Contextual Search feature since Android 15 QPR2+. It only needs ACCESS_CONTEXTUAL_SEARCH permission on Launcher3 manifest xml sources, overlay configs on vendor, and sysconfig xml for enabling contextual search feature on GMS. That commit also breaks vibration effect during press-and-hold the navigation gesture pill when invoking Circle to Search.

# 20250819_hotfix
- Sync source to latest (fixed issue with clock size in lock screen)

# 20250819
- Initial build
