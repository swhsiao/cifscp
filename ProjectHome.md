Simple low overhead client for cifs/smb protocol,
written on plain C without dependencies.

```
usage: 
  cifscp -l FILE...
  cifscp [OPTION]... SOURCE DEST
  cifscp [OPTION]... SOURCE... DIRECTORY
  
  URI:    (smb|cifs)://[user[:password]@]host[:[addr:]port]/share/path
  UNC:    \\host\share\path
  
  OPTION:
  -l                    list directory contents
  -L                    list with directory size
  -R                    recurcive list
  -s <int>[k|m|g|t]     limit download speed
  -h                    show this message and exit
  -v                    increase verbosity
```