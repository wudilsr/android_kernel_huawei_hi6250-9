ccflags-y += -I$(src)			# needed for trace events

obj-$(CONFIG_ANDROID_BINDER_IPC)	+= binder.o binder_alloc.o
obj-$(CONFIG_ANDROID_BINDER_IPC_SELFTEST) += binder_alloc_selftest.o
obj-$(CONFIG_HUAWEI_BINDER_ASHMEM)	+= binder_ashmem.o

ifeq ($(BUILD_WITH_HARMONY), true)			# zidane
ccflags-y += -DCONFIG_HARMONY_BINDER_HANDLE
endif