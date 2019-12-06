all: list_devices list_platforms

list_platforms: list_platforms.c
	clang -framework OpenCL -Wno-deprecated-declarations list_platforms.c -o list_platforms

list_devices: list_devices.c
	clang -framework OpenCL -Wno-deprecated-declarations list_devices.c -o list_devices

.PHONY clean:
	-rm list_platforms
	-rm list_devices
