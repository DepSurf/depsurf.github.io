# Struct: <code>pci_controller_ops</code>

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
struct pci_controller_ops {
    void (*)(struct pci_dev *) dma_dev_setup;
    void (*)(struct pci_bus *) dma_bus_setup;
    bool (*)(struct pci_dev *, u64) iommu_bypass_supported;
    int (*)(struct pci_bus *) probe_mode;
    bool (*)(struct pci_dev *) enable_device_hook;
    void (*)(struct pci_dev *) disable_device;
    void (*)(struct pci_dev *) release_device;
    resource_size_t (*)(struct pci_bus *, long unsigned int) window_alignment;
    void (*)(struct pci_bus *, long unsigned int) setup_bridge;
    void (*)(struct pci_dev *) reset_secondary_bus;
    int (*)(struct pci_dev *, int, int) setup_msi_irqs;
    void (*)(struct pci_dev *) teardown_msi_irqs;
    void (*)(struct pci_controller *) shutdown;
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
struct pci_controller_ops {
    void (*)(struct pci_dev *) dma_dev_setup;
    void (*)(struct pci_bus *) dma_bus_setup;
    bool (*)(struct pci_dev *, u64) iommu_bypass_supported;
    int (*)(struct pci_bus *) probe_mode;
    bool (*)(struct pci_dev *) enable_device_hook;
    void (*)(struct pci_dev *) disable_device;
    void (*)(struct pci_dev *) release_device;
    resource_size_t (*)(struct pci_bus *, long unsigned int) window_alignment;
    void (*)(struct pci_bus *, long unsigned int) setup_bridge;
    void (*)(struct pci_dev *) reset_secondary_bus;
    int (*)(struct pci_dev *, int, int) setup_msi_irqs;
    void (*)(struct pci_dev *) teardown_msi_irqs;
    void (*)(struct pci_controller *) shutdown;
}
```
</details>
</li>
</ul>
