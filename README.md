# dumb-program-fixes
this is pretty much a list of dumb things i have seen and the fixes for them

# screen tearing on x11 with picom

add --experimental-backends as an argument for picom when it starts

# broadcom drivers not working

install broadcom-wl
add module_blacklist=b43,b43legacy,ssb,bcm43xx,brcm80211,brcmfmac,brcmsmac,bcma to kernel parameters
