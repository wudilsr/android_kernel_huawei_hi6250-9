ccflags-y += -I$(src)			# needed for trace events

ifeq ($(BUILD_WITH_HARMONY), true)
ccflags-y += -DCONFIG_HARMONY_LOWMEMORYKILLER_OPTIMIZE
endif

obj-y					+= ion/
obj-$(CONFIG_FIQ_DEBUGGER)		+= fiq_debugger/

obj-$(CONFIG_ASHMEM)			+= ashmem.o
obj-$(CONFIG_ANDROID_LOW_MEMORY_KILLER)	+= lowmemorykiller.o
obj-$(CONFIG_ANDROID_INTF_ALARM_DEV)	+= alarm-dev.o
obj-$(CONFIG_ANDROID_VSOC)              += vsoc.o
obj-$(CONFIG_HISI_SMART_RECLAIM)	+= smart_reclaim.o
obj-$(CONFIG_HW_LOGGER)				+= hwlogger/
obj-$(CONFIG_HUAWEI_RCC)		+= rcc.o
