# Function: <code>memblock_phys_free</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int memblock_phys_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_phys_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594706886,
      "name": "memblock_phys_free",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/mm/init.c:init_mem_mapping",
        "mm/memblock.c:memblock_free",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_free_ring",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594706886,
      "name": "memblock_phys_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int memblock_phys_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_phys_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596450160,
      "name": "memblock_phys_free",
      "external": true,
      "loc": "mm/memblock.c:842",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:ima_free_kexec_buffer",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/platform/efi/memmap.c:__efi_memmap_free",
        "mm/memblock.c:memblock_double_array",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596450160,
      "name": "memblock_phys_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int memblock_phys_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_phys_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596991488,
      "name": "memblock_phys_free",
      "external": true,
      "loc": "mm/memblock.c:855",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:ima_free_kexec_buffer",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/platform/efi/memmap.c:__efi_memmap_free",
        "mm/memblock.c:memblock_double_array",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596991488,
      "name": "memblock_phys_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int memblock_phys_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_phys_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597920624,
      "name": "memblock_phys_free",
      "external": true,
      "loc": "mm/memblock.c:895",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/platform/efi/memmap.c:__efi_memmap_free",
        "kernel/crash_core.c:reserve_crashkernel_generic",
        "mm/memblock.c:memblock_double_array",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597920624,
      "name": "memblock_phys_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int memblock_phys_free(phys_addr_t base, phys_addr_t size)
```
</details>
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
