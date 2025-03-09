# Struct: <code>pci_sriov</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    struct mutex lock;
    resource_size_t[6] barsz;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    struct mutex lock;
    resource_size_t[6] barsz;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    struct mutex lock;
    resource_size_t[6] barsz;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 cfg_size;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
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
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
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
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_sriov {
    int pos;
    int nres;
    u32 cap;
    u16 ctrl;
    u16 total_VFs;
    u16 initial_VFs;
    u16 num_VFs;
    u16 offset;
    u16 stride;
    u16 vf_device;
    u32 pgsz;
    u8 link;
    u8 max_VF_buses;
    u16 driver_max_VFs;
    struct pci_dev * dev;
    struct pci_dev * self;
    u32 class;
    u8 hdr_type;
    u16 subsystem_vendor;
    u16 subsystem_device;
    resource_size_t[6] barsz;
    bool drivers_autoprobe;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool drivers_autoprobe</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 vf_device</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 class</code>
</li>
<li>
<b>Field added. </b>
<code>u8 hdr_type</code>
</li>
<li>
<b>Field added. </b>
<code>u16 subsystem_vendor</code>
</li>
<li>
<b>Field added. </b>
<code>u16 subsystem_device</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 cfg_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u32 cfg_size</code>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
