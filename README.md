# WindowsSignerInfo
 
The data in this repository has been collect using Sysinternals' Sigcheck in 5 different default installations of the Windows OS:

- Windows 10 (Microsoft Windows 10 Enterprise Evaluation - Build 19045)
- Windows 11 (Microsoft Windows 11 Enterprise Evaluation - Build 22621)
- Windows Server 2016 (Microsoft Windows Server 2016 Datacenter Evaluation - Build 14393)
- Windows Server 2019 (Microsoft Windows Server 2019 Datacenter Evaluation - Build 17763)
- Windows Server 2022 (Microsoft Windows Server 2022 Datacenter Evaluation - Build 20348)

Sigcheck Command Lines
```
.\sigcheck64.exe -i -s C:\Windows\System32\ -nobanner -accepteula
.\sigcheck64.exe -i C:\Windows\System32\ -nobanner -accepteula
```
