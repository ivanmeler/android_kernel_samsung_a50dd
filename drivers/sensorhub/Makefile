#
# Makefile for the sensor hub drivers.
#

# Each configuration option enables a list of files.
obj-$(CONFIG_SENSORS_SSP)		+= ssp_platform.o ssp_data.o ssp_comm.o ssp_debug.o ssp_dev.o ssp_sysfs.o sensors_core.o \
					   ssp_iio.o ssp_scontext.o ssp_sensor_dump.o ssp_dump.o ssp_injection.o\
                                           factory/
#grip_sensor
obj-$(CONFIG_SENSORS_A96T3X6)		+= a96t3x6.o
obj-$(CONFIG_SENSORS_TC3XXK)  		+= tc3xxk.o
