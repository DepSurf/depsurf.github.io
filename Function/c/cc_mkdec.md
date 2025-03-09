# Function: <code>cc_mkdec</code>

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
u64 cc_mkdec(u64 val)
```

```json
{
  "name": "cc_mkdec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578856000,
      "name": "cc_mkdec",
      "external": true,
      "loc": "arch/x86/coco/core.c:118",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot",
        "kernel/dma/direct.c:dma_direct_mmap",
        "mm/memory.c:vm_iomap_memory",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856000,
      "name": "cc_mkdec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
u64 cc_mkdec(u64 val)
```

```json
{
  "name": "cc_mkdec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858368,
      "name": "cc_mkdec",
      "external": true,
      "loc": "arch/x86/coco/core.c:118",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot",
        "kernel/dma/direct.c:dma_direct_mmap",
        "mm/memory.c:vm_iomap_memory",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858368,
      "name": "cc_mkdec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 cc_mkdec(u64 val)
```

```json
{
  "name": "cc_mkdec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855968,
      "name": "cc_mkdec",
      "external": true,
      "loc": "arch/x86/coco/core.c:135",
      "file": "arch/x86/coco/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot",
        "kernel/dma/direct.c:dma_direct_mmap",
        "mm/memory.c:vm_iomap_memory",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855968,
      "name": "cc_mkdec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 cc_mkdec(u64 val)
```

```json
{
  "name": "cc_mkdec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856048,
      "name": "cc_mkdec",
      "external": true,
      "loc": "arch/x86/coco/core.c:135",
      "file": "arch/x86/coco/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_map_gpa",
        "arch/x86/coco/tdx/tdx.c:tdx_map_gpa",
        "arch/x86/coco/tdx/tdx.c:tdx_hcall_get_quote",
        "arch/x86/entry/vdso/vma.c:vvar_fault",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot",
        "kernel/dma/direct.c:dma_direct_mmap",
        "mm/memory.c:vm_iomap_memory",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mmap",
        "drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856048,
      "name": "cc_mkdec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
u64 cc_mkdec(u64 val)
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
