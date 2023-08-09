- #### 📦 Status
| Tool | Status |
| ---- | ------ |
|[GDB & GDBServer](https://github.com/Azathothas/static-toolbox/actions/workflows/build-gdb.yml)|[![⚙️ Build GDB 📦](https://github.com/Azathothas/static-toolbox/actions/workflows/build-gdb.yml/badge.svg)](https://github.com/Azathothas/static-toolbox/actions/workflows/build-gdb.yml)|
|[Nmap](https://github.com/Azathothas/static-toolbox/actions/workflows/build-nmap.yml)|[![⚙️ Build Nmap 📦](https://github.com/Azathothas/static-toolbox/actions/workflows/build-nmap.yml/badge.svg)](https://github.com/Azathothas/static-toolbox/actions/workflows/build-nmap.yml)|
|[OpenSSH](https://github.com/Azathothas/static-toolbox/actions/workflows/build-openssh.yml)|[![⚙️ Build OpenSSH 📦](https://github.com/Azathothas/static-toolbox/actions/workflows/build-openssh.yml/badge.svg)](https://github.com/Azathothas/static-toolbox/actions/workflows/build-openssh.yml)|
|[Socat](https://github.com/Azathothas/static-toolbox/actions/workflows/build-socat.yml)|[![⚙️ Build Socat 📦](https://github.com/Azathothas/static-toolbox/actions/workflows/build-socat.yml/badge.svg)](https://github.com/Azathothas/static-toolbox/actions/workflows/build-socat.yml)|
|[Strace](https://github.com/Azathothas/static-toolbox/actions/workflows/build-strace.yml)|[![⚙️ Build Strace 📦](https://github.com/Azathothas/static-toolbox/actions/workflows/build-strace.yml/badge.svg)](https://github.com/Azathothas/static-toolbox/actions/workflows/build-strace.yml)|
|[TCPDump](https://github.com/Azathothas/static-toolbox/actions/workflows/build-tcpdump.yml)|[![⚙️ Build TCPDump 📦](https://github.com/Azathothas/static-toolbox/actions/workflows/build-tcpdump.yml/badge.svg)](https://github.com/Azathothas/static-toolbox/actions/workflows/build-tcpdump.yml)|

---
- #### Catalogue
> > ```bash
> > !# Install eget
> > curl -qfsSL "https://zyedidia.github.io/eget.sh" | bash
> > !# Move it to "$HOME/bin/eget" or "/usr/local/bin/eget"
> > ```
- ##### [GDB](https://www.sourceware.org/gdb/)
> ```bash
> --> amd || x86_64
> -->  eget "Azathothas/static-toolbox" --tag "gdb" --asset "^server" --asset "x86_64" --to "gdb"
> --> aarch64 || arm64
> -->  eget "Azathothas/static-toolbox" --tag "nmap" --asset "x86_64" --to "nmap"
> ```
- ##### [Nmap](https://nmap.org/)
> ```bash
> --> amd || x86_64
> -->  eget "Azathothas/static-toolbox" --tag "nmap" --asset "x86_64" --to "nmap"
> --> aarch64 || arm64
> -->  eget "Azathothas/static-toolbox" --tag "nmap" --asset "x86_64" --to "nmap"
> ```
- ##### [OpenSSH](https://www.openssh.com/)
> ```bash
> --> amd || x86_64
> -->  eget "Azathothas/static-toolbox" --tag "openssh" --asset "x86_64" --to "openssh"
> --> aarch64 || arm64
> -->  
> ```
- ##### [Socat](http://www.dest-unreach.org/socat/)
> ```bash
> --> amd || x86_64
> -->  eget "Azathothas/static-toolbox" --tag "socat" --asset "x86_64" --to "socat"
> --> aarch64 || arm64
> -->  
> ```
- ##### [Strace](https://github.com/strace/strace)
> ```bash
> --> amd || x86_64
> -->  eget "Azathothas/static-toolbox" --tag "strace" --asset "x86_64" --to "strace"
> --> aarch64 || arm64
> -->  
> ```
- ##### [TCPDump](https://www.tcpdump.org/)
> ```bash
> --> amd || x86_64
> -->  eget "Azathothas/static-toolbox" --tag "tcpdump" --asset "x86_64" --to "tcpdump"
> --> aarch64 || arm64
> -->  
> ```
