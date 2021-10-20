# how-to-react-native-windows
 How to install React Native on Windows



## (1) Chocolatey
Site: https://chocolatey.org/

open Command Prompt(cmd) as Administrator, and execute the command below.

> @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"




> choco –version

If its ok ,you can see Chocolatey version on the screen.

> 0.10.15

## (2) Nodejs

> choco install -y nodejs.install
> node -–version
> npm --version

## (3) Python
> choco install -y python2
> python --version

## (4) React Native CLI
> npm install -g react-native-cli
> npx react-native --version

## (5) Android Studio
. Android Studio: https://developer.android.com/studio

![alt](https://https://dev-yakuza.posstree.com/assets/images/category/react-native/2018/install-on-windows/android_studio_start.jpg)





