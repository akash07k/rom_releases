## EvolutionX
### 21st September, 2022

* Huge device overlay updates
* Enabled display async powermode
* configs: Updated powerhint (Remove top-app boost. All it does is to add extra stutters and increase power consumption)
* Enable Audio Support for Hearing Aids
* configs: perf: Do not balance msm_drm and kgsl-3d0 IRQs. These are critical for display performance and should not be balanced in order to improve latency and responsiveness.
* Enabled the status for turbo charging
* Added the support for handling audio direction changes between major call states
* Added the support for stopping battery drain by some major common apps such as WhatsApp, Telegram, Truecaller etc.
* Rom will correctly identify that device has fingerprint sensor in power button
* Specify if the fingerprint hardware support gestures (Experimental)
* Use SkiaGL threaded renderer Used on Pixel devices. This should fix strange video glitches with Vulkan.
* Add MiSoundFX blobs
* gpt-utils: Update PTN_SWAP_LIST to reflect partition entry changes   to BOOT LUN and handle "multiimgoem", "multiimgqti"   partitions, similar to other BOOT LUN partitions.
* Disabled dataroaming by default
* Updated and cleaned up the vendor blobs
* Kernel updates
* Many more bug fixes and source updates
