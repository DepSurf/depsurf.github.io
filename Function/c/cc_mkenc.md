# Function: <code>cc_mkenc</code>

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
u64 cc_mkenc(u64 val)
```

```json
{
  "name": "cc_mkenc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578856080,
      "name": "cc_mkenc",
      "external": true,
      "loc": "arch/x86/coco/core.c:99",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/mm/mem_encrypt_amd.c:sme_early_init",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856080,
      "name": "cc_mkenc",
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
u64 cc_mkenc(u64 val)
```

```json
{
  "name": "cc_mkenc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858464,
      "name": "cc_mkenc",
      "external": true,
      "loc": "arch/x86/coco/core.c:99",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pgprot.c:add_encrypt_protection_map",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858464,
      "name": "cc_mkenc",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
u64 cc_mkenc(u64 val)
```

```json
{
  "name": "cc_mkenc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578856080,
      "name": "cc_mkenc",
      "external": true,
      "loc": "arch/x86/coco/core.c:113",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/pgprot.c:add_encrypt_protection_map",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856080,
      "name": "cc_mkenc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
u64 cc_mkenc(u64 val)
```

```json
{
  "name": "cc_mkenc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578856160,
      "name": "cc_mkenc",
      "external": true,
      "loc": "arch/x86/coco/core.c:113",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/pgprot.c:add_encrypt_protection_map",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable",
        "arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve",
        "fs/proc/vmcore.c:remap_oldmem_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856160,
      "name": "cc_mkenc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
u64 cc_mkenc(u64 val)
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
