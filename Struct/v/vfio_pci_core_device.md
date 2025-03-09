# Struct: <code>vfio_pci_core_device</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vfio_pci_core_device {
    struct vfio_device vdev;
    struct pci_dev * pdev;
    void *[6] barmap;
    bool[6] bar_mmap_supported;
    u8 * pci_config_map;
    u8 * vconfig;
    struct perm_bits * msi_perm;
    spinlock_t irqlock;
    struct mutex igate;
    struct vfio_pci_irq_ctx * ctx;
    int num_ctx;
    int irq_type;
    int num_regions;
    struct vfio_pci_region * region;
    u8 msi_qmax;
    u8 msix_bar;
    u16 msix_size;
    u32 msix_offset;
    u32[7] rbar;
    bool pci_2_3;
    bool virq_disabled;
    bool reset_works;
    bool extended_caps;
    bool bardirty;
    bool has_vga;
    bool needs_reset;
    bool nointx;
    bool needs_pm_restore;
    struct pci_saved_state * pci_saved_state;
    struct pci_saved_state * pm_save;
    int ioeventfds_nr;
    struct eventfd_ctx * err_trigger;
    struct eventfd_ctx * req_trigger;
    struct list_head dummy_resources_list;
    struct mutex ioeventfds_lock;
    struct list_head ioeventfds_list;
    struct vfio_pci_vf_token * vf_token;
    struct notifier_block nb;
    struct mutex vma_lock;
    struct list_head vma_list;
    struct rw_semaphore memory_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vfio_pci_core_device {
    struct vfio_device vdev;
    struct pci_dev * pdev;
    void *[6] barmap;
    bool[6] bar_mmap_supported;
    u8 * pci_config_map;
    u8 * vconfig;
    struct perm_bits * msi_perm;
    spinlock_t irqlock;
    struct mutex igate;
    struct vfio_pci_irq_ctx * ctx;
    int num_ctx;
    int irq_type;
    int num_regions;
    struct vfio_pci_region * region;
    u8 msi_qmax;
    u8 msix_bar;
    u16 msix_size;
    u32 msix_offset;
    u32[7] rbar;
    bool pci_2_3;
    bool virq_disabled;
    bool reset_works;
    bool extended_caps;
    bool bardirty;
    bool has_vga;
    bool needs_reset;
    bool nointx;
    bool needs_pm_restore;
    struct pci_saved_state * pci_saved_state;
    struct pci_saved_state * pm_save;
    int ioeventfds_nr;
    struct eventfd_ctx * err_trigger;
    struct eventfd_ctx * req_trigger;
    struct list_head dummy_resources_list;
    struct mutex ioeventfds_lock;
    struct list_head ioeventfds_list;
    struct vfio_pci_vf_token * vf_token;
    struct list_head sriov_pfs_item;
    struct vfio_pci_core_device * sriov_pf_core_dev;
    struct notifier_block nb;
    struct mutex vma_lock;
    struct list_head vma_list;
    struct rw_semaphore memory_lock;
}
```
</details>
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct vfio_pci_core_device {
    struct vfio_device vdev;
    struct pci_dev * pdev;
    void *[6] barmap;
    bool[6] bar_mmap_supported;
    u8 * pci_config_map;
    u8 * vconfig;
    struct perm_bits * msi_perm;
    spinlock_t irqlock;
    struct mutex igate;
    struct vfio_pci_irq_ctx * ctx;
    int num_ctx;
    int irq_type;
    int num_regions;
    struct vfio_pci_region * region;
    u8 msi_qmax;
    u8 msix_bar;
    u16 msix_size;
    u32 msix_offset;
    u32[7] rbar;
    bool pci_2_3;
    bool virq_disabled;
    bool reset_works;
    bool extended_caps;
    bool bardirty;
    bool has_vga;
    bool needs_reset;
    bool nointx;
    bool needs_pm_restore;
    struct pci_saved_state * pci_saved_state;
    struct pci_saved_state * pm_save;
    int ioeventfds_nr;
    struct eventfd_ctx * err_trigger;
    struct eventfd_ctx * req_trigger;
    struct list_head dummy_resources_list;
    struct mutex ioeventfds_lock;
    struct list_head ioeventfds_list;
    struct vfio_pci_vf_token * vf_token;
    struct notifier_block nb;
    struct mutex vma_lock;
    struct list_head vma_list;
    struct rw_semaphore memory_lock;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head sriov_pfs_item</code>
</li>
<li>
<b>Field added. </b>
<code>struct vfio_pci_core_device * sriov_pf_core_dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct vfio_pci_core_device {
    struct vfio_device vdev;
    struct pci_dev * pdev;
    void *[6] barmap;
    bool[6] bar_mmap_supported;
    u8 * pci_config_map;
    u8 * vconfig;
    struct perm_bits * msi_perm;
    spinlock_t irqlock;
    struct mutex igate;
    struct vfio_pci_irq_ctx * ctx;
    int num_ctx;
    int irq_type;
    int num_regions;
    struct vfio_pci_region * region;
    u8 msi_qmax;
    u8 msix_bar;
    u16 msix_size;
    u32 msix_offset;
    u32[7] rbar;
    bool pci_2_3;
    bool virq_disabled;
    bool reset_works;
    bool extended_caps;
    bool bardirty;
    bool has_vga;
    bool needs_reset;
    bool nointx;
    bool needs_pm_restore;
    struct pci_saved_state * pci_saved_state;
    struct pci_saved_state * pm_save;
    int ioeventfds_nr;
    struct eventfd_ctx * err_trigger;
    struct eventfd_ctx * req_trigger;
    struct list_head dummy_resources_list;
    struct mutex ioeventfds_lock;
    struct list_head ioeventfds_list;
    struct vfio_pci_vf_token * vf_token;
    struct list_head sriov_pfs_item;
    struct vfio_pci_core_device * sriov_pf_core_dev;
    struct notifier_block nb;
    struct mutex vma_lock;
    struct list_head vma_list;
    struct rw_semaphore memory_lock;
}
```
</details>
</li>
</ul>
