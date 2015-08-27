#Paranoid tree for Moto G (2015)
* Based off https://github.com/MotoG3/android_device_motorola_osprey

Copy pa_config/pa_osprey.mk to vendor/pa/products/
Until patch is taken in the official AOSPA-L android_system_core repository, apply the patch pa_config/0001-init-Add-support-for-gzipped-firmware-files.patch

In your build folder

	cd system/core/
	git am ../../device/motorola/osprey/pa_config/0001-init-Add-support-for-gzipped-firmware-files.patch
	cd ../..

then run ./rom_build.sh osprey

