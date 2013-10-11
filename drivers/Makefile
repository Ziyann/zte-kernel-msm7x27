#
# Makefile for the Linux kernel device drivers.
#
# 15 Sep 2000, Christoph Hellwig <hch@infradead.org>
# Rewritten to use lists instead of if-statements.
#

obj-y				+= gpio/
obj-$(CONFIG_PCI)		+= pci/
obj-y				+= video/
obj-y				+= idle/
obj-$(CONFIG_ACPI)		+= acpi/
# PnP must come after ACPI since it will eventually need to check if acpi
# was used and do nothing if so
obj-$(CONFIG_PNP)		+= pnp/

# char/ comes before serial/ etc so that the VT console is the boot-time
# default.
obj-y				+= char/

# gpu/ comes after char for AGP vs DRM startup
obj-y				+= gpu/

obj-$(CONFIG_CONNECTOR)		+= connector/

obj-y				+= serial/
obj-y				+= base/ block/ misc/
obj-$(CONFIG_SCSI)		+= scsi/
obj-$(CONFIG_MTD)		+= mtd/
obj-y				+= net/
obj-$(CONFIG_UIO)		+= uio/
obj-$(CONFIG_PCCARD)		+= pcmcia/
obj-$(CONFIG_SBUS)		+= sbus/
obj-$(CONFIG_USB_OTG_UTILS)	+= usb/otg/
obj-$(CONFIG_USB)		+= usb/
obj-$(CONFIG_USB_MUSB_HDRC)	+= usb/musb/
obj-$(CONFIG_PCI)		+= usb/
obj-$(CONFIG_USB_GADGET)	+= usb/gadget/
obj-$(CONFIG_DIAG_CHAR)         += char/diag/
obj-$(CONFIG_USB_FUNCTION)	+= usb/function/
obj-$(CONFIG_SERIO)		+= input/serio/
obj-$(CONFIG_INPUT)		+= input/
obj-$(CONFIG_RTC_LIB)		+= rtc/
obj-y				+= i2c/ media/
obj-$(CONFIG_PPS)		+= pps/
obj-$(CONFIG_POWER_SUPPLY)	+= power/
obj-$(CONFIG_HWMON)		+= hwmon/
obj-$(CONFIG_THERMAL)		+= thermal/
obj-$(CONFIG_WATCHDOG)		+= watchdog/
obj-$(CONFIG_PHONE)		+= telephony/
obj-$(CONFIG_MD)		+= md/
obj-$(CONFIG_BT)		+= bluetooth/
obj-$(CONFIG_EDAC)		+= edac/
obj-y				+= lguest/
obj-$(CONFIG_CPU_FREQ)		+= cpufreq/
obj-$(CONFIG_CPU_IDLE)		+= cpuidle/
obj-$(CONFIG_MMC)		+= mmc/
obj-$(CONFIG_MEMSTICK)		+= memstick/
obj-$(CONFIG_NEW_LEDS)		+= leds/
obj-$(CONFIG_SWITCH)		+= switch/
obj-$(CONFIG_SGI_SN)		+= sn/
obj-y				+= firmware/
obj-$(CONFIG_CRYPTO)		+= crypto/
obj-$(CONFIG_GENERIC_TIME)	+= clocksource/
obj-$(CONFIG_DMA_ENGINE)	+= dma/
obj-$(CONFIG_HID)		+= hid/
obj-$(CONFIG_OF)		+= of/
obj-$(CONFIG_SSB)		+= ssb/
obj-$(CONFIG_STAGING)		+= staging/
obj-y				+= platform/
