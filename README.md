# rtl8723bs v5.2.17.1_26955.20180307_COEX20180201-6f52
https://github.com/rockchip-linux/kernel/tree/release-4.4/drivers/net/wireless/rockchip_wlan/rtl8723bs

This driver is the only one I've found so far that consistently works
for me on my NTC CHIP. Ideally some day we can use the mainline
driver, but for now it remains in staging and seems to not work properly
on my NTC CHIP.

Clone this driver and then copy the 8723bs-5.2.17.1 folder into /usr/src/
Then, install with "dkms install -m 8723bs -v 5.2.17.1". You probably
want to blacklist the mainline r8723bs driver while you're at it.
