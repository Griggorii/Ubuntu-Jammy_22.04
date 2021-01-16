# chromium-browser_87.0.4280.88-0ubuntu0.20.04_amd64.deb , wayland perfomance , super stable ungoogled chromium
chromium-browser_87.0.4280.88-0ubuntu0.20.04_amd64.deb

deb-package: https://github.com/Griggorii/chromium-browser_87.0.4280.88-0ubuntu0.20.04_amd64.deb/releases/tag/chromium-browser

$ sudo rm -rf /usr/lib/chromium-browser

$ cd /var/lib/dpkg/info && rm -rf chromium-browser*

Double installation !

$ sudo dpkg -i ./chromium-browser_87.0.4280.88-0ubuntu0.20.04_amd64.deb

$ sudo dpkg -i ./chromium-browser_87.0.4280.88-0ubuntu

Local State copy setting too:

$ mkdir ~/.config/chromium ~/.config/chromium/Default && cp 'Local State' ~/.config/chromium

Run check profile chrome://gpu/

Wayland chromium flags griggorii setting example:

X name version browser opera , google-chrome , Brave-Browser , yandex , palemoon , chromium-browser

Varinat run chromium-browser rename browser:

chromium-browser --enable-pinch --enable-features=UseOzonePlatform --ozone-platform=wayland --cross-origin-isolated@1 --enable-ephemeral-guest-profiles-on-desktop@1 --enable-experimental-web-platform-features --enable-future-v8-vm-features@1 --enable-generic-sensor-extra-classes@1 --enable-google-srp-isolated-prerender-nsp --enable-google-srp-isolated-prerender-probing@1 --enable-google-srp-isolated-prerenders@10 --enable-quic@1 --enable-webrtc-pipewire-capturer@1 --enable-zero-copy@1 --force-color-profile@1 --hardware-media-key-handling@1 --installed-apps-in-cbd@1 --load-media-router-component-extension@1 --omnibox-tab-switch-suggestions@1 --pull-to-refresh@2 --tab-groups@1 --tab-hover-card-images@1 --use-sync-sandbox --flag-switches-begin --enable-accelerated-video-decode --enable-experimental-web-platform-features --isolated-prerender-nsp-enabled --enable-gpu-rasterization --enable-quic --enable-zero-copy --force-color-profile=srgb --ignore-gpu-blocklist --ignore-previews-blacklist --load-media-router-component-extension=1 --sync-url=https://chrome-sync.sandbox.google.com/chrome-sync/alpha --enable-features=UseOzonePlatform,ClickToCallUI,CrossOriginIsolated,GenericSensorExtraClasses,HardwareMediaKeyHandling,InstalledAppsInCbd,IsolatePrerenders,IsolatePrerendersMustProbeOrigin,OmniboxTabSwitchSuggestions,TabGroups,TabHoverCardImages,V8VmFuture,Vulkan --disable-features=EnableTLS13EarlyData,FontAccess,ScrollUnification --flag-switches-end --flag-switches-begin --enable-experimental-web-platform-features --isolated-prerender-nsp-enabled --enable-quic --enable-zero-copy --force-color-profile=srgb --load-media-router-component-extension=1 --sync-url=https://chrome-sync.sandbox.google.com/chrome-sync/alpha --enable-features=UseOzonePlatform,ClickToCallUI,CrossOriginIsolated,GenericSensorExtraClasses,HardwareMediaKeyHandling,InstalledAppsInCbd,IsolatePrerenders,IsolatePrerendersMustProbeOrigin,OmniboxTabSwitchSuggestions,TabGroups,TabHoverCardImages,V8VmFuture,Vulkan,IsolatePrerenders:max_srp_prefetches/15 --flag-switches-end



