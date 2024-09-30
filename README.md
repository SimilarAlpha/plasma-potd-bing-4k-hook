# plasma-potd-bing-4k-hook

Pacman hook to patch KDE Plasma's Picture of the Day Bing wallpaper provider to always use 4K (3840x2160) resolution

# Why?

By default the plugin uses 4K wallpaper only when screen resolution is higher than 1980x1080. Because of high compression full hd wallpapers from Bing have visible JPEG artifacts and look worse than scaled down 4K wallpapers.
This hook patches relevant files when associated package is updated.

# Installation

Copy:  
90-bing-4k-wallpaper.hook to /etc/pacman.d/hooks/ and  
bing-4k-wallpaper to /usr/share/libalpm/scripts/
