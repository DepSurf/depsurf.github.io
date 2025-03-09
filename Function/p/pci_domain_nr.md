# Function: <code>pci_domain_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578935517,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948375,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578956779,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208796,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/kernel/apic/htirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234811,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271561,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583279703,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_find_bus",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303056,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583307393,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/proc.c:pci_proc_attach_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310923,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583347768,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/pcie/aer/aerdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583349914,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583365656,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367002,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583370014,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583378498,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583381064,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583388536,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583391880,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_enable_sriov"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583592604,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583897854,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583899019,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583908069,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584299924,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584306720,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586149905,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586154443,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586161798,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pci_read",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pcibios_add_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578928429,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578945303,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953665,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209644,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/kernel/apic/htirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553072,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583582464,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583591426,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583614730,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583620650,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583621883,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583659713,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/pcie/aer/aerdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583661882,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583678884,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680762,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683378,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583691782,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583694568,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/hotplug-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583702968,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583707421,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583915215,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584228846,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584230052,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584239123,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584649654,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584653337,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562737,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567275,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586575712,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:35",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578928909,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578945767,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578955068,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221308,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "arch/x86/kernel/apic/htirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672298,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583689632,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719861,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583728562,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583751930,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757850,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583759083,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583797281,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/pcie/aer/aerdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583799274,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583817089,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818874,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821490,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829943,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832680,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/hotplug-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583841288,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845757,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056103,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410318,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584411524,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420737,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584835702,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839421,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586744353,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586748827,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586757264,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:38",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578922301,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578938839,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578947810,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219116,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "arch/x86/kernel/apic/htirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/htirq.c:htirq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712345,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730153,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_bus_read_dev_vendor_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583760253,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583769407,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583793815,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583800486,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583840289,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/pcie/aer/aerdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583842236,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583860065,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583861887,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583864382,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583872892,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583875144,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/hotplug-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583883144,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583887258,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894913,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584116820,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584494820,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504640,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584925370,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584947374,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586871588,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586876027,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586884101,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:39",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578924365,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578941015,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578949437,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583969791,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583992731,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019629,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584029231,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055904,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584063654,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584103009,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pcie/aer/aerdrv_acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584104965,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584123668,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125503,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584127982,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584136412,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146632,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584149973,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157617,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584387745,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584905179,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584914656,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585346702,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585368718,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587359796,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364123,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587372762,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578929613,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578943479,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578952611,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584166239,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584186843,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584216480,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_reassigndev_resource_alignment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584226495,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584255388,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584263014,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584275463,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_gpu_hda"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584298413,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584305522,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584324255,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584325926,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584332101,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584334058,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584337062,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584340860,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584341395,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584351803,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584363449,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584366962,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584375093,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584609281,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585135669,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585136715,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585146210,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585588830,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585611149,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663198,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587667819,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587676570,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578931405,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578945479,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578954283,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584254031,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275547,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584283087,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584316143,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584345148,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584352742,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584369239,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_gpu_hda"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584393133,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584401186,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584419488,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420913,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584427652,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584429416,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584432310,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436012,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584436544,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584446219,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584458553,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584462098,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584466645,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584706849,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585246469,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585247515,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585257042,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585712782,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585735453,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585742309,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587794398,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587799019,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587807866,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:40",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578938334,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951062,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961003,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450075,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584465883,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584477489,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584511120,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584538831,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584547560,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584567592,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584593599,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584596832,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616479,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584617369,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619651,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584626252,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584631047,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584632910,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633421,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584642884,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584655401,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584659491,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584664069,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584907987,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585458786,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585459715,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585466469,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585940702,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585964708,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973989,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588099758,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588103745,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588113354,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578940814,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953494,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963435,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293095,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584586774,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584601259,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584612977,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584647136,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584673967,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584682952,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584704456,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584731445,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584734656,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584754207,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584755353,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584757523,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584763948,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584768743,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584770606,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584771117,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584780548,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584793001,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584797651,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584802341,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585043699,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585599189,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585600435,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607173,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586083886,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586108020,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586119477,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587062425,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588307080,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588309441,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319050,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578947870,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578960294,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970971,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322071,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585262723,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585278619,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585289768,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585330320,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585360671,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386017,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585388712,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585396440,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585398221,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585418904,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585444878,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585446423,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585448168,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585455261,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585459959,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585462076,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585462589,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585471879,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585485481,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585491955,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585495157,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585746640,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586321845,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586323123,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_external_startup",
        "drivers/xen/dbgp.c:xen_dbgp_reset_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586329844,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586831507,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586861844,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586870373,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587901833,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591125006,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591129265,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591139418,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578949790,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961718,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578974359,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_get_topology",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_mapping_show",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324759,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591390775,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585437323,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585443784,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585483552,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585512415,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518741,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585530517,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/rcec.c:walk_rcec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591399794,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585546040,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585553192,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585554941,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585575592,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591411134,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585594775,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596472,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591412982,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591414088,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591415827,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607133,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585613639,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624499,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585627333,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585866016,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586439813,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586441075,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_external_startup",
        "drivers/xen/dbgp.c:xen_dbgp_reset_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586447689,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586888154,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586916206,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586919211,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587962425,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591211440,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591215425,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591223626,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578948765,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578967014,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980027,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054220,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327479,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591333030,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585317451,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585323980,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363173,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585390975,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585396972,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585408901,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/rcec.c:walk_rcec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591341986,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585424296,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585431752,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585433501,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585453464,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591353485,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585473175,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585475363,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591355361,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591356467,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591358187,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585485533,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585492084,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503087,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585506101,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585744069,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586323749,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586325140,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_external_startup",
        "drivers/xen/dbgp.c:xen_dbgp_reset_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586331545,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586768954,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797150,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586800507,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587844713,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591160567,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591164807,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591172874,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959565,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979558,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995355,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075116,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382135,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592358018,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585773339,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585780412,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585822557,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585852639,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585859932,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585870981,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/rcec.c:walk_rcec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585882023,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585889304,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585897176,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585898909,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585919832,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592381012,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585939415,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585941664,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592383220,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592384422,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592386385,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585952139,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585958918,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585970799,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973877,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586226645,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586630997,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/viot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/viot.c:viot_pci_dev_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586843491,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586844900,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_external_startup",
        "drivers/xen/dbgp.c:xen_dbgp_reset_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851427,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587324106,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587353810,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587357451,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588448617,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592012319,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592016615,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592026394,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578976082,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578993175,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009699,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100419,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447283,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594220399,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586959083,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586968587,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587013011,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587045741,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587059237,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/msi/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587063905,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/rcec.c:walk_rcec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587076567,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587086328,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594235750,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/edr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587095405,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587097324,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587122613,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594244799,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587142481,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587144921,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594247030,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594248347,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594250254,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587156280,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587163753,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587176718,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587180133,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587464977,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587896709,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/viot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/viot.c:viot_pci_dev_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588130323,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_pci_notifier",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588130712,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_external_startup",
        "drivers/xen/dbgp.c:xen_dbgp_reset_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588138279,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588638602,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588662359,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:dmar_ats_supported",
        "drivers/iommu/intel/iommu.c:dmar_ats_supported",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589849133,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593780187,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593782055,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593793370,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_device_add",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627513415,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013927,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579030349,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136995,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579534147,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588096290,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588122251,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588133323,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588183107,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588226505,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588243013,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/msi/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588249073,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/rcec.c:walk_rcec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588262604,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588273753,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281617,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/edr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588286205,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588288364,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588321141,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588343708,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588346721,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588349417,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588356940,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588360179,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588364843,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588365240,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588376846,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588390546,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588394405,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588402240,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pdma_map_segment",
        "drivers/pci/p2pdma.c:calc_map_type_and_dist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588731553,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589246325,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/viot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/viot.c:viot_pci_dev_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518838,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_pci_notifier",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589519256,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_external_startup",
        "drivers/xen/dbgp.c:xen_dbgp_reset_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589527746,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590076288,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:check_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590108794,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590135813,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:dmar_ats_supported",
        "drivers/iommu/intel/iommu.c:dmar_ats_supported",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595719515,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595722535,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595736458,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_device_add",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619258327,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013975,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035761,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_update_device_location",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137891,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547059,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588370722,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588397515,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588407963,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588459101,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588501993,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518565,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/msi/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588524625,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/rcec.c:walk_rcec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588538293,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588549385,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588557441,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/edr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588562109,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588564268,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588597237,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588619788,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588622975,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588625673,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588633052,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636270,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588640907,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588641294,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588652814,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588666562,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588670389,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588678144,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pdma_map_segment",
        "drivers/pci/p2pdma.c:calc_map_type_and_dist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589019601,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589543084,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/viot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/viot.c:viot_pci_dev_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589819802,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_pci_notifier",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589820232,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_external_startup",
        "drivers/xen/dbgp.c:xen_dbgp_reset_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828818,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590388819,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590422538,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590449573,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:dmar_ats_supported",
        "drivers/iommu/intel/iommu.c:dmar_ats_supported",
        "drivers/iommu/intel/iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596244811,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596248311,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596262442,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_device_add",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621550999,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pci_init",
        "arch/x86/events/intel/uncore.c:uncore_pci_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe",
        "arch/x86/events/intel/uncore.c:uncore_pci_find_dev_pmu_from_types",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment",
        "arch/x86/events/intel/uncore.c:uncore_die_to_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038903,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060529,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:spr_update_device_location",
        "arch/x86/events/intel/uncore_snbep.c:discover_upi_topology",
        "arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164323,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575331,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588665490,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588693499,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588703147,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588756189,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588800409,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588817157,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/msi/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/irqdomain.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588823265,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/rcec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/rcec.c:walk_rcec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588837821,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849001,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588857169,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pcie/edr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/edr.c:edr_handle_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588861885,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588864092,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588896949,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588919964,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588923151,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588925849,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588933319,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_core.c:init_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588936590,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588941307,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588941694,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588953356,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588967202,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588971029,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588978970,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pdma_map_segment",
        "drivers/pci/p2pdma.c:calc_map_type_and_dist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589323952,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589851420,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/acpi/viot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/viot.c:viot_pci_dev_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590156202,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_pci_notifier",
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590156632,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_external_startup",
        "drivers/xen/dbgp.c:xen_dbgp_reset_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590165826,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590731374,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590766682,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/intel/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590787177,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:dmar_ats_supported",
        "drivers/iommu/intel/iommu.c:dmar_ats_supported",
        "drivers/iommu/intel/iommu.c:device_lookup_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592046495,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/gpu/drm/drm_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_file.c:drm_show_fdinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592189167,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "drivers/gpu/drm/drm_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_pci.c:drm_pci_set_busid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597126699,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_restore_msi",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597130199,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597145098,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:44",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_device_add",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/controller/dwc/pcie-al.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/acpi/arm64/iort.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230102744,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 3230124484,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 3230132704,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 3230171132,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 3230199424,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 3230208344,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230229832,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230254380,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3230257680,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3230261888,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 3230276020,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3230281088,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-label.c:find_smbios_instance_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pci_domain_nr(struct pci_bus * bus)
```

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282607904,
      "name": "pci_domain_nr",
      "external": true,
      "loc": "arch/powerpc/kernel/pci-common.c:324",
      "file": "arch/powerpc/kernel/pci-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus",
        "arch/powerpc/kernel/pci-common.c:pcibios_resource_survey",
        "arch/powerpc/kernel/pci-common.c:pcibios_resource_survey",
        "arch/powerpc/kernel/pci-common.c:pcibios_resource_survey",
        "arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources",
        "arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range",
        "arch/powerpc/kernel/pci-common.c:pci_mmap_legacy_page_range"
      ],
      "caller_func": [
        "arch/powerpc/kernel/pci-hotplug.c:pci_hp_remove_devices",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_setup_bus_PE",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pe_level_printk",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pe_level_printk",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_bridge_reset",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_bridge_reset",
        "arch/powerpc/platforms/powernv/ocxl.c:find_link",
        "arch/powerpc/platforms/powernv/ocxl.c:find_link",
        "arch/powerpc/platforms/pseries/iommu.c:pci_dma_dev_setup_pSeriesLP",
        "arch/powerpc/platforms/pseries/iommu.c:pci_dma_bus_setup_pSeriesLP",
        "arch/powerpc/platforms/pseries/pci.c:pseries_set_pe_num",
        "arch/powerpc/platforms/pseries/pci_dlpar.c:remove_phb_dynamic",
        "drivers/pci/access.c:pci_generic_config_write32",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pci.c:pci_dev_str_match",
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus",
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources",
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282604928,
      "name": "pci_domain_nr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275529174,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275548562,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275555512,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275586014,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275608912,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275615514,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275634380,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275657530,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275660468,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275676810,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275678114,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275679976,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275686052,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275688272,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275691642,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275692030,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275698800,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_set_desc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275711256,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "include/linux/pci.h:1602",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578940814,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953494,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963435,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584538934,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584553419,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584565137,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584597616,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584624431,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633432,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584654936,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584680965,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584683456,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584703023,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584704169,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584706339,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584712764,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584717559,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584719422,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584719933,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584729333,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584741753,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584746403,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584751077,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584982323,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585361813,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363059,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585368821,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585845006,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585868260,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585879845,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587910728,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587913089,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587922698,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578937790,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951286,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961115,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584467094,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584481579,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584493297,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527424,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584554255,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584563240,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584584088,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584611077,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584614580,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633791,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584634937,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584637107,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584643532,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584648327,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650190,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650701,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584660101,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584672521,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584677171,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584681861,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584891219,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585704046,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585728164,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585739621,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586710345,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587629233,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587638663,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578940750,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578953430,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963371,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584536934,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584551419,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584563137,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584597296,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584624127,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633112,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584654616,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584681605,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584684816,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584704367,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705513,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584707683,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584714108,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584718903,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584720766,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584721277,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730708,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584743161,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584747811,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584752501,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584995283,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585549589,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585550835,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585557573,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586033902,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586058036,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586069493,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016985,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588244136,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588246497,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256106,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_domain_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578941328,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pcibus_to_physid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578954006,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:snb_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963451,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298935,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584644678,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_generic_config_write32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584659163,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_sort_bf_cmp",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584670881,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_str_match"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584704992,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/search.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/search.c:pci_get_domain_bus_and_slot",
        "drivers/pci/search.c:pci_find_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584731823,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:__pci_bridge_assign_resources",
        "drivers/pci/setup-bus.c:__pci_bus_assign_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584740808,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/proc.c:pci_proc_attach_device",
        "drivers/pci/proc.c:proc_bus_pci_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/slot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584762312,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584789301,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:aer_print_port_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584792913,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584812010,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584813161,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584815267,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821692,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584826487,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_ctrl.c:board_added"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584828350,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584828861,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/shpchp_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584838276,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584850729,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/msi.c:pci_msi_domain_calc_hwirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584855379,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/iov.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584860021,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/pci/pci-label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585101459,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/acpi/pci_irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585657541,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/pci.c:xen_add_device",
        "drivers/xen/pci.c:xen_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585658787,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/dbgp.c:xen_dbgp_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665525,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/xen/platform-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586141868,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dmar.c:dmar_find_matched_drhd_unit",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info",
        "drivers/iommu/dmar.c:dmar_alloc_pci_notify_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586166055,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_find_matched_atsr_unit",
        "drivers/iommu/intel-iommu.c:device_to_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586177701,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-pasid.c:get_alias_pasid_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587124153,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_fill_devs",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_vga_decode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378552,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs",
        "arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588381921,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/fixup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_write",
        "arch/x86/pci/fixup.c:quirk_pcie_aspm_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588391626,
      "name": "pci_domain_nr",
      "external": false,
      "loc": "arch/x86/include/asm/pci.h:41",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pcibios_add_device",
        "arch/x86/pci/common.c:pci_write",
        "arch/x86/pci/common.c:pci_read"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int pci_domain_nr(struct pci_bus * bus)
```
</details>
</li>
</ul>
