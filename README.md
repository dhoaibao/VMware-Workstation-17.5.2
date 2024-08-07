## VMware Workstation 17.5.2
[Download for Windows](https://github.com/dhoaibao/VMware-Workstation-17.5.2/releases/download/17.5.2/VMware-workstation-full-17.5.2-23775571.exe)

[Download for Linux](https://github.com/dhoaibao/VMware-Workstation-17.5.2/releases/download/17.5.2/VMware-Workstation-Full-17.5.2-23775571.x86_64.bundle)

## Install on Linux
```js
  chmod +x ./VMware-Workstation-Full-17.5.2-23775571.x86_64.bundle
  sudo ./VMware-Workstation-Full-17.5.2-23775571.x86_64.bundle
  sudo rm -f ./VMware-Workstation-Full-17.5.2-23775571.x86_64.bundle

  git clone https://github.com/mkubecek/vmware-host-modules
  cd vmware-host-modules
  git checkout workstation-17.5.1
  sudo make
  sudo make install
  cd ..
  sudo rm -rf ./vmware-host-modules
```

## Key Pro
```js
  MG210-0EK8K-H89Y1-VLAN2-93K20
  HF200-0W05K-089X8-4R1EK-032J0
  5A69H-4A08H-480K1-KU972-932L4
  5Y69H-0J250-H88C8-MJ8Q0-2C2P4
```

## Uninstall on Linux
```js
  vmware-installer -u vmware-workstation
```
