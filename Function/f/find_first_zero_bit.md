# Function: <code>find_first_zero_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583031040,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:100",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:topology_update_package_map",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "block/blk-tag.c:blk_queue_start_tag",
        "block/blk-tag.c:blk_queue_start_tag",
        "block/blk-mq-tag.c:blk_mq_has_free_tags",
        "lib/idr.c:idr_mark_full",
        "lib/idr.c:idr_get_empty_slot",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583031040,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323488,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:100",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "block/blk-tag.c:blk_queue_start_tag",
        "block/blk-tag.c:blk_queue_start_tag",
        "block/blk-mq-tag.c:blk_mq_has_free_tags",
        "lib/idr.c:idr_get_empty_slot",
        "lib/idr.c:idr_mark_full",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323488,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448400,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:100",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "block/blk-tag.c:blk_queue_start_tag",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/lightnvm/sysblk.c:nvm_dev_factory",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448400,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469040,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:100",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "block/blk-tag.c:blk_queue_start_tag",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:__dev_alloc_name",
        "lib/idr.c:ida_get_new_above"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469040,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649968,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:100",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/hmm.c:hmm_device_new",
        "block/blk-tag.c:blk_queue_start_tag",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_get_new_above"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649968,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868000,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:120",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/hmm.c:hmm_device_new",
        "block/blk-tag.c:blk_queue_start_tag",
        "block/blk-tag.c:blk_queue_start_tag",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msi_irq",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_get_new_above"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868000,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953280,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:120",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/hmm.c:hmm_device_new",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:dmar_parse_one_drhd",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953280,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584133024,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:116",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:handle_swbp",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/iommu/intel-iommu.c:domain_attach_iommu",
        "drivers/scsi/scsi_logging.c:scsi_log_reserve_buffer",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/soundwire/bus.c:sdw_handle_slave_status",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133024,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255424,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:116",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:handle_swbp",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255424,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584663184,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:124",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "kernel/events/uprobes.c:xol_take_insn_slot",
        "lib/idr.c:ida_alloc_range",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:__dev_alloc_name",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584663184,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780544,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:126",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "kernel/events/uprobes.c:xol_take_insn_slot",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "lib/idr.c:ida_alloc_range",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:__dev_alloc_name",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780544,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579265493,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579317315,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298105,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582790153,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585079088,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585251188,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585512083,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585527761,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586081237,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586610389,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586651681,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586678165,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_get_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586746927,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764540,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:alloc_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586782869,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:domain_attach_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587488039,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589112955,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589239832,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780529,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:129",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
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
  "name": "find_first_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579307093,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367637,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581543241,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583116167,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585525934,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585707093,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585980848,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585983864,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585997761,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586578050,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587153692,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587199937,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587226693,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_get_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587295407,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587319676,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:alloc_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587339349,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588064239,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588389679,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589831339,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589964008,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590539953,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/asm-generic/bitops/find.h:132",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
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
  "name": "find_first_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579364341,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430241,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581893993,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600650,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586658404,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586679066,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586875526,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587196519,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587199445,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587214747,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587837984,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588459332,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588503267,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530453,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_get_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601648,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588634998,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/dmar.c:alloc_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588664755,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:domain_add_dev_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589428260,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589787223,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591350388,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591510111,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592149569,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593595633,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:163",
      "file": "net/ncsi/ncsi-manage.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579436133,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514280,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582327305,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584205956,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587906043,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588024850,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588426263,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588429635,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588446891,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180160,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589895137,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589975093,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_get_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590059702,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:domain_id_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590125295,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:domain_attach_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591004990,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591437431,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593105330,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593281295,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593975793,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595523217,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595759285,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:293",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range"
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
  "name": "find_first_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448213,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579526459,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168200,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446578,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:close_pipe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374608,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_full",
        "kernel/bpf/cpumask.c:bpf_cpumask_first_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582528537,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584435795,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177547,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588299191,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588703991,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588707155,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588725996,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589474224,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590204361,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590284693,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_get_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590371174,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:domain_id_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590439813,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:domain_attach_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591358686,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591852512,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593556690,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593740143,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594352913,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596031761,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596283643,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range"
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
  "name": "find_first_zero_bit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579478021,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555227,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580214488,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556114,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:close_pipe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541936,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "kernel/bpf/cpumask.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumask.c:bpf_cpumask_full",
        "kernel/bpf/cpumask.c:bpf_cpumask_first_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582697523,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:pre_ssout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584657396,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:ifs_free",
        "fs/iomap/buffered-io.c:ifs_set_range_uptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588468395,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbitmap_queue_get_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588592603,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589004839,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589008051,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/pci/endpoint/pci-epf-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589026492,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589780116,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_map_pxm_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590545167,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590625829,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_get_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590736926,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590798645,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:domain_attach_iommu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591708797,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594329362,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594486743,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__dev_alloc_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595155409,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596896337,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597168420,
      "name": "find_first_zero_bit",
      "external": false,
      "loc": "include/linux/find.h:358",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_alloc_range"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224160,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:116",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:handle_swbp",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224160,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159376,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:116",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:handle_swbp",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159376,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207920,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:116",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:handle_swbp",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207920,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312480,
      "name": "find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:116",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "kernel/events/uprobes.c:handle_swbp",
        "lib/sbitmap.c:sbitmap_any_bit_clear",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_outbound_atu",
        "drivers/tty/serial/max310x.c:max310x_probe",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd_iommu.c:domain_id_alloc",
        "drivers/iommu/dmar.c:alloc_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/dev.c:dev_alloc_name_ns",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312480,
      "name": "find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
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
