TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# Build an IOC support library

LIBRARY_IOC += ACRMotor

# axisRecord.h will be created from axisRecord.dbd
# install devMotorSoft.dbd into <top>/dbd
DBD += ACRMotorSupport.dbd

# The following are compiled and added to the Support library
ACRMotor_SRCS += ACRMotorDriver.cpp

ACRMotor_LIBS += axis
ACRMotor_LIBS += asyn
ACRMotor_LIBS += $(EPICS_BASE_IOC_LIBS)

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

