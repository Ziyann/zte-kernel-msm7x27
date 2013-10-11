#
# Makefile for misc devices that really don't fit anywhere else.
#
obj-$(CONFIG_ANDROID_PMEM)	+= pmem.o
obj-$(CONFIG_FM_SI4708)		+= fm_si4708.o
obj-$(CONFIG_UID_STAT)		+= uid_stat.o
obj-y				+= eeprom/
obj-$(CONFIG_TSIF) += msm_tsif.o
msm_tsif-objs := tsif.o
obj-$(CONFIG_TSIF_CHRDEV) += tsif_chrdev.o
#ZTE_MODEMCTL_WXW, 20100414, begin, add the modemctl driver module for R750 item
obj-$(CONFIG_MODEMCTL)		+= modemctl/
#ZTE_MODEMCTL_WX
obj-$(CONFIG_MSM_MEMORY_LOW_POWER_MODE_SUSPEND_DEEP_POWER_DOWN) \
	+= msm_migrate_pages.o
