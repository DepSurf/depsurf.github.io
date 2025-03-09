# Struct: <code>aer_rpc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pcie_device * rpd;
    struct work_struct dpc_handler;
    struct aer_err_source[100] e_sources;
    short unsigned int prod_idx;
    short unsigned int cons_idx;
    int isr;
    spinlock_t e_lock;
    struct mutex rpc_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pcie_device * rpd;
    struct work_struct dpc_handler;
    struct aer_err_source[100] e_sources;
    short unsigned int prod_idx;
    short unsigned int cons_idx;
    int isr;
    spinlock_t e_lock;
    struct mutex rpc_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pcie_device * rpd;
    struct work_struct dpc_handler;
    struct aer_err_source[100] e_sources;
    struct aer_err_info e_info;
    short unsigned int prod_idx;
    short unsigned int cons_idx;
    int isr;
    spinlock_t e_lock;
    struct mutex rpc_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pcie_device * rpd;
    struct work_struct dpc_handler;
    struct aer_err_source[100] e_sources;
    struct aer_err_info e_info;
    short unsigned int prod_idx;
    short unsigned int cons_idx;
    int isr;
    spinlock_t e_lock;
    struct mutex rpc_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pcie_device * rpd;
    struct work_struct dpc_handler;
    struct aer_err_source[100] e_sources;
    struct aer_err_info e_info;
    short unsigned int prod_idx;
    short unsigned int cons_idx;
    int isr;
    spinlock_t e_lock;
    struct mutex rpc_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct work_struct dpc_handler;
    struct aer_err_source[100] e_sources;
    struct aer_err_info e_info;
    short unsigned int prod_idx;
    short unsigned int cons_idx;
    int isr;
    spinlock_t e_lock;
    struct mutex rpc_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
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
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
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
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
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
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct aer_err_info e_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct pcie_device * rpd</code> ➡️ <code>struct pci_dev * rpd</code>
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
<code>struct (anon) aer_fifo</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct dpc_handler</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aer_err_source[100] e_sources</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aer_err_info e_info</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int prod_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int cons_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>int isr</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t e_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mutex rpc_mutex</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct aer_rpc {
    struct pci_dev * rpd;
    struct (anon) aer_fifo;
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
