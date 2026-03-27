# scoop-filebeam                                                                                                                                                                                 
Scoop bucket for [FileBeam](https://github.com/michaellwest/FileBeam) — a LAN file-sharing server packed into a single executable.                                                               
## Usage                                                                                                                                                                                      
### Installing

```powershell
scoop bucket add filebeam https://github.com/michaellwest/scoop-filebeam
scoop install filebeam
```

### Running
```powershell
filebeam --download C:\SharedFiles --port 9000
```

### Updating

```powershell
scoop update filebeam
```

## About FileBeam

Self-contained ASP.NET Core server for sharing files on your local network. Features include:

- Browse, upload, download, and delete files from any browser
- Role-based access with invite tokens
- Time-limited share links
- Live reload via Server-Sent Events
- TLS support
- Single executable — no runtime required

See the https://github.com/michaellwest/FileBeam#readme for full documentation.