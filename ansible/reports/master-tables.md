## Device  vmx7

| Device Facts |  Values      |
|--------------|--------------|
|Hostname  | vmx7 |
|FQDN | vmx7.ntc.com |
|Model  | VMX |
|OS Version | 15.1F4.15 |
|Serial Number | VMXd6 |
|Vendor  | Juniper |
---
| Hostname | Local Interface | Neighbor | Neighbor Interface |
|----------|-----------------|----------|--------------------|
vmx7 | ge-0/0/1 | vmx9 | 518 |
vmx7 | fxp0 | vmx8 | 1 |
vmx7 | fxp0 | vmx9 | 1 |
vmx7 | fxp0 | csr2 | Gi1 |
vmx7 | fxp0 | eos-leaf2 | Management1 |
vmx7 | fxp0 | eos-spine2 | Management1 |
vmx7 | fxp0 | eos-leaf1 | Management1 |
vmx7 | fxp0 | eos-spine1 | Management1 |
vmx7 | ge-0/0/0 | vmx8 | 517 |
---

## Interface Summary:

| Total Interfaces | Enabled Interfaces | Up Interfaces |
|------------------|--------------------|---------------|
| 47 | 41 | 41 |

---

## Interface Status Summary:

| Interface | Description | Enabled | Status |
|-----------|-------------|---------|--------|
ge-0/0/7 |  | up | down |
ge-0/0/6 |  | up | down |
ge-0/0/5 |  | up | up |
ge-0/0/4 |  | up | up |
ge-0/0/3 |  | up | up |
ge-0/0/2 | UNUSED | down | down |
ge-0/0/1 | CONNECTS_vmx9 | up | up |
ge-0/0/0 | CONNECTS_vmx8 | up | up |
ge-0/0/9 |  | up | down |
ge-0/0/8 |  | up | down |
lo0.16384 |  | down | up |
lo0.16385 |  | down | up |
ge-0/0/2.0 |  | down | down |
ge-0/0/0.0 |  | up | up |
fxp0.0 |  | up | up |
fxp0 | MANAGEMENT | up | up |
lo0.0 |  | down | up |
ge-0/0/1.0 |  | up | up |
lo0 | OSPF_ROUTER_ID | up | up |

---

## IP Address Information:

| Interface | IP Address |
|-----------|------------|
| lo0.0 | 3.3.3.3/32 |
| fxp0.0 | 10.0.0.37/24 |
| lo0.16384 | 127.0.0.1/32 |
| ge-0/0/0.0 | 10.254.13.3/24 |
| ge-0/0/1.0 | 10.254.23.3/24 |
______________
## Device  vmx8

| Device Facts |  Values      |
|--------------|--------------|
|Hostname  | vmx8 |
|FQDN | vmx8.ntc.com |
|Model  | VMX |
|OS Version | 15.1F4.15 |
|Serial Number | VMXe8 |
|Vendor  | Juniper |
---
| Hostname | Local Interface | Neighbor | Neighbor Interface |
|----------|-----------------|----------|--------------------|
vmx8 | ge-0/0/2 | vmx9 | 519 |
vmx8 | fxp0 | vmx7 | 1 |
vmx8 | fxp0 | vmx9 | 1 |
vmx8 | fxp0 | csr2 | Gi1 |
vmx8 | fxp0 | eos-leaf2 | Management1 |
vmx8 | fxp0 | eos-spine2 | Management1 |
vmx8 | fxp0 | eos-leaf1 | Management1 |
vmx8 | fxp0 | eos-spine1 | Management1 |
vmx8 | ge-0/0/0 | vmx7 | 517 |
---

## Interface Summary:

| Total Interfaces | Enabled Interfaces | Up Interfaces |
|------------------|--------------------|---------------|
| 47 | 41 | 41 |

---

## Interface Status Summary:

| Interface | Description | Enabled | Status |
|-----------|-------------|---------|--------|
ge-0/0/7 |  | up | down |
ge-0/0/6 |  | up | down |
ge-0/0/5 |  | up | up |
ge-0/0/4 |  | up | up |
ge-0/0/3 |  | up | up |
ge-0/0/2 | CONNECTS_vmx9 | up | up |
ge-0/0/1 | UNUSED | down | down |
ge-0/0/0 | CONNECTS_vmx7 | up | up |
ge-0/0/9 |  | up | down |
ge-0/0/8 |  | up | down |
lo0.16384 |  | down | up |
lo0.16385 |  | down | up |
ge-0/0/2.0 |  | up | up |
ge-0/0/0.0 |  | up | up |
fxp0.0 |  | up | up |
fxp0 | MANAGEMENT | up | up |
lo0.0 |  | down | up |
ge-0/0/1.0 |  | down | down |
lo0 | OSPF_ROUTER_ID | up | up |

---

## IP Address Information:

| Interface | IP Address |
|-----------|------------|
| ge-0/0/2.0 | 10.254.12.1/24 |
| lo0.0 | 1.1.1.1/32 |
| lo0.16384 | 127.0.0.1/32 |
| ge-0/0/0.0 | 10.254.13.1/24 |
| fxp0.0 | 10.0.0.38/24 |
______________
## Device  vmx9

| Device Facts |  Values      |
|--------------|--------------|
|Hostname  | vmx9 |
|FQDN | vmx9.ntc.com |
|Model  | VMX |
|OS Version | 15.1F4.15 |
|Serial Number | VMXd2 |
|Vendor  | Juniper |
---
| Hostname | Local Interface | Neighbor | Neighbor Interface |
|----------|-----------------|----------|--------------------|
vmx9 | ge-0/0/2 | vmx8 | 519 |
vmx9 | ge-0/0/1 | vmx7 | 518 |
vmx9 | fxp0 | vmx8 | 1 |
vmx9 | fxp0 | vmx7 | 1 |
vmx9 | fxp0 | csr2 | Gi1 |
vmx9 | fxp0 | eos-leaf2 | Management1 |
vmx9 | fxp0 | eos-spine2 | Management1 |
vmx9 | fxp0 | eos-leaf1 | Management1 |
vmx9 | fxp0 | eos-spine1 | Management1 |
---

## Interface Summary:

| Total Interfaces | Enabled Interfaces | Up Interfaces |
|------------------|--------------------|---------------|
| 47 | 41 | 41 |

---

## Interface Status Summary:

| Interface | Description | Enabled | Status |
|-----------|-------------|---------|--------|
ge-0/0/7 |  | up | down |
ge-0/0/6 |  | up | down |
ge-0/0/5 |  | up | up |
ge-0/0/4 |  | up | up |
ge-0/0/3 |  | up | up |
ge-0/0/2 | CONNECTS_vmx8 | up | up |
ge-0/0/1 | CONNECTS_vmx7 | up | up |
ge-0/0/0 | UNUSED | down | down |
ge-0/0/9 |  | up | down |
ge-0/0/8 |  | up | down |
lo0.16384 |  | down | up |
lo0.16385 |  | down | up |
ge-0/0/2.0 |  | up | up |
ge-0/0/0.0 |  | down | down |
fxp0.0 |  | up | up |
fxp0 | MANAGEMENT | up | up |
lo0.0 |  | down | up |
ge-0/0/1.0 |  | up | up |
lo0 | OSPF_ROUTER_ID | up | up |

---

## IP Address Information:

| Interface | IP Address |
|-----------|------------|
| ge-0/0/2.0 | 10.254.12.2/24 |
| lo0.0 | 2.2.2.2/32 |
| fxp0.0 | 10.0.0.39/24 |
| lo0.16384 | 127.0.0.1/32 |
| ge-0/0/1.0 | 10.254.23.2/24 |
