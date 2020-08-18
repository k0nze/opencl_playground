all: list_devices list_platforms

list_platforms: list_platforms.c
	gcc list_platforms.c -o list_platforms -lOpenCL

list_devices: list_devices.c
	gcc list_devices.c -o list_devices -lOpenCL

.PHONY clean:
	-rm list_platforms
	-rm list_devices
