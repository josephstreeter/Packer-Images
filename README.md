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