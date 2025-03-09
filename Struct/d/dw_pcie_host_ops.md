# Struct: <code>dw_pcie_host_ops</code>

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
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    void (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    int (*)(struct pcie_port *, struct msi_controller *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    int (*)(struct pcie_port *, struct msi_controller *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
    void (*)(int, struct pcie_port *) msi_irq_ack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
    void (*)(int, struct pcie_port *) msi_irq_ack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *) host_init;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *) host_init;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *) host_init;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *) host_init;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct dw_pcie_rp *) host_init;
    void (*)(struct dw_pcie_rp *) host_deinit;
    int (*)(struct dw_pcie_rp *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct dw_pcie_rp *) host_init;
    void (*)(struct dw_pcie_rp *) host_deinit;
    int (*)(struct dw_pcie_rp *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct dw_pcie_rp *) init;
    void (*)(struct dw_pcie_rp *) deinit;
    void (*)(struct dw_pcie_rp *) post_init;
    int (*)(struct dw_pcie_rp *) msi_init;
    void (*)(struct dw_pcie_rp *) pme_turn_off;
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
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
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
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
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
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
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
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    void (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *, int) msi_set_irq;
    void (*)(struct pcie_port *, int) msi_clear_irq;
    phys_addr_t (*)(struct pcie_port *) get_msi_addr;
    u32 (*)(struct pcie_port *, int) get_msi_data;
    void (*)(struct pcie_port *) scan_bus;
    int (*)(struct pcie_port *, struct msi_controller *) msi_host_init;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct pcie_port *) host_init</code> ➡️ <code>int (*)(struct pcie_port *) host_init</code>
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
<code>void (*)(struct pcie_port *) set_num_vectors</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(int, struct pcie_port *) msi_irq_ack</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pcie_port *, struct msi_controller *) msi_host_init</code> ➡️ <code>int (*)(struct pcie_port *) msi_host_init</code>
</li>
</ul>
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
<b>Field removed. </b>
<code>void (*)(struct pcie_port *, int) msi_set_irq</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct pcie_port *, int) msi_clear_irq</code>
</li>
<li>
<b>Field removed. </b>
<code>phys_addr_t (*)(struct pcie_port *) get_msi_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 (*)(struct pcie_port *, int) get_msi_data</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(int, struct pcie_port *) msi_irq_ack</code>
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
<b>Field removed. </b>
<code>int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct pcie_port *, int, int, u32) wr_own_conf</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct pcie_port *) scan_bus</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct pcie_port *) set_num_vectors</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct dw_pcie_rp *) host_deinit</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pcie_port *) host_init</code> ➡️ <code>int (*)(struct dw_pcie_rp *) host_init</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct pcie_port *) msi_host_init</code> ➡️ <code>int (*)(struct dw_pcie_rp *) msi_host_init</code>
</li>
</ul>
</details>
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
<code>int (*)(struct dw_pcie_rp *) init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dw_pcie_rp *) deinit</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dw_pcie_rp *) post_init</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct dw_pcie_rp *) msi_init</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct dw_pcie_rp *) pme_turn_off</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dw_pcie_rp *) host_init</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct dw_pcie_rp *) host_deinit</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct dw_pcie_rp *) msi_host_init</code>
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
struct dw_pcie_host_ops {
    int (*)(struct pcie_port *, int, int, u32 *) rd_own_conf;
    int (*)(struct pcie_port *, int, int, u32) wr_own_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32 *) rd_other_conf;
    int (*)(struct pcie_port *, struct pci_bus *, unsigned int, int, int, u32) wr_other_conf;
    int (*)(struct pcie_port *) host_init;
    void (*)(struct pcie_port *) scan_bus;
    void (*)(struct pcie_port *) set_num_vectors;
    int (*)(struct pcie_port *) msi_host_init;
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
