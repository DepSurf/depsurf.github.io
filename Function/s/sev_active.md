# Function: <code>sev_active</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602726498,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:410",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvm_memblock_free",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370160,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602896939,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:344",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvm_memblock_free",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/dma/direct.c:dma_direct_free",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383680,
      "name": "sev_active",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604694248,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:344",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "kernel/dma/direct.c:dma_direct_free_pages",
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:__dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411536,
      "name": "sev_active",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579427328,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:349",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables",
        "fs/proc/vmcore.c:elfcorehdr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427296,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579430496,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:348",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430464,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579456016,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:348",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:sev_map_percpu_data",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455984,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579452608,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:381",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sev_setup_arch",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:sev_map_percpu_data",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452560,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579454976,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:375",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:arch_has_restricted_virtio_memory_access",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sev_setup_arch",
        "arch/x86/mm/mem_encrypt.c:sme_early_init",
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454960,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579520384,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:376",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:arch_has_restricted_virtio_memory_access",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sev_setup_arch",
        "arch/x86/mm/mem_encrypt.c:sme_early_init",
        "arch/x86/mm/mem_encrypt.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt.c:sme_map_bootdata"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520368,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579426336,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:348",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426304,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579355440,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:348",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355408,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579426256,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:348",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426224,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool sev_active()
```

```json
{
  "name": "sev_active",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579435440,
      "name": "sev_active",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt.c:348",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt.c:sme_early_init"
      ],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_setup_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435408,
      "name": "sev_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool sev_active()
```
</details>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool sev_active()
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
bool sev_active()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool sev_active()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool sev_active()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool sev_active()
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
