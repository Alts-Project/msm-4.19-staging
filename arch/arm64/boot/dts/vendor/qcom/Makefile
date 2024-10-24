ifeq ($(PLATFORM_VERSION_CODENAME),)
ifneq ($(CONFIG_MACH_XIAOMI),y)
dtb-$(CONFIG_ARCH_QCOM)	+= apq8016-sbc.dtb msm8916-mtp.dtb
dtb-$(CONFIG_ARCH_QCOM)	+= msm8996-mtp.dtb
dtb-$(CONFIG_ARCH_QCOM)	+= apq8096-db820c.dtb
endif
endif

dtb-$(CONFIG_MACH_XIAOMI_YSL) += msm8953-ysl.dtb

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb