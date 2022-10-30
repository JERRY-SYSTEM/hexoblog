---
title: WinSXS极限精简
date: 2022-07-22 19:38:54
tags:
- 哔哩哔哩
---

# WinSXS极限精简

## 精简配方(需要的文件目录)

##### 能进系统SXS：

> Catalogs
> FileMaps
> InstallTemp
> Manifests
> amd64_microsoft-windows-s..cingstack.resources_*
> amd64_microsoft-windows-servicingstack_*
> amd64_microsoft.windows.c..-controls.resources_*
> amd64_microsoft.windows.common-controls_*
> amd64_microsoft.windows.gdiplus_*

##### 能用系统SXS：

> Catalogs
> FileMaps
> InstallTemp
> Manifests
> amd64_microsoft-windows-cmisetup*
> amd64_microsoft-windows-cmi*
> amd64_microsoft-windows-com-dtc-runtime*
> amd64_microsoft-windows-d..t-services-unattend*
> amd64_microsoft-windows-deltacompressionengine*
> amd64_microsoft-windows-deltapackageexpander*
> amd64_microsoft-windows-drvstore*
> amd64_microsoft-windows-dynamicvolumemanager*
> amd64_microsoft-windows-help-datalayer*
> amd64_microsoft-windows-i..ntrolpanel.appxmain*
> amd64_microsoft-windows-m..acementmanifests-ds*
> amd64_microsoft-windows-m..cementmanifests-com*
> amd64_microsoft-windows-m..cementmanifests-net*
> amd64_microsoft-windows-m..elmanifests-drivers*
> amd64_microsoft-windows-m..elmanifests-enduser*
> amd64_microsoft-windows-m..elmanifests-inetsrv*
> amd64_microsoft-windows-m..elmanifests-onecore*
> amd64_microsoft-windows-m..elmanifests-pcshell*
> amd64_microsoft-windows-m..elmanifests-termsrv*
> amd64_microsoft-windows-m..elmanifests-windows*
> amd64_microsoft-windows-m..ementmanifests-base*
> amd64_microsoft-windows-m..entmanifests-avcore*
> amd64_microsoft-windows-m..evelmanifests-minio*
> amd64_microsoft-windows-m..lmanifests-inetcore*
> amd64_microsoft-windows-m..manifests-minkernel*
> amd64_microsoft-windows-m..manifests-minkernel*
> amd64_microsoft-windows-m..manifests-printscan*
> amd64_microsoft-windows-m..manifests-printscan*
> amd64_microsoft-windows-m..mentmanifests-admin*
> amd64_microsoft-windows-m..mentmanifests-minio*
> amd64_microsoft-windows-m..mentmanifests-shell*
> amd64_microsoft-windows-m..nlevelmanifests-com*
> amd64_microsoft-windows-m..ntmanifests-drivers*
> amd64_microsoft-windows-m..ntmanifests-enduser*
> amd64_microsoft-windows-m..ntmanifests-inetsrv*
> amd64_microsoft-windows-m..ntmanifests-onecore*
> amd64_microsoft-windows-m..ntmanifests-termsrv*
> amd64_microsoft-windows-m..ntmanifests-windows*
> amd64_microsoft-windows-m..tion-isolationlayer*
> amd64_microsoft-windows-m..wnlevelmanifests-ds*
> amd64_microsoft-windows-msxml60*
> amd64_microsoft-windows-naturallanguage6-base*
> amd64_microsoft-windows-oobe-firstlogonanimexe*
> amd64_microsoft-windows-oobe-firstlogonanim*
> amd64_microsoft-windows-p..ncetoolscommandline*
> amd64_microsoft-windows-packagemanager*
> amd64_microsoft-windows-pantherengine*
> amd64_microsoft-windows-s..cingstack.resources*
> amd64_microsoft-windows-s..stack-msg.resources*
> amd64_microsoft-windows-servicingstack*
> amd64_microsoft-windows-servicingstack*
> amd64_microsoft-windows-setup-unattend*
> amd64_microsoft-windows-shell32*
> amd64_microsoft-windows-smi-engine*
> amd64_microsoft-windows-store-licensemanager*
> amd64_microsoft-windows-t..platform-comruntime*
> amd64_microsoft-windows-uiribbon.resources*
> amd64_microsoft-windows-uiribbon*
> amd64_microsoft-windows-wmi-core-fastprox-dll*
> amd64_microsoft-windows-wmi-core-repdrvfs-dll*
> amd64_microsoft-windows-wmi-core-wbemcomn-dll*
> amd64_microsoft-windows-wmi-core-wbemcore-dll*
> amd64_microsoft-windows-wmi-core*
> amd64_microsoft-windows-wmi-mofinstaller*
> amd64_microsoft-windows-xmllite*
> amd64_microsoft.vc80.crt*
> amd64_microsoft.vc90.crt*
> amd64_microsoft.windows.c..-controls.resources*
> amd64_microsoft.windows.common-controls*
> amd64_microsoft.windows.gdiplus.systemcopy*
> amd64_microsoft.windows.gdiplus*
> amd64_microsoft.windows.i..utomation.proxystub*
> amd64_microsoft.windows.isolationautomation*
> amd64_system.runtime.seri..ion.formatters.soap*
> wow64_microsoft-windows-cmisetup*
> wow64_microsoft-windows-cmi*
> wow64_microsoft-windows-deltacompressionengine*
> wow64_microsoft-windows-deltapackageexpander*
> wow64_microsoft-windows-drvstore*
> wow64_microsoft-windows-help-datalayer*
> wow64_microsoft-windows-m..tion-isolationlayer*
> wow64_microsoft-windows-msxml60*
> wow64_microsoft-windows-naturallanguage6-base*
> wow64_microsoft-windows-p..ncetoolscommandline*
> wow64_microsoft-windows-shell32*
> wow64_microsoft-windows-store-licensemanager*
> wow64_microsoft-windows-t..platform-comruntime*
> wow64_microsoft-windows-uiribbon.resources*
> wow64_microsoft-windows-uiribbon*
> wow64_microsoft-windows-wmi-core-fastprox-dll*
> wow64_microsoft-windows-wmi-core-repdrvfs-dll*
> wow64_microsoft-windows-wmi-core-wbemcomn-dll*
> wow64_microsoft-windows-wmi-core-wbemcore-dll*
> wow64_microsoft-windows-wmi-core*
> wow64_microsoft-windows-xmllite*
> wow64_microsoft.windows.gdiplus.systemcopy*
> x86_microsoft-windows-packagemanager*
> x86_microsoft-windows-pantherengine*
> x86_microsoft-windows-servicingstack*
> x86_microsoft-windows-servicingstack*
> x86_microsoft.vc80.crt*
> x86_microsoft.vc90.crt*
> x86_microsoft.windows.c..-controls.resources*
> x86_microsoft.windows.common-controls*
> x86_microsoft.windows.gdiplus*
> x86_microsoft.windows.i..utomation.proxystub*
> x86_microsoft.windows.isolationautomation*

## PE复制文件命令行

最简便的命令行写法：

```cmd
for /f %f in (txt文件) do pecmd.exe file C:\Windows\W1\%f"->C:\Windows\WinSXS"
```


在cmd中，变量应写为%f；在批处理中，变量应写为%%f。

txt文件即将上面的内容复制进txt文件。

W1为原WinSXS文件夹重命名后的文件夹名。

## 成果展示

![01](007_01.png)

## 视频介绍

<div style="position: relative; padding: 30% 45%;">
    <iframe style="
        position: absolute; 
        width: 100%; 
        height: 100%; 
        left: 0; top: 0;" 
        src="//player.bilibili.com/player.html?aid=601231806&bvid=BV1wB4y1h7XU&cid=781089910&page=1"
        scrolling="no" 
        border="0" 
        frameborder="no" 
        framespacing="0" 
        allowfullscreen="true">
    </iframe>
</div>

## 下载链接

| 下载             | 链接                                | 提取码 |
| ---------------- | ----------------------------------- | ------ |
| PowerRun提权工具 | https://wwa.lanzoui.com/i6wquqq90fg | 无     |
