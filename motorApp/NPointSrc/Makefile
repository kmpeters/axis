TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# Build an IOC support library

LIBRARY_IOC += NPointMotor

# axisRecord.h will be created from axisRecord.dbd
# install devMotorSoft.dbd into <top>/dbd
DBD += NPointMotorSupport.dbd

# The following are compiled and added to the Support library
NPointMotor_SRCS += C300MotorDriver.cpp

NPointMotor_LIBS += axis
NPointMotor_LIBS += asyn
NPointMotor_LIBS += $(EPICS_BASE_IOC_LIBS)

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

