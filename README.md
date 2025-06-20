# android-studio-
android studio自定义个人偏好


1、工具栏：view->apprearance->toolbar

2、tab:
show tab in one row
tab limmit
open new tabs in end

3、调出git保存代码
VCS -> enable version control..

4、打包apk




----------------------------------------------------


adb push app-aht-release.apk /system/app/SYSettingHmi/SYSettingHmi.apk

adb push ./ /system/app/SYSettingHmi/lib/arm64/

adb shell killall com.gxatek.cockpit.car.settings

 git reset --soft HEAD~1
