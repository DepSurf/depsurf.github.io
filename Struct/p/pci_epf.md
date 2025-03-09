# Struct: <code>pci_epf</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
    struct notifier_block nb;
    struct mutex lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
    struct notifier_block nb;
    struct mutex lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
    struct notifier_block nb;
    struct mutex lock;
    struct pci_epc * sec_epc;
    struct list_head sec_epc_list;
    struct pci_epf_bar[6] sec_epc_bar;
    u8 sec_epc_func_no;
    struct config_group * group;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    u8 vfunc_no;
    struct pci_epc * epc;
    struct pci_epf * epf_pf;
    struct pci_epf_driver * driver;
    struct list_head list;
    struct notifier_block nb;
    struct mutex lock;
    struct pci_epc * sec_epc;
    struct list_head sec_epc_list;
    struct pci_epf_bar[6] sec_epc_bar;
    u8 sec_epc_func_no;
    struct config_group * group;
    unsigned int is_bound;
    unsigned int is_vf;
    long unsigned int vfunction_num_map;
    struct list_head pci_vepf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    u8 vfunc_no;
    struct pci_epc * epc;
    struct pci_epf * epf_pf;
    struct pci_epf_driver * driver;
    struct list_head list;
    struct notifier_block nb;
    struct mutex lock;
    struct pci_epc * sec_epc;
    struct list_head sec_epc_list;
    struct pci_epf_bar[6] sec_epc_bar;
    u8 sec_epc_func_no;
    struct config_group * group;
    unsigned int is_bound;
    unsigned int is_vf;
    long unsigned int vfunction_num_map;
    struct list_head pci_vepf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    u8 vfunc_no;
    struct pci_epc * epc;
    struct pci_epf * epf_pf;
    struct pci_epf_driver * driver;
    struct list_head list;
    struct notifier_block nb;
    struct mutex lock;
    struct pci_epc * sec_epc;
    struct list_head sec_epc_list;
    struct pci_epf_bar[6] sec_epc_bar;
    u8 sec_epc_func_no;
    struct config_group * group;
    unsigned int is_bound;
    unsigned int is_vf;
    long unsigned int vfunction_num_map;
    struct list_head pci_vepf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    u8 vfunc_no;
    struct pci_epc * epc;
    struct pci_epf * epf_pf;
    struct pci_epf_driver * driver;
    const struct pci_epf_device_id * id;
    struct list_head list;
    struct mutex lock;
    struct pci_epc * sec_epc;
    struct list_head sec_epc_list;
    struct pci_epf_bar[6] sec_epc_bar;
    u8 sec_epc_func_no;
    struct config_group * group;
    unsigned int is_bound;
    unsigned int is_vf;
    long unsigned int vfunction_num_map;
    struct list_head pci_vepf;
    const struct pci_epc_event_ops * event_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    u8 vfunc_no;
    struct pci_epc * epc;
    struct pci_epf * epf_pf;
    struct pci_epf_driver * driver;
    const struct pci_epf_device_id * id;
    struct list_head list;
    struct mutex lock;
    struct pci_epc * sec_epc;
    struct list_head sec_epc_list;
    struct pci_epf_bar[6] sec_epc_bar;
    u8 sec_epc_func_no;
    struct config_group * group;
    unsigned int is_bound;
    unsigned int is_vf;
    long unsigned int vfunction_num_map;
    struct list_head pci_vepf;
    const struct pci_epc_event_ops * event_ops;
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
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
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
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u16 msix_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct pci_epf {
    struct device dev;
    const char * name;
    struct pci_epf_header * header;
    struct pci_epf_bar[6] bar;
    u8 msi_interrupts;
    u8 func_no;
    struct pci_epc * epc;
    struct pci_epf_driver * driver;
    struct list_head list;
}
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 msix_interrupts</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct notifier_block nb</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct pci_epc * sec_epc</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head sec_epc_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct pci_epf_bar[6] sec_epc_bar</code>
</li>
<li>
<b>Field added. </b>
<code>u8 sec_epc_func_no</code>
</li>
<li>
<b>Field added. </b>
<code>struct config_group * group</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 vfunc_no</code>
</li>
<li>
<b>Field added. </b>
<code>struct pci_epf * epf_pf</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int is_bound</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int is_vf</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int vfunction_num_map</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head pci_vepf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct pci_epf_device_id * id</code>
</li>
<li>
<b>Field added. </b>
<code>const struct pci_epc_event_ops * event_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>struct notifier_block nb</code>
</li>
</ul>
</details>
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
