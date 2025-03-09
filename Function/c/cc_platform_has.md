# Function: <code>cc_platform_has</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool cc_platform_has(enum cc_attr attr)
```

```json
{
  "name": "cc_platform_has",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579451856,
      "name": "cc_platform_has",
      "external": true,
      "loc": "arch/x86/kernel/cc_platform.c:62",
      "file": "arch/x86/kernel/cc_platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451856,
      "name": "cc_platform_has",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool cc_platform_has(enum cc_attr attr)
```

```json
{
  "name": "cc_platform_has",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578855712,
      "name": "cc_platform_has",
      "external": true,
      "loc": "arch/x86/coco/core.c:84",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/sev.c:snp_init_platform_device",
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu",
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:memremap_should_map_decrypted",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem",
        "arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:elfcorehdr_read_notes",
        "arch/x86/lib/iomem.c:memset_io",
        "drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type",
        "drivers/iommu/amd/init.c:amd_iommu_detect",
        "drivers/iommu/amd/init.c:copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855712,
      "name": "cc_platform_has",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
bool cc_platform_has(enum cc_attr attr)
```

```json
{
  "name": "cc_platform_has",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858064,
      "name": "cc_platform_has",
      "external": true,
      "loc": "arch/x86/coco/core.c:84",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/sev.c:snp_init_platform_device",
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu",
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:memremap_should_map_decrypted",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem",
        "arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_smt_disable",
        "kernel/cpu.c:smp_shutdown_nonboot_cpus",
        "kernel/cpu.c:cpu_device_down",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:elfcorehdr_read_notes",
        "arch/x86/lib/iomem.c:memset_io",
        "drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type",
        "drivers/iommu/amd/init.c:amd_iommu_detect",
        "drivers/iommu/amd/init.c:__copy_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858064,
      "name": "cc_platform_has",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
bool cc_platform_has(enum cc_attr attr)
```

```json
{
  "name": "cc_platform_has",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596905984,
      "name": "cc_platform_has",
      "external": true,
      "loc": "arch/x86/coco/core.c:100",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/sev.c:snp_init_platform_device",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu",
        "arch/x86/kernel/sev.c:snp_accept_memory",
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/mm/ioremap.c:memremap_should_map_decrypted",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_prepare",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "kernel/cpu.c:cpu_down_maps_locked",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:elfcorehdr_read_notes",
        "arch/x86/lib/iomem.c:memset_io",
        "drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type",
        "drivers/iommu/amd/init.c:amd_iommu_detect",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596905984,
      "name": "cc_platform_has",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool cc_platform_has(enum cc_attr attr)
```

```json
{
  "name": "cc_platform_has",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597831072,
      "name": "cc_platform_has",
      "external": true,
      "loc": "arch/x86/coco/core.c:100",
      "file": "arch/x86/coco/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/realmode/init.c:setup_real_mode",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/nmi.c:exc_nmi",
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "arch/x86/kernel/pci-dma.c:pci_iommu_alloc",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages",
        "arch/x86/kernel/machine_kexec_64.c:arch_kexec_post_alloc_pages",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/crash_dump_64.c:elfcorehdr_read",
        "arch/x86/kernel/kvm.c:kvm_init_platform",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu",
        "arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration",
        "arch/x86/kernel/kvmclock.c:kvmclock_init_mem",
        "arch/x86/kernel/sev.c:snp_init_platform_device",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu",
        "arch/x86/kernel/sev.c:snp_accept_memory",
        "arch/x86/kernel/sev.c:snp_set_memory_private",
        "arch/x86/kernel/sev.c:snp_set_memory_shared",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/mm/ioremap.c:memremap_should_map_decrypted",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_collect_map_flags",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust",
        "arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks",
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:force_dma_unencrypted",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_setup_arch",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_finish",
        "arch/x86/mm/mem_encrypt_amd.c:amd_enc_status_change_prepare",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/platform/efi/efi_64.c:efi_update_mem_attr",
        "arch/x86/platform/efi/efi_64.c:__map_region",
        "arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings",
        "kernel/cpu.c:cpu_down_maps_locked",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "fs/proc/vmcore.c:__read_vmcore",
        "fs/proc/vmcore.c:elfcorehdr_read_notes",
        "arch/x86/lib/iomem.c:memset_io",
        "drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type",
        "drivers/iommu/amd/init.c:amd_iommu_detect",
        "drivers/iommu/amd/init.c:__copy_device_table",
        "drivers/firmware/efi/unaccepted_memory.c:accept_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597831072,
      "name": "cc_platform_has",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool cc_platform_has(enum cc_attr attr)
```
</details>
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
