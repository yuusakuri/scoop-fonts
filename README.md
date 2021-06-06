# scoop-fonts

scoop-fonts contains manifests for installing Fonts without administrator privileges using the [Scoop](https://github.com/lukesampson/scoop) for Windows. This repository contains many fonts for Japanese.

To install fonts, use the function `Install-Font` included in the PowerShell module [PSWinGlue](https://github.com/ralish/PSWinGlue).

## Add Bucket

To install the app from this bucket, first execute the following code in PowerShell. The dependency Scoop bucket also needs to be added.

```
scoop bucket add yuusakuri https://github.com/yuusakuri/scoop-bucket.git
scoop bucket add yuusakuri-fonts https://github.com/yuusakuri/scoop-fonts.git
```

## Install fonts

Execute the following code to install the font.

```powershell
scoop install NAME
```
