## GitHub Copilot Chat

- Extension: 0.48.1 (prod)
- VS Code: 1.101.2 (2901c5ac6db8a986a5666c3af51ff804d05af0d4)
- OS: win32 10.0.26200 x64
- GitHub Account: chennakesava1002

## Network

User Settings:
```json
  "http.systemCertificatesNode": undefined,
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 20.207.73.85 (32 ms)
- DNS ipv6 Lookup: Error (22 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (14 ms)
- Electron fetch (configured): HTTP 200 (23 ms)
- Node.js https: HTTP 200 (78 ms)
- Node.js fetch: HTTP 200 (139 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.114.21 (18 ms)
- DNS ipv6 Lookup: Error (18 ms): getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Proxy URL: None (2 ms)
- Electron fetch (configured): HTTP 200 (695 ms)
- Node.js https: HTTP 200 (705 ms)
- Node.js fetch: HTTP 200 (701 ms)

Connecting to https://proxy.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 52.175.140.176 (81 ms)
- DNS ipv6 Lookup: Error (18 ms): getaddrinfo ENOTFOUND proxy.individual.githubcopilot.com
- Proxy URL: None (1 ms)
- Electron fetch (configured): HTTP 200 (558 ms)
- Node.js https: HTTP 200 (484 ms)
- Node.js fetch: HTTP 200 (522 ms)

Connecting to https://mobile.events.data.microsoft.com: HTTP 404 (242 ms)
Connecting to https://dc.services.visualstudio.com: HTTP 404 (765 ms)
Connecting to https://copilot-telemetry.githubusercontent.com/_ping: HTTP 200 (729 ms)
Connecting to https://telemetry.individual.githubcopilot.com/_ping: HTTP 200 (741 ms)
Connecting to https://default.exp-tas.com: HTTP 400 (220 ms)

Number of system certificates: 38

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).