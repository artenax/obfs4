## About
obfs4proxy transport for Tor. Provides obfs3, obfs4, meek bridges.

## Usage
torrc:  
```
UseBridges 1
ClientTransportPlugin obfs4,obfs3,meek_lite exec obfs4proxy.exe -enableLogging=false -unsafeLogging=false -logLevel INFO
Bridge obfs4 IP:PORT ID cert=CERT iat-mode=0
```
