This repo already contains a compiled module for RPI3 (not +)
To install it just run:

  sudo make install
  sudo modprobe 8821cu

## Compiling and installing

make
sudo make install
sudo modprobe 8821cu

### RPI3

Makefile is already configured for RPI 3 (not +)

### RPI3+ change:

CONFIG_PLATFORM_ARM_RPI = n
CONFIG_PLATFORM_ARM_RPI3 = y

### NOTE: Not tested for RPI2, RPI4 and over, but give it a try
