# Struct: <code>devlink_port_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    bool set;
    enum devlink_port_flavour flavour;
    u32 port_number;
    bool split;
    u32 split_subport_number;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    bool set;
    enum devlink_port_flavour flavour;
    u32 port_number;
    bool split;
    u32 split_subport_number;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 split;
    u8 splittable;
    u32 lanes;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 split;
    u8 splittable;
    u32 lanes;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
    struct devlink_port_pci_sf_attrs pci_sf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 split;
    u8 splittable;
    u32 lanes;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
    struct devlink_port_pci_sf_attrs pci_sf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 split;
    u8 splittable;
    u32 lanes;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
    struct devlink_port_pci_sf_attrs pci_sf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 split;
    u8 splittable;
    u32 lanes;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
    struct devlink_port_pci_sf_attrs pci_sf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 split;
    u8 splittable;
    u32 lanes;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
    struct devlink_port_pci_sf_attrs pci_sf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 split;
    u8 splittable;
    u32 lanes;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
    struct devlink_port_pci_sf_attrs pci_sf;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct devlink_port_attrs {
    u8 set;
    u8 split;
    u8 switch_port;
    enum devlink_port_flavour flavour;
    struct netdev_phys_item_id switch_id;
    struct devlink_port_phys_attrs phys;
    struct devlink_port_pci_pf_attrs pci_pf;
    struct devlink_port_pci_vf_attrs pci_vf;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct devlink_port_attrs {
    bool set;
    enum devlink_port_flavour flavour;
    u32 port_number;
    bool split;
    u32 split_subport_number;
}
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 switch_port</code>
</li>
<li>
<b>Field added. </b>
<code>struct netdev_phys_item_id switch_id</code>
</li>
<li>
<b>Field added. </b>
<code>struct devlink_port_phys_attrs phys</code>
</li>
<li>
<b>Field added. </b>
<code>struct devlink_port_pci_pf_attrs pci_pf</code>
</li>
<li>
<b>Field added. </b>
<code>struct devlink_port_pci_vf_attrs pci_vf</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 port_number</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 split_subport_number</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool set</code> ➡️ <code>u8 set</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool split</code> ➡️ <code>u8 split</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 splittable</code>
</li>
<li>
<b>Field added. </b>
<code>u32 lanes</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 set</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 switch_port</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct devlink_port_pci_sf_attrs pci_sf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
