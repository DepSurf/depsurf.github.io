# Struct: <code>pcie_port_service_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume;
    const struct pci_error_handlers * err_handler;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume;
    const struct pci_error_handlers * err_handler;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume;
    const struct pci_error_handlers * err_handler;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume;
    const struct pci_error_handlers * err_handler;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    int (*)(struct pcie_device *) slot_reset;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    int (*)(struct pcie_device *) slot_reset;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    int (*)(struct pcie_device *) slot_reset;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    int (*)(struct pcie_device *) slot_reset;
    int port_type;
    u32 service;
    struct device_driver driver;
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
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
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
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct pci_dev *) error_resume</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct pci_error_handlers * err_handler</code>
</li>
</ul>
</details>
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
<code>int (*)(struct pcie_device *) resume_noirq</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct pcie_device *) runtime_suspend</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct pcie_device *) runtime_resume</code>
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
<b>Field removed. </b>
<code>pci_ers_result_t (*)(struct pci_dev *) reset_link</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct pcie_device *) slot_reset</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct pci_dev *) error_resume</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pcie_port_service_driver {
    const char * name;
    int (*)(struct pcie_device *) probe;
    void (*)(struct pcie_device *) remove;
    int (*)(struct pcie_device *) suspend;
    int (*)(struct pcie_device *) resume_noirq;
    int (*)(struct pcie_device *) resume;
    int (*)(struct pcie_device *) runtime_suspend;
    int (*)(struct pcie_device *) runtime_resume;
    void (*)(struct pci_dev *) error_resume;
    pci_ers_result_t (*)(struct pci_dev *) reset_link;
    int port_type;
    u32 service;
    struct device_driver driver;
}
```
</details>
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
