# 酷派5267 编译TWRP 基础device tree
操作步骤：
mkdir twrp
cd twrp
repo init -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-6.0
repo sync
git clone https://github.com/lpxx50117/android_device_Coolpad_Coolpad5267.git device/Coolpad/Coolpad5267
. build/envsetup.sh
lunch omni_Coolpad5267-userdebug
mka recoveryimage


