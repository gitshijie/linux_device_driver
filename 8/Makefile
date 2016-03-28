obj-m += globalfifo.o

#KER_DIR := /home/shijie/work/fsl-release-bsp/build-x11/tmp/work-shared/imx6ulevk/kernel-source
#KER_DIR := /home/shijie/work/tools/linux-4.0.1
KER_DIR := /home/shijie/work/tmp/dc200/linux-3.15
PWD := $(shell pwd)

all:
	make -C $(KER_DIR) M=$(PWD) modules

clean:
	make -C $(KER_DIR) M=$(PWD) clean
