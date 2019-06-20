ifneq ($(KERNELRELEASE),)
	obj-m := hello_zed.o

else
	KERNELDIR ?= /home/andy88980/Desktop/Zynq/linux-xlnx

default:
	$(MAKE) -C $(KERNELDIR) M=$(PWD) modules
clean :
	$(MAKE) -C $(KERNELDIR) M=$(PWD) clean

endif

help:
