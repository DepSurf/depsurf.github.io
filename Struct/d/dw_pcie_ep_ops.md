# Struct: <code>dw_pcie_ep_ops</code>

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
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, enum pci_epc_irq_type, u8) raise_irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, enum pci_epc_irq_type, u8) raise_irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u8) raise_irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
    unsigned int (*)(struct dw_pcie_ep *, u8) func_conf_select;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
    unsigned int (*)(struct dw_pcie_ep *, u8) func_conf_select;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
    unsigned int (*)(struct dw_pcie_ep *, u8) func_conf_select;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
    unsigned int (*)(struct dw_pcie_ep *, u8) func_conf_select;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
    unsigned int (*)(struct dw_pcie_ep *, u8) func_conf_select;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
    unsigned int (*)(struct dw_pcie_ep *, u8) func_conf_select;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) pre_init;
    void (*)(struct dw_pcie_ep *) init;
    void (*)(struct dw_pcie_ep *) deinit;
    int (*)(struct dw_pcie_ep *, u8, unsigned int, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
    unsigned int (*)(struct dw_pcie_ep *, u8) get_dbi_offset;
    unsigned int (*)(struct dw_pcie_ep *, u8) get_dbi2_offset;
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
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
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
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
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
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
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
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, enum pci_epc_irq_type, u8) raise_irq;
}
```
</details>
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
<code>int (*)(struct dw_pcie_ep *, enum pci_epc_irq_type, u8) raise_irq</code> ➡️ <code>int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u8) raise_irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u8) raise_irq</code> ➡️ <code>int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features</code>
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
<code>unsigned int (*)(struct dw_pcie_ep *, u8) func_conf_select</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct dw_pcie_ep *) pre_init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dw_pcie_ep *) init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dw_pcie_ep *) deinit</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct dw_pcie_ep *, u8) get_dbi_offset</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int (*)(struct dw_pcie_ep *, u8) get_dbi2_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dw_pcie_ep *) ep_init</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int (*)(struct dw_pcie_ep *, u8) func_conf_select</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq</code> ➡️ <code>int (*)(struct dw_pcie_ep *, u8, unsigned int, u16) raise_irq</code>
</li>
</ul>
</details>
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
struct dw_pcie_ep_ops {
    void (*)(struct dw_pcie_ep *) ep_init;
    int (*)(struct dw_pcie_ep *, u8, enum pci_epc_irq_type, u16) raise_irq;
    const struct pci_epc_features * (*)(struct dw_pcie_ep *) get_features;
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
