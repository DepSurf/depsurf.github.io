# Struct: <code>pnv_phb</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pnv_phb {
    struct pci_controller * hose;
    enum pnv_phb_type type;
    enum pnv_phb_model model;
    u64 hub_id;
    u64 opal_id;
    int flags;
    void * regs;
    u64 regs_phys;
    int initialized;
    spinlock_t lock;
    int has_dbgfs;
    struct dentry * dbgfs;
    unsigned int msi_base;
    unsigned int msi32_support;
    struct msi_bitmap msi_bmp;
    int (*)(struct pnv_phb *, struct pci_dev *, unsigned int, unsigned int, unsigned int, struct msi_msg *) msi_setup;
    void (*)(struct pnv_phb *, struct pci_dev *) dma_dev_setup;
    int (*)(struct pnv_phb *) init_m64;
    int (*)(struct pnv_phb *, int) get_pe_state;
    void (*)(struct pnv_phb *, int) freeze_pe;
    int (*)(struct pnv_phb *, int, int) unfreeze_pe;
    struct (anon) ioda;
    unsigned int diag_data_size;
    u8 * diag_data;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct pnv_phb {
    struct pci_controller * hose;
    enum pnv_phb_type type;
    enum pnv_phb_model model;
    u64 hub_id;
    u64 opal_id;
    int flags;
    void * regs;
    u64 regs_phys;
    int initialized;
    spinlock_t lock;
    int has_dbgfs;
    struct dentry * dbgfs;
    unsigned int msi_base;
    unsigned int msi32_support;
    struct msi_bitmap msi_bmp;
    int (*)(struct pnv_phb *, struct pci_dev *, unsigned int, unsigned int, unsigned int, struct msi_msg *) msi_setup;
    void (*)(struct pnv_phb *, struct pci_dev *) dma_dev_setup;
    int (*)(struct pnv_phb *) init_m64;
    int (*)(struct pnv_phb *, int) get_pe_state;
    void (*)(struct pnv_phb *, int) freeze_pe;
    int (*)(struct pnv_phb *, int, int) unfreeze_pe;
    struct (anon) ioda;
    unsigned int diag_data_size;
    u8 * diag_data;
}
```
</details>
</li>
</ul>
