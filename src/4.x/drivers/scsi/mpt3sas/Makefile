# mpt3sas makefile
ifeq ($(CONFIG_BROADWELL),m)
  EXTRA_CFLAGS+=-DCONFIG_BROADWELL
endif
ifeq ($(CONFIG_BROADWELLNK),m)
  EXTRA_CFLAGS+=-DCONFIG_BROADWELLNK
endif

obj-$(CONFIG_SCSI_MPT3SAS) += mpt3sas.o
mpt3sas-y +=  mpt3sas_base.o     \
		mpt3sas_config.o \
		mpt3sas_scsih.o      \
		mpt3sas_transport.o     \
		mpt3sas_ctl.o	\
		mpt3sas_trigger_diag.o \
		mpt3sas_warpdrive.o
