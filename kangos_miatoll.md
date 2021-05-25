Changelog - 25/05/2021

    * Fixxed Moto Dolby sepolicies
    * Fixed lag on getting network service after boot
    * Import USB init scripts from stock 
    * Use Google's schedutil rate-limits 
    * Use cpusets from sunfish 
    * Added device mask (redfin for good cts)
    * Enable boosted color mode by default 
    * Enable back display SVI configuration
    * Advertise fingerprint on power button 
    * Add 4MB overhead space to super partition 
    * Remove bogus tombstone directory directives 
    * Switch to prebuilt audio hal 
    * Update media configs from curtana qssi-user 11 RKQ1.200826.002.7.RJWMIXM release-keys
    * Enable QCRIL radio power saving 
    * Set voice call volume steps to 6 
    * Override few audio props via init 
    * Upstreamed Etherious kernel to v4.14.232
    * minor changes...

 Notes:

    * No
----------------------------------------------------------------------------------------------------

Changelog - 07/04/2021

    * Added Moto Dolby 04.01.0931
    * Fully Fixed Miuicamera got more than 150 reprts that it works so if you have problem, try to flash last fw or miui.
    * Dispalysettings: Added more nocutout features - You can use Nothbarkiller from dev options (disabled by default)
    * Applock works in fully enforcment- denials added
    * April security patch
    * Updated Thermal - No more heatness ( Thx to Kobux) 
    * Upstreamed Etherious kernel to v4.14.228
    * minor changes...

 Notes:

    * No
----------------------------------------------------------------------------------------------------

Changelog - 14/03/2021

    * Fixed google sound recorder
    * Fully Fixed ANX v185 camera (third cam apps works)
    * Dispalysettings: Added nocutout features
    * Upstreamed kernel to v4.14.226
    * minor changes...

 Notes:

    * No
----------------------------------------------------------------------------------------------------

Changelog - 14/03/2021

    *  XiaomiParts: Add dynamic thermal profile implementation
    *  XiaomiParts: Drop support for browser thermal profile 
    *  XiaomiParts: Set dynamic thermal interval to 5 sec
    *  XiaomiParts: Add switchbar to disable dynamic thermal 
    *  XiaomiParts: Switch to TaskStackListener 
    *  XiaomiParts: Increase BootReceiver priority 
    *  XiaomiParts: Add ACTION_SCREEN_ON intent filter 
    *  XiaomiParts: Add GPU Boost
    *  XiaomiParts: Fix fastcharge toggle icon's tint 
    *  Guard tree with soong namespace
    *  Add kpti=off to boot command line 
    *  overlay: Configure SQLite to operate in MEMORY mode 
    *  Update TetheringOverlay & WifiOverlay 
    *  Force disable wide color display 
    *  overlay: Set fast charging indicator threshold to 10.8W
    *  Set TARGET_INPUTDISPATCHER_SKIP_EVENT_KEY
    *  Don't pin camera app in memory 
    *  overlay: Pin surfaceflinger
    *  Enable usage of dex2oat64 
    *  Remove dexpreopt flags that are default
    *  Fix mic issues in apps like WhatsApp 
    *  wifi: enable QPower and Deep Sleep at the same time 
    *  audio: update audio_io_policy for VoIP 
    *  audio: enforce 24-bit audio for offload playback 
    *  Force triple frame buffers
    *  rootdir: zram tuning
    *  wlan: Enable DFS channel scanning in P2P search.
    *  wlan: Relax WiFi re-association RSSI thresholds. 
    *  wlan: Disable logging.
    *  wlan: Smarter decisions on whether to use a 2- or 5Ghz… 
    *  rootdir: Launch bootanimation early 
    *  audio: Define acdb ids for voice recorder 
    *  KERNEL UPSTREAMED TO V4.14.225 InnOvaTioN#R
        
Notes:

    * No
----------------------------------------------------------------------------------------------------

Changelog - 24/02/2021

    * sm6250-common: XiaomiParts: Add Fastcharge toggle 
    * sm6250-common: XiaomiParts: Removed some useless Doze blobs
    * sm6250-common: Added CustomDoze 
    * sm6250-common: Allow vendor read access to 'ro.camera' property 
    
Notes:

    * No
----------------------------------------------------------------------------------------------------

Changelog - 17/02/2021

    * Initial build

Notes:

    * Clean flash if you're coming from unofficial build
----------------------------------------------------------------------------------------------------
