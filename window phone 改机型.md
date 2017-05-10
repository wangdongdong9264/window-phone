##window phone 改机型  

    1. 先下载 interop Tools
    2. 设置-更新和安全-针对开发人员 选择开发人员模式
    3. 安装 interop Tools
    4. 打开 选择REGISTRY BROWSER
    5. 找到以下目录

        ```
            HKEY_LOCAL_MACHINE\SYSTEM\Platform\DeviceTargetingInfo
        ```

    6. 进入PhoneManufacturer项     将设备制造商的值改为Microsoft，然后点击Write

    7. PhoneModelName项，将其中型号名称的值改为你的目标型号(我的手机(Lumia 830)要改成的型号是Lumia 950，所以这里填写的是RM-1118，然后点击Write

    8. PhoneManufacturerModelName，将其中设备工程型号的值改为RM-1118_11280，然后点击Write

    9. PhoneHardwareVariant，将手机硬件类型的值改为RM-1118，然后点击Write

    10. 重启手机    设置>系统>关于 查看你的手机型号


##其它

    1. microsoft 950

        * PhoneManufacturerModelName    RM-1118_11280
        * PhoneModelName        RM-1118
        * PhoneManufacturer     Microsoft

    2. microsoft 950XL

        * PhoneManufacturerModelName    RM-1116_11258
        * PhoneModelName        RM-1116
        * PhoneManufacturer     Microsoft

    3. lumia 830

        * PhoneManufacturerModelName    RM-984_1043
        * PhoneModelName        Lumia 830
        * PhoneManufacturer     NOKIA


