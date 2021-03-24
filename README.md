# HuaweiBWRemove
Describes how to remove the bloatware on a Huawei phone (Mate 10 Pro)

## Commands

### List devices 

Accept connection on phone;
Developer mode and usb debugging must be turned on
```shell
adb devices
```

### Connect to shell
```shell
adb shell
```

### Remove a package
```shell
pm uninstall -k --user 0 package_name
```

### Reinstall a package 
```shell
cmd package install-existing package_name
```

### List all installed packages
```shell
pm list packages -f
```

### My list (Mate 10 Pro)

```shell
pm uninstall -k --user 0 com.huawei.videoeditor
pm uninstall -k --user 0 com.amazon.appmanager 
pm uninstall -k --user 0 com.amazon.mShop.android.shopping 
pm uninstall -k --user 0 com.android.email
pm uninstall -k --user 0 com.android.bookmarkprovider
pm uninstall -k --user 0 com.android.partnerbrowsercustomizations.tmobile
pm uninstall -k --user 0 com.android.providers.partnerbookmarks
pm uninstall -k --user 0 com.android.partnerbrowsercustomizations
pm uninstall -k --user 0 com.android.stk
pm uninstall -k --user 0 com.baidu.input_huawei 
pm uninstall -k --user 0 com.huawei.appmarket
pm uninstall -k --user 0 com.huawei.phoneservice
pm uninstall -k --user 0 com.huawei.hwid
pm uninstall -k --user 0 com.huawei.android.hwpay
pm uninstall -k --user 0 com.huawei.android.remotecontroller
pm uninstall -k --user 0 com.huawei.android.tips
pm uninstall -k --user 0 com.huawei.browser
pm uninstall -k --user 0 com.huawei.compass
pm uninstall -k --user 0 com.huawei.contactscamcard
pm uninstall -k --user 0 com.huawei.health
pm uninstall -k --user 0 com.huawei.search
pm uninstall -k --user 0 com.huawei.tips
pm uninstall -k --user 0 com.huawei.vassistant
pm uninstall -k --user 0 com.huawei.wallet
pm uninstall -k --user 0 com.ironsource.appcloud.oobe.huawei
pm uninstall -k --user 0 com.facebook.appmanager
pm uninstall -k --user 0 com.facebook.system
pm uninstall -k --user 0 com.facebook.katana
pm uninstall -k --user 0 com.facebook.services
pm uninstall -k --user 0 com.swiftkey.swiftkeyconfigurator
pm uninstall -k --user 0 com.touchtype.swiftkey
pm uninstall -k --user 0 com.huawei.gameassistant
pm uninstall -k --user 0 com.android.mediacenter
pm uninstall -k --user 0 com.huawei.hifolder
pm uninstall -k --user 0 com.huawei.hicard
pm uninstall -k --user 0 com.huawei.hidisk
pm uninstall -k --user 0 com.huawei.hiview
pm uninstall -k --user 0 com.huawei.iaware
pm uninstall -k --user 0 com.huawei.android.thememanager
pm uninstall -k --user 0 com.huawei.android.chr
pm uninstall -k --user 0 com.huawei.nearby
pm uninstall -k --user 0 com.huawei.android.FloatTasks
pm uninstall -k --user 0 com.huawei.desktop.systemui
pm uninstall -k --user 0 com.huawei.intelligent
pm uninstall -k --user 0 com.huawei.parentcontrol
pm uninstall -k --user 0 com.huawei.desktop.explorer
pm uninstall -k --user 0 com.android.soundrecorder
pm uninstall -k --user 0 com.huawei.hiviewtunnel
pm uninstall -k --user 0 com.hisi.mapcon
pm uninstall -k --user 0 com.huawei.android.instantshare
pm uninstall -k --user 0 com.google.android.apps.tachyon
pm uninstall -k --user 0 com.huawei.livewallpaper.matetwenty
pm uninstall -k --user 0 com.google.android.music
pm uninstall -k --user 0 com.huawei.HwMultiScreenShot
pm uninstall -k --user 0 com.example.android.notepad
pm uninstall -k --user 0 com.huawei.languagedownloader
pm uninstall -k --user 0 com.huawei.hwstartupguide
pm uninstall -k --user 0 com.android.calllogbackup
pm uninstall -k --user 0 com.huawei.stylus.floatmenu
pm uninstall -k --user 0 com.huawei.contactscamcard
pm uninstall -k --user 0 com.huawei.hitouch
pm uninstall -k --user 0 com.huawei.android.wfdft
pm uninstall -k --user 0 com.android.wallpaper.livepicker
pm uninstall -k --user 0 com.qeexo.smartshot
pm uninstall -k --user 0 com.huawei.android.instantonline
pm uninstall -k --user 0 com.huawei.pcassistant
pm uninstall -k --user 0 com.huawei.scanner
pm uninstall -k --user 0 com.android.huawei.HiMediaEngine
pm uninstall -k --user 0 com.android.deskclock
pm uninstall -k --user 0 com.huawei.hwdetectrepair
pm uninstall -k --user 0 com.huawei.android.karaoke
pm uninstall -k --user 0 com.huawei.bd
pm uninstall -k --user 0 com.huawei.lbs
pm uninstall -k --user 0 com.huawei.vassistant
pm uninstall -k --user 0 com.huawei.android.totemweather
pm uninstall -k --user 0 com.huawei.mw
pm uninstall -k --user 0 com.android.calendar
pm uninstall -k --user 0 com.huawei.powergenie
pm uninstall -k --user 0 com.huawei.android.hwaps
```
