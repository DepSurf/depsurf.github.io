# Function: <code>_find_first_zero_bit</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "_find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584824640,
      "name": "_find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:96",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "lib/idr.c:ida_alloc_range",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/dev.c:__dev_alloc_name",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584824640,
      "name": "_find_first_zero_bit",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "_find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242928,
      "name": "_find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:96",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "lib/idr.c:ida_alloc_range",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/dev.c:__dev_alloc_name",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242928,
      "name": "_find_first_zero_bit",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "_find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586083952,
      "name": "_find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:117",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "lib/idr.c:ida_alloc_range",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/char/misc.c:misc_register",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/intel/dmar.c:alloc_iommu",
        "drivers/iommu/intel/iommu.c:domain_add_dev_info",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/dev.c:__dev_alloc_name",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586083952,
      "name": "_find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "_find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587065136,
      "name": "_find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:123",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd/iommu.c:domain_id_alloc",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/dev.c:__dev_alloc_name",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065136,
      "name": "_find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "_find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587323200,
      "name": "_find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:123",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/trace/trace.c:close_pipe_on_cpu",
        "kernel/bpf/cpumask.c:bpf_cpumask_full",
        "kernel/bpf/cpumask.c:bpf_cpumask_first_zero",
        "fs/iomap/buffered-io.c:iomap_iop_set_range_uptodate",
        "fs/iomap/buffered-io.c:iomap_page_release",
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd/iommu.c:domain_id_alloc",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/dev.c:__dev_alloc_name",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323200,
      "name": "_find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```

```json
{
  "name": "_find_first_zero_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587606144,
      "name": "_find_first_zero_bit",
      "external": true,
      "loc": "lib/find_bit.c:123",
      "file": "lib/find_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_va_page_full",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_slot",
        "arch/x86/kernel/apic/io_apic.c:io_apic_unique_id",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/sched/core.c:mm_cid_get",
        "kernel/trace/trace.c:close_pipe_on_cpu",
        "kernel/bpf/cpumask.c:bpf_cpumask_full",
        "kernel/bpf/cpumask.c:bpf_cpumask_first_zero",
        "fs/iomap/buffered-io.c:ifs_free",
        "fs/iomap/buffered-io.c:ifs_set_range_uptodate",
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar",
        "drivers/acpi/numa/srat.c:acpi_map_pxm_to_node",
        "drivers/char/agp/generic.c:agp_get_key",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/scsi/sr.c:sr_probe",
        "net/core/dev.c:__dev_alloc_name",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "lib/idr.c:ida_alloc_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587606144,
      "name": "_find_first_zero_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
long unsigned int _find_first_zero_bit(const long unsigned int * addr, long unsigned int size)
```
</details>
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
