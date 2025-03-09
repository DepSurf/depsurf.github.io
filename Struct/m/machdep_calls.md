# Struct: <code>machdep_calls</code>

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
struct machdep_calls {
    char * name;
    void (*)() iommu_save;
    void (*)() iommu_restore;
    long unsigned int (*)() memory_block_size;
    void (*)(struct device *, u64) dma_set_mask;
    int (*)() probe;
    void (*)() setup_arch;
    void (*)(struct seq_file *) show_cpuinfo;
    void (*)(struct seq_file *, int) show_percpuinfo;
    long unsigned int (*)(unsigned int) get_proc_freq;
    void (*)() init_IRQ;
    unsigned int (*)() get_irq;
    void (*)() pcibios_fixup;
    void (*)(struct pci_dev *) pci_irq_fixup;
    int (*)(struct pci_host_bridge *) pcibios_root_bridge_prepare;
    int (*)(struct pci_controller *) pci_setup_phb;
    volatile void (*)(char *) * restart;
    volatile void (*)() * halt;
    void (*)(char *) panic;
    void (*)() cpu_die;
    long int (*)() time_init;
    int (*)(struct rtc_time *) set_rtc_time;
    void (*)(struct rtc_time *) get_rtc_time;
    time64_t (*)() get_boot_time;
    unsigned char (*)(int) rtc_read_val;
    void (*)(int, unsigned char) rtc_write_val;
    void (*)() calibrate_decr;
    void (*)(char *, short unsigned int) progress;
    void (*)(char *, unsigned int, int) log_error;
    unsigned char (*)(int) nvram_read_val;
    void (*)(int, unsigned char) nvram_write_val;
    ssize_t (*)(char *, size_t, loff_t *) nvram_write;
    ssize_t (*)(char *, size_t, loff_t *) nvram_read;
    ssize_t (*)() nvram_size;
    void (*)() nvram_sync;
    int (*)(struct pt_regs *) system_reset_exception;
    int (*)(struct pt_regs *) machine_check_exception;
    int (*)(struct pt_regs *) handle_hmi_exception;
    int (*)(struct pt_regs *) hmi_exception_early;
    long int (*)(struct pt_regs *) machine_check_early;
    bool (*)(struct pt_regs *) mce_check_early_recovery;
    long int (*)(unsigned int, void) feature_call;
    int (*)(struct pci_dev *, int) pci_get_legacy_ide_irq;
    pgprot_t (*)(struct file *, long unsigned int, long unsigned int, pgprot_t) phys_mem_access_prot;
    void (*)() power_save;
    void (*)() enable_pmcs;
    int (*)(long unsigned int, long unsigned int) set_dabr;
    int (*)(long unsigned int, long unsigned int) set_dawr;
    int (*)(struct pci_controller *, unsigned char, unsigned char) pci_exclude_device;
    void (*)(struct pci_dev *) pcibios_fixup_resources;
    void (*)(struct pci_bus *) pcibios_fixup_bus;
    void (*)(struct pci_controller *) pcibios_fixup_phb;
    void (*)(struct pci_dev *) pcibios_bus_add_device;
    resource_size_t (*)() pcibios_default_alignment;
    void (*)(struct pci_dev *) pcibios_fixup_sriov;
    resource_size_t (*)(struct pci_dev *, int) pcibios_iov_resource_alignment;
    int (*)(struct pci_dev *, u16) pcibios_sriov_enable;
    int (*)(struct pci_dev *) pcibios_sriov_disable;
    void (*)() machine_shutdown;
    void (*)(int, int) kexec_cpu_down;
    int (*)(struct kimage *) machine_kexec_prepare;
    void (*)(struct kimage *) machine_kexec;
    void (*)() suspend_disable_irqs;
    void (*)() suspend_enable_irqs;
    int (*)() suspend_disable_cpu;
    ssize_t (*)(const char *, size_t) cpu_probe;
    ssize_t (*)(const char *, size_t) cpu_release;
    int (*)(long unsigned int *) get_random_seed;
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
struct machdep_calls {
    char * name;
    void (*)() iommu_save;
    void (*)() iommu_restore;
    long unsigned int (*)() memory_block_size;
    void (*)(struct device *, u64) dma_set_mask;
    int (*)() probe;
    void (*)() setup_arch;
    void (*)(struct seq_file *) show_cpuinfo;
    void (*)(struct seq_file *, int) show_percpuinfo;
    long unsigned int (*)(unsigned int) get_proc_freq;
    void (*)() init_IRQ;
    unsigned int (*)() get_irq;
    void (*)() pcibios_fixup;
    void (*)(struct pci_dev *) pci_irq_fixup;
    int (*)(struct pci_host_bridge *) pcibios_root_bridge_prepare;
    int (*)(struct pci_controller *) pci_setup_phb;
    volatile void (*)(char *) * restart;
    volatile void (*)() * halt;
    void (*)(char *) panic;
    void (*)() cpu_die;
    long int (*)() time_init;
    int (*)(struct rtc_time *) set_rtc_time;
    void (*)(struct rtc_time *) get_rtc_time;
    time64_t (*)() get_boot_time;
    unsigned char (*)(int) rtc_read_val;
    void (*)(int, unsigned char) rtc_write_val;
    void (*)() calibrate_decr;
    void (*)(char *, short unsigned int) progress;
    void (*)(char *, unsigned int, int) log_error;
    unsigned char (*)(int) nvram_read_val;
    void (*)(int, unsigned char) nvram_write_val;
    ssize_t (*)(char *, size_t, loff_t *) nvram_write;
    ssize_t (*)(char *, size_t, loff_t *) nvram_read;
    ssize_t (*)() nvram_size;
    void (*)() nvram_sync;
    int (*)(struct pt_regs *) system_reset_exception;
    int (*)(struct pt_regs *) machine_check_exception;
    int (*)(struct pt_regs *) handle_hmi_exception;
    int (*)(struct pt_regs *) hmi_exception_early;
    long int (*)(struct pt_regs *) machine_check_early;
    bool (*)(struct pt_regs *) mce_check_early_recovery;
    long int (*)(unsigned int, void) feature_call;
    int (*)(struct pci_dev *, int) pci_get_legacy_ide_irq;
    pgprot_t (*)(struct file *, long unsigned int, long unsigned int, pgprot_t) phys_mem_access_prot;
    void (*)() power_save;
    void (*)() enable_pmcs;
    int (*)(long unsigned int, long unsigned int) set_dabr;
    int (*)(long unsigned int, long unsigned int) set_dawr;
    int (*)(struct pci_controller *, unsigned char, unsigned char) pci_exclude_device;
    void (*)(struct pci_dev *) pcibios_fixup_resources;
    void (*)(struct pci_bus *) pcibios_fixup_bus;
    void (*)(struct pci_controller *) pcibios_fixup_phb;
    void (*)(struct pci_dev *) pcibios_bus_add_device;
    resource_size_t (*)() pcibios_default_alignment;
    void (*)(struct pci_dev *) pcibios_fixup_sriov;
    resource_size_t (*)(struct pci_dev *, int) pcibios_iov_resource_alignment;
    int (*)(struct pci_dev *, u16) pcibios_sriov_enable;
    int (*)(struct pci_dev *) pcibios_sriov_disable;
    void (*)() machine_shutdown;
    void (*)(int, int) kexec_cpu_down;
    int (*)(struct kimage *) machine_kexec_prepare;
    void (*)(struct kimage *) machine_kexec;
    void (*)() suspend_disable_irqs;
    void (*)() suspend_enable_irqs;
    int (*)() suspend_disable_cpu;
    ssize_t (*)(const char *, size_t) cpu_probe;
    ssize_t (*)(const char *, size_t) cpu_release;
    int (*)(long unsigned int *) get_random_seed;
}
```
</details>
</li>
</ul>
