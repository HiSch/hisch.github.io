# nmap

## Enumeration
### SMB
```sh
nmap -p 445 --script=smb-enum-shares.nse,smb-enum-users.nse <ip>
```
