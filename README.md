### wpad-autoconfigure: Configuration for Web Proxy AutoDiscovery Protocol (WPAD)

- Set [wpad.dat](wpad.dat) MIME filetype to "application/x-javascript-config"
- Set your localDomain/proxyUrl settings below at FindProxyForUrl() in [wpad.dat](wpad.dat)
- Place the file at http://wpad.yourdomain/wpad.dat
- Enforce the [wpad.dat](wpad.dat) by:
  - Creating a DHCP 252 config option
  - Creating a DNS wpad.yourdomain
  - Creating a GPO on your Active Directory server.

