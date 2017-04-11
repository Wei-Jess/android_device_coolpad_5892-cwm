# android_device_coolpad_5892-cwm
Build CWM Recovery V6.0.5.1 for Coolpad 5892


========================================================

source build/envsetup.sh

make -j4 otatools

lunch cm_5892-userdebug

make -j4 recoveryimage

========================================================
