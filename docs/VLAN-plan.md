
| VLAN | Name  | Subnet        | Gateway     | Purpose                         |
|-----:|-------|---------------|-------------|---------------------------------|
| 10   | Corp  | 10.10.10.0/24 | 10.10.10.1  | AD DS/DNS + domain clients      |
| 20   | Guest | 10.10.20.0/24 | 10.10.20.1  | Internet-only, no corp access   |
| 99   | Mgmt  | 10.10.99.0/24 | 10.10.99.1  | (optional) admin services        |
