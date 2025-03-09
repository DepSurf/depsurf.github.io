# Struct: <code>pci_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
    unsigned int unsafe_warn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
    unsigned int unsafe_warn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
    unsigned int unsafe_warn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
    unsigned int unsafe_warn;
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
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    int domain_nr;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    int domain_nr;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    int domain_nr;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
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
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_bus {
    struct list_head node;
    struct pci_bus * parent;
    struct list_head children;
    struct list_head devices;
    struct pci_dev * self;
    struct list_head slots;
    struct resource *[4] resource;
    struct list_head resources;
    struct resource busn_res;
    struct pci_ops * ops;
    struct msi_controller * msi;
    void * sysdata;
    struct proc_dir_entry * procdir;
    unsigned char number;
    unsigned char primary;
    unsigned char max_bus_speed;
    unsigned char cur_bus_speed;
    char[48] name;
    short unsigned int bridge_ctl;
    pci_bus_flags_t bus_flags;
    struct device * bridge;
    struct device dev;
    struct bin_attribute * legacy_io;
    struct bin_attribute * legacy_mem;
    unsigned int is_added;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct msi_controller * msi</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int unsafe_warn</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int domain_nr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int domain_nr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int domain_nr</code>
</li>
</ul>
</details>
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
