#
# Makefile for the sensor drivers.
#

# Each configuration option enables a list of files.
obj-$(CONFIG_SENSORS_SSP_MPU6500)	+= accel_mpu6500.o gyro_mpu6500.o
obj-$(CONFIG_SENSORS_SSP_TMG399X)       += light_tmg399x.o prox_tmg399x.o gesture_tmg399x.o
obj-$(CONFIG_SENSORS_SSP_AK09911)	+= magnetic_ak09911.o
obj-$(CONFIG_SENSORS_SSP_BMP280)	+= pressure_bmp280.o
obj-$(CONFIG_SENSORS_SSP_LPS25H)	+= pressure_lps25h.o
obj-$(CONFIG_SENSORS_SSP_ATUC128L5HAR)	+= mcu_atuc128l5har.o
obj-$(CONFIG_SENSORS_SSP_MOBEAM)	+= barcode_emul_tmg3992.o
