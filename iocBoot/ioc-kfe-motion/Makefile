IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.2.4
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = plc-kfe-motion
PROJECT_PATH := ../../plc-kfe-motion/plc-kfe-motion.tsproj
PLC = kfe_motion

PYTMC_OPTS :=
PREFIX = PLC:KFE:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base
