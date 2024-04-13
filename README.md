# Packer-Images
Using Packer to create images. 

> Copied from [Automated Windows Server 2022 Packer Build](https://www.virtualizationhowto.com/2021/06/automated-windows-server-2022-packer-build/) so to learn Packer. 

## Executing Automated Build
The following command will execute the Packer build workflow. 

```
packer init .
packer validate .
packer build .
```

## References
- [Automated Windows Server 2022 Packer Build](https://www.virtualizationhowto.com/2021/06/automated-windows-server-2022-packer-build/)
- [Windows Server 2019 Automating Windows Update with PowerShell and Logs](https://www.virtualizationhowto.com/2019/07/windows-server-2019-automating-windows-update-with-powershell-and-logs/)
- [Automated Windows 10 Installation with AutoUnattend and Packer](https://www.virtualizationhowto.com/2019/05/automated-windows-10-installation-with-autounattend-and-packer/)
- [Windows Server 2019 Unattended Install Windows Updates](https://www.virtualizationhowto.com/2019/05/windows-server-2019-unattended-install-windows-updates/)

- [eaksel/packer-Win2022](https://github.com/eaksel/packer-Win2022)
- [eaksel/packer-Win2019](https://github.com/eaksel/packer-Win2019)