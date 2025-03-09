# Struct: <code>pci_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    u8 dma_alias_devfn;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_interrupt;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int ignore_hotplug;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int multifunction;
    unsigned int is_added;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int has_secondary_link;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_interrupt;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int ignore_hotplug;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct cpumask * irq_affinity;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int multifunction;
    unsigned int is_added;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int has_secondary_link;
    unsigned int non_compliant_bars;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_interrupt;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int multifunction;
    unsigned int is_added;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int has_secondary_link;
    unsigned int non_compliant_bars;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int multifunction;
    unsigned int is_added;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int is_thunderbolt;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int has_secondary_link;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int multifunction;
    unsigned int is_added;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int is_thunderbolt;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int has_secondary_link;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int is_thunderbolt;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int has_secondary_link;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int has_secondary_link;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int has_secondary_link;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    u16 dpc_cap;
    unsigned int dpc_rp_extensions;
    u8 dpc_rp_log_size;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    u16 pri_cap;
    u32 pri_reqs_alloc;
    unsigned int pasid_required;
    u16 pasid_cap;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    struct rcec_ea * rcec_ea;
    struct pci_dev * rcec;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3hot_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    u16 l1ss;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int external_facing;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    unsigned int no_command_memory;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    u16 dpc_cap;
    unsigned int dpc_rp_extensions;
    u8 dpc_rp_log_size;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    u16 pri_cap;
    u32 pri_reqs_alloc;
    unsigned int pasid_required;
    u16 pasid_cap;
    u16 pasid_features;
    u16 acs_cap;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    struct rcec_ea * rcec_ea;
    struct pci_dev * rcec;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3hot_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    u16 l1ss;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int external_facing;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    unsigned int no_command_memory;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    u16 dpc_cap;
    unsigned int dpc_rp_extensions;
    u8 dpc_rp_log_size;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    u16 pri_cap;
    u32 pri_reqs_alloc;
    unsigned int pasid_required;
    u16 pasid_cap;
    u16 pasid_features;
    u16 acs_cap;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    struct rcec_ea * rcec_ea;
    struct pci_dev * rcec;
    u32 devcap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3hot_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    u16 l1ss;
    unsigned int pasid_no_tlp;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int external_facing;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    unsigned int no_command_memory;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd vpd;
    u16 dpc_cap;
    unsigned int dpc_rp_extensions;
    u8 dpc_rp_log_size;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    u16 pri_cap;
    u32 pri_reqs_alloc;
    unsigned int pasid_required;
    u16 pasid_cap;
    u16 pasid_features;
    u16 acs_cap;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
    u8[7] reset_methods;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    struct rcec_ea * rcec_ea;
    struct pci_dev * rcec;
    u32 devcap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3hot_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    u16 l1ss;
    unsigned int pasid_no_tlp;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int is_msi_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int external_facing;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    unsigned int no_command_memory;
    unsigned int rom_bar_overlap;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    void * msix_base;
    raw_spinlock_t msi_lock;
    struct pci_vpd vpd;
    u16 dpc_cap;
    unsigned int dpc_rp_extensions;
    u8 dpc_rp_log_size;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    u16 pri_cap;
    u32 pri_reqs_alloc;
    unsigned int pasid_required;
    u16 pasid_cap;
    u16 pasid_features;
    u16 acs_cap;
    phys_addr_t rom;
    size_t romlen;
    const char * driver_override;
    long unsigned int priv_flags;
    u8[7] reset_methods;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    struct rcec_ea * rcec_ea;
    struct pci_dev * rcec;
    u32 devcap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3hot_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    u16 l1ss;
    unsigned int pasid_no_tlp;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    struct resource driver_exclusive_resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int is_msi_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int external_facing;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    unsigned int no_command_memory;
    unsigned int rom_bar_overlap;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    u16 ptm_cap;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    void * msix_base;
    raw_spinlock_t msi_lock;
    struct pci_vpd vpd;
    u16 dpc_cap;
    unsigned int dpc_rp_extensions;
    u8 dpc_rp_log_size;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    u16 pri_cap;
    u32 pri_reqs_alloc;
    unsigned int pasid_required;
    u16 pasid_cap;
    u16 pasid_features;
    struct pci_p2pdma * p2pdma;
    u16 acs_cap;
    phys_addr_t rom;
    size_t romlen;
    const char * driver_override;
    long unsigned int priv_flags;
    u8[7] reset_methods;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    struct rcec_ea * rcec_ea;
    struct pci_dev * rcec;
    u32 devcap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3hot_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    u16 l1ss;
    unsigned int pasid_no_tlp;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    struct resource driver_exclusive_resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int is_msi_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int external_facing;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    unsigned int no_command_memory;
    unsigned int rom_bar_overlap;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    spinlock_t pcie_cap_lock;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    u16 ptm_cap;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    void * msix_base;
    raw_spinlock_t msi_lock;
    struct pci_vpd vpd;
    u16 dpc_cap;
    unsigned int dpc_rp_extensions;
    u8 dpc_rp_log_size;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    u16 pri_cap;
    u32 pri_reqs_alloc;
    unsigned int pasid_required;
    u16 pasid_cap;
    u16 pasid_features;
    struct pci_p2pdma * p2pdma;
    struct xarray doe_mbs;
    u16 acs_cap;
    phys_addr_t rom;
    size_t romlen;
    const char * driver_override;
    long unsigned int priv_flags;
    u8[7] reset_methods;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    struct rcec_ea * rcec_ea;
    struct pci_dev * rcec;
    u32 devcap;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    u8 pm_cap;
    unsigned int imm_ready;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3hot_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    u16 l1ss;
    unsigned int ltr_path;
    unsigned int pasid_no_tlp;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    struct resource driver_exclusive_resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int is_msi_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int external_facing;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    unsigned int no_command_memory;
    unsigned int rom_bar_overlap;
    unsigned int rom_attr_enabled;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    spinlock_t pcie_cap_lock;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    u16 ptm_cap;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    void * msix_base;
    raw_spinlock_t msi_lock;
    struct pci_vpd vpd;
    u16 dpc_cap;
    unsigned int dpc_rp_extensions;
    u8 dpc_rp_log_size;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    u16 pri_cap;
    u32 pri_reqs_alloc;
    unsigned int pasid_required;
    u16 pasid_cap;
    u16 pasid_features;
    struct pci_p2pdma * p2pdma;
    struct xarray doe_mbs;
    u16 acs_cap;
    phys_addr_t rom;
    size_t romlen;
    const char * driver_override;
    long unsigned int priv_flags;
    u8[7] reset_methods;
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
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
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
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_dev {
    struct list_head bus_list;
    struct pci_bus * bus;
    struct pci_bus * subordinate;
    void * sysdata;
    struct proc_dir_entry * procent;
    struct pci_slot * slot;
    unsigned int devfn;
    short unsigned int vendor;
    short unsigned int device;
    short unsigned int subsystem_vendor;
    short unsigned int subsystem_device;
    unsigned int class;
    u8 revision;
    u8 hdr_type;
    u16 aer_cap;
    struct aer_stats * aer_stats;
    u8 pcie_cap;
    u8 msi_cap;
    u8 msix_cap;
    u8 pcie_mpss;
    u8 rom_base_reg;
    u8 pin;
    u16 pcie_flags_reg;
    long unsigned int * dma_alias_mask;
    struct pci_driver * driver;
    u64 dma_mask;
    struct device_dma_parameters dma_parms;
    pci_power_t current_state;
    unsigned int imm_ready;
    u8 pm_cap;
    unsigned int pme_support;
    unsigned int pme_poll;
    unsigned int d1_support;
    unsigned int d2_support;
    unsigned int no_d1d2;
    unsigned int no_d3cold;
    unsigned int bridge_d3;
    unsigned int d3cold_allowed;
    unsigned int mmio_always_on;
    unsigned int wakeup_prepared;
    unsigned int runtime_d3cold;
    unsigned int skip_bus_pm;
    unsigned int ignore_hotplug;
    unsigned int hotplug_user_indicators;
    unsigned int clear_retrain_link;
    unsigned int d3_delay;
    unsigned int d3cold_delay;
    struct pcie_link_state * link_state;
    unsigned int ltr_path;
    unsigned int eetlp_prefix_path;
    pci_channel_state_t error_state;
    struct device dev;
    int cfg_size;
    unsigned int irq;
    struct resource[17] resource;
    bool match_driver;
    unsigned int transparent;
    unsigned int io_window;
    unsigned int pref_window;
    unsigned int pref_64_window;
    unsigned int multifunction;
    unsigned int is_busmaster;
    unsigned int no_msi;
    unsigned int no_64bit_msi;
    unsigned int block_cfg_access;
    unsigned int broken_parity_status;
    unsigned int irq_reroute_variant;
    unsigned int msi_enabled;
    unsigned int msix_enabled;
    unsigned int ari_enabled;
    unsigned int ats_enabled;
    unsigned int pasid_enabled;
    unsigned int pri_enabled;
    unsigned int is_managed;
    unsigned int needs_freset;
    unsigned int state_saved;
    unsigned int is_physfn;
    unsigned int is_virtfn;
    unsigned int reset_fn;
    unsigned int is_hotplug_bridge;
    unsigned int shpc_managed;
    unsigned int is_thunderbolt;
    unsigned int untrusted;
    unsigned int __aer_firmware_first_valid;
    unsigned int __aer_firmware_first;
    unsigned int broken_intx_masking;
    unsigned int io_window_1k;
    unsigned int irq_managed;
    unsigned int non_compliant_bars;
    unsigned int is_probed;
    unsigned int link_active_reporting;
    unsigned int no_vf_scan;
    pci_dev_flags_t dev_flags;
    atomic_t enable_cnt;
    u32[16] saved_config_space;
    struct hlist_head saved_cap_space;
    struct bin_attribute * rom_attr;
    int rom_attr_enabled;
    struct bin_attribute *[17] res_attr;
    struct bin_attribute *[17] res_attr_wc;
    unsigned int broken_cmd_compl;
    unsigned int ptm_root;
    unsigned int ptm_enabled;
    u8 ptm_granularity;
    const struct attribute_group * * msi_irq_groups;
    struct pci_vpd * vpd;
    struct pci_sriov * sriov;
    struct pci_dev * physfn;
    u16 ats_cap;
    u8 ats_stu;
    atomic_t ats_ref_cnt;
    u32 pri_reqs_alloc;
    u16 pasid_features;
    phys_addr_t rom;
    size_t romlen;
    char * driver_override;
    long unsigned int priv_flags;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int * dma_alias_mask</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int bridge_d3</code>
</li>
<li>
<b>Field added. </b>
<code>struct cpumask * irq_affinity</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int non_compliant_bars</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 dma_alias_devfn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 aer_cap</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int hotplug_user_indicators</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ptm_root</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int ptm_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>u8 ptm_granularity</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cpumask * irq_affinity</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int pasid_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pri_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int is_thunderbolt</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int is_probed</code>
</li>
<li>
<b>Field added. </b>
<code>u32 pri_reqs_alloc</code>
</li>
<li>
<b>Field added. </b>
<code>u16 pasid_features</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int priv_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int pme_interrupt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int ltr_path</code>
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
<code>unsigned int broken_cmd_compl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int is_added</code>
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
<code>struct aer_stats * aer_stats</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int imm_ready</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int eetlp_prefix_path</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int shpc_managed</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int untrusted</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int link_active_reporting</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_vf_scan</code>
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
<code>unsigned int skip_bus_pm</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int clear_retrain_link</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int io_window</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pref_window</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pref_64_window</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int has_secondary_link</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u16 dpc_cap</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int dpc_rp_extensions</code>
</li>
<li>
<b>Field added. </b>
<code>u8 dpc_rp_log_size</code>
</li>
<li>
<b>Field added. </b>
<code>u16 pri_cap</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pasid_required</code>
</li>
<li>
<b>Field added. </b>
<code>u16 pasid_cap</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int __aer_firmware_first_valid</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int __aer_firmware_first</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t ats_ref_cnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rcec_ea * rcec_ea</code>
</li>
<li>
<b>Field added. </b>
<code>struct pci_dev * rcec</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int d3hot_delay</code>
</li>
<li>
<b>Field added. </b>
<code>u16 l1ss</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int external_facing</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int no_command_memory</code>
</li>
<li>
<b>Field added. </b>
<code>u16 acs_cap</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int d3_delay</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct bin_attribute * rom_attr</code>
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
<code>u32 devcap</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int pasid_no_tlp</code>
</li>
<li>
<b>Field added. </b>
<code>u8[7] reset_methods</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int reset_fn</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct pci_vpd * vpd</code> ➡️ <code>struct pci_vpd vpd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int is_msi_managed</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int rom_bar_overlap</code>
</li>
<li>
<b>Field added. </b>
<code>void * msix_base</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t msi_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int runtime_d3cold</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct attribute_group * * msi_irq_groups</code>
</li>
<li>
<b>Field type changed. </b>
<code>char * driver_override</code> ➡️ <code>const char * driver_override</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct resource driver_exclusive_resource</code>
</li>
<li>
<b>Field added. </b>
<code>u16 ptm_cap</code>
</li>
<li>
<b>Field added. </b>
<code>struct pci_p2pdma * p2pdma</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>spinlock_t pcie_cap_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray doe_mbs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int rom_attr_enabled</code> ➡️ <code>unsigned int rom_attr_enabled</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int broken_cmd_compl</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u16 aer_cap</code>
</li>
<li>
<b>Field removed. </b>
<code>struct aer_stats * aer_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pcie_link_state * link_state</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int ltr_path</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int broken_cmd_compl</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int ptm_root</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int ptm_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 ptm_granularity</code>
</li>
</ul>
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
