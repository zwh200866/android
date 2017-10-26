# android
android study note
init commit.修改了一些配置文件
device/softwinner/tulip-ococci/init.sun50iw1p1.rc
device/softwinner/tulip-ococci/tulip_ococci.mk对android 预安装包的说明
PRODUCT_PACKAGES += \    WallpaperPicker \    ESFileExplorer \    VideoPlayer \ Saturn \    Bluetooth \ readdemo \ testkey \    Update
增加了testkey安装包的配置需要 在device/softwinner/common/prebuild/preinstallapk/Testkey中加入testkey.apk和android.mk
