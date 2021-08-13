# Description
Easily Deploy a SimpleHelp Server

# Setup
```
    apt instal ansible
    ansible-pull -U https://github.com/ryanvanmass/SimpleHelp_Ansible Deploy.yml
```

# UFW Configuration
| Port | State   | Purpose    |
|------|---------|------------|
| 22   | Limited | SSH        |
| 443  | Allowed | SimpleHelp |
| 80   | Allowed | SimpleHelp |

