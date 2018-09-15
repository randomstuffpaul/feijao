obj-$(CONFIG_FTS_FT5346I) += focaltech_core.o focaltech_ctl.o focaltech_ex_fun.o focaltech_gesture.o focaltech_flash.o
extlibs :=$(srctree)/$(src)/ft_gesture_32bit_lib_v1.0_20140820.a
ldflags-y +=--whole-archive $(extlibs) --no-whole-archive

