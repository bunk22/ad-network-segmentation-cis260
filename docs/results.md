# Results Log

## 1) Environment Setup
- VirtualBox VMs created (pfSense, Server 2022, Win11)
- ISOs verified

## 2) Domain Controller
- Installed AD DS + DNS, domain: `corp.local`
- Screenshot: AD Users & Computers (pending)

## 3) Client Join
- Win11 joined to `corp.local`
- Screenshot: System → Domain = corp.local (pending)

## 4) GPO Proof
- `gpresult /h C:\gp.html` generated
- Screenshot: GPO report (pending)

## 5) Segmentation (later step)
- Guest VLAN blocked from Corp subnet
- Screenshot: failed ping/port from Guest (pending)
