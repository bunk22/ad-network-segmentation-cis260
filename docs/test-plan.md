# Test Plan

## AD & DNS
- Join Win11 client to domain `corp.local`
- Verify DNS resolution to DC (A, SRV records)

## GPOs
- Apply banner/password policy
- `gpupdate /force` + export `gpresult /h C:\gp.html`

## File Shares & ACLs
- Create `\\10.10.10.10\HR`
- HR user: read/write; Sales user: read/deny write

## Segmentation (when ready)
- From Guest VLAN: no access to 10.10.10.0/24 (block RFC1918)
- Internet from Guest works (HTTP/HTTPS)

## Evidence
- Screenshots (ADUC, gpresult, share perms, pfSense rules)
- Optional: pfSense firewall logs showing blocks
