# 酷派5267 编译TWRP 基础device tree
##操作步骤：<br> 
mkdir twrp <br> 
cd twrp <br> 
repo init -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-6.0 <br>
repo sync <br>
git clone https://github.com/lpxx50117/android_device_Coolpad_Coolpad5267.git device/Coolpad/Coolpad5267 <br>
. build/envsetup.sh <br>
lunch omni_Coolpad5267-userdebug <br>
mka recoveryimage <br>


