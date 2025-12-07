# nxcspray
Simple bash script to spray known credentials against multiple services with netexec

# Installation
Clone this repo or download the script directly.

Add the script to /usr/local/bin/ to execute it from anywhere on your machine, or use it in a local directory of your choice.
```
sudo mv ~/Downloads/nxcspray /usr/local/bin
chmod +x /usr/local/bin/nxcspray
```

# Usage
```
nxcspray <protocols> <targets> -u <username> -p <password>
```

Example Usage
```
nxcspray smb,mssql,winrm,rdp targets.txt -u bob -p boblovescamping123!
```
