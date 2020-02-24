# wpad-autoconfigure: Configuration for Web Proxy AutoDiscovery Protocol (WPAD)

- Set wpad.dat MIME filetype to "application/x-javascript-config"
- Set your localDomain/proxyUrl settings below at FindProxyForUrl()
- Place the file at http://wpad.yourdomain/wpad.dat
- Enforce the wpad.pdat by:
  - Creating a DHCP 252 config option
  - Creating a DNS wpad.yourdomain
  - Creating a GPO on your Active Directory server.

