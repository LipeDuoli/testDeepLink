# Navigation Component deep link Test

To run the deeplinks, use one of these commands

`adb shell am start -W -a android.intent.action.VIEW -d "deeplink://dashboard/[1-4]"`
`adb shell am start -W -a android.intent.action.VIEW -d "deeplink://home/[1-4]"`
`adb shell am start -W -a android.intent.action.VIEW -d "deeplink://notification/[1-6]"`
