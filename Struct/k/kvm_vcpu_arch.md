# Struct: <code>kvm_vcpu_arch</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_arch {
    long unsigned int[17] regs;
    u32 regs_avail;
    u32 regs_dirty;
    long unsigned int cr0;
    long unsigned int cr0_guest_owned_bits;
    long unsigned int cr2;
    long unsigned int cr3;
    long unsigned int cr4;
    long unsigned int cr4_guest_owned_bits;
    long unsigned int cr4_guest_rsvd_bits;
    long unsigned int cr8;
    u32 host_pkru;
    u32 pkru;
    u32 hflags;
    u64 efer;
    u64 apic_base;
    struct kvm_lapic * apic;
    bool apicv_active;
    bool load_eoi_exitmap_pending;
    long unsigned int[4] ioapic_handled_vectors;
    long unsigned int apic_attention;
    int32_t apic_arb_prio;
    int mp_state;
    u64 ia32_misc_enable_msr;
    u64 smbase;
    u64 smi_count;
    bool tpr_access_reporting;
    bool xsaves_enabled;
    u64 ia32_xss;
    u64 microcode_version;
    u64 arch_capabilities;
    u64 perf_capabilities;
    struct kvm_mmu * mmu;
    struct kvm_mmu root_mmu;
    struct kvm_mmu guest_mmu;
    struct kvm_mmu nested_mmu;
    struct kvm_mmu * walk_mmu;
    struct kvm_mmu_memory_cache mmu_pte_list_desc_cache;
    struct kvm_mmu_memory_cache mmu_shadow_page_cache;
    struct kvm_mmu_memory_cache mmu_gfn_array_cache;
    struct kvm_mmu_memory_cache mmu_page_header_cache;
    struct fpu * user_fpu;
    struct fpu * guest_fpu;
    u64 xcr0;
    u64 guest_supported_xcr0;
    struct kvm_pio_request pio;
    void * pio_data;
    void * guest_ins_data;
    u8 event_exit_inst_len;
    struct kvm_queued_exception exception;
    struct kvm_queued_interrupt interrupt;
    int halt_request;
    int cpuid_nent;
    struct kvm_cpuid_entry2 * cpuid_entries;
    long unsigned int cr3_lm_rsvd_bits;
    int maxphyaddr;
    int max_tdp_level;
    struct x86_emulate_ctxt * emulate_ctxt;
    bool emulate_regs_need_sync_to_vcpu;
    bool emulate_regs_need_sync_from_vcpu;
    int (*)(struct kvm_vcpu *) complete_userspace_io;
    gpa_t time;
    struct pvclock_vcpu_time_info hv_clock;
    unsigned int hw_tsc_khz;
    struct gfn_to_hva_cache pv_time;
    bool pv_time_enabled;
    bool pvclock_set_guest_stopped_request;
    struct (anon) st;
    u64 l1_tsc_offset;
    u64 tsc_offset;
    u64 last_guest_tsc;
    u64 last_host_tsc;
    u64 tsc_offset_adjustment;
    u64 this_tsc_nsec;
    u64 this_tsc_write;
    u64 this_tsc_generation;
    bool tsc_catchup;
    bool tsc_always_catchup;
    s8 virtual_tsc_shift;
    u32 virtual_tsc_mult;
    u32 virtual_tsc_khz;
    s64 ia32_tsc_adjust_msr;
    u64 msr_ia32_power_ctl;
    u64 tsc_scaling_ratio;
    atomic_t nmi_queued;
    unsigned int nmi_pending;
    bool nmi_injected;
    bool smi_pending;
    struct kvm_mtrr mtrr_state;
    u64 pat;
    unsigned int switch_db_regs;
    long unsigned int[4] db;
    long unsigned int dr6;
    long unsigned int dr7;
    long unsigned int[4] eff_db;
    long unsigned int guest_debug_dr7;
    u64 msr_platform_info;
    u64 msr_misc_features_enables;
    u64 mcg_cap;
    u64 mcg_status;
    u64 mcg_ctl;
    u64 mcg_ext_ctl;
    u64 * mce_banks;
    u64 mmio_gva;
    unsigned int mmio_access;
    gfn_t mmio_gfn;
    u64 mmio_gen;
    struct kvm_pmu pmu;
    long unsigned int singlestep_rip;
    struct kvm_vcpu_hv hyperv;
    cpumask_var_t wbinvd_dirty_mask;
    long unsigned int last_retry_eip;
    long unsigned int last_retry_addr;
    struct (anon) apf;
    struct (anon) osvw;
    struct (anon) pv_eoi;
    u64 msr_kvm_poll_control;
    bool write_fault_to_shadow_pgtable;
    long unsigned int exit_qualification;
    struct (anon) pv;
    int pending_ioapic_eoi;
    int pending_external_vector;
    bool preempted_in_kernel;
    bool l1tf_flush_l1d;
    unsigned int last_vmentry_cpu;
    u64 msr_hwcr;
    struct (anon) pv_cpuid;
    bool guest_state_protected;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_arch {
    long unsigned int[17] regs;
    u32 regs_avail;
    u32 regs_dirty;
    long unsigned int cr0;
    long unsigned int cr0_guest_owned_bits;
    long unsigned int cr2;
    long unsigned int cr3;
    long unsigned int cr4;
    long unsigned int cr4_guest_owned_bits;
    long unsigned int cr4_guest_rsvd_bits;
    long unsigned int cr8;
    u32 host_pkru;
    u32 pkru;
    u32 hflags;
    u64 efer;
    u64 apic_base;
    struct kvm_lapic * apic;
    bool apicv_active;
    bool load_eoi_exitmap_pending;
    long unsigned int[4] ioapic_handled_vectors;
    long unsigned int apic_attention;
    int32_t apic_arb_prio;
    int mp_state;
    u64 ia32_misc_enable_msr;
    u64 smbase;
    u64 smi_count;
    bool tpr_access_reporting;
    bool xsaves_enabled;
    u64 ia32_xss;
    u64 microcode_version;
    u64 arch_capabilities;
    u64 perf_capabilities;
    struct kvm_mmu * mmu;
    struct kvm_mmu root_mmu;
    struct kvm_mmu guest_mmu;
    struct kvm_mmu nested_mmu;
    struct kvm_mmu * walk_mmu;
    struct kvm_mmu_memory_cache mmu_pte_list_desc_cache;
    struct kvm_mmu_memory_cache mmu_shadow_page_cache;
    struct kvm_mmu_memory_cache mmu_gfn_array_cache;
    struct kvm_mmu_memory_cache mmu_page_header_cache;
    struct fpu * user_fpu;
    struct fpu * guest_fpu;
    u64 xcr0;
    u64 guest_supported_xcr0;
    struct kvm_pio_request pio;
    void * pio_data;
    void * guest_ins_data;
    u8 event_exit_inst_len;
    struct kvm_queued_exception exception;
    struct kvm_queued_interrupt interrupt;
    int halt_request;
    int cpuid_nent;
    struct kvm_cpuid_entry2 * cpuid_entries;
    u64 reserved_gpa_bits;
    int maxphyaddr;
    int max_tdp_level;
    struct x86_emulate_ctxt * emulate_ctxt;
    bool emulate_regs_need_sync_to_vcpu;
    bool emulate_regs_need_sync_from_vcpu;
    int (*)(struct kvm_vcpu *) complete_userspace_io;
    gpa_t time;
    struct pvclock_vcpu_time_info hv_clock;
    unsigned int hw_tsc_khz;
    struct gfn_to_hva_cache pv_time;
    bool pv_time_enabled;
    bool pvclock_set_guest_stopped_request;
    struct (anon) st;
    u64 l1_tsc_offset;
    u64 tsc_offset;
    u64 last_guest_tsc;
    u64 last_host_tsc;
    u64 tsc_offset_adjustment;
    u64 this_tsc_nsec;
    u64 this_tsc_write;
    u64 this_tsc_generation;
    bool tsc_catchup;
    bool tsc_always_catchup;
    s8 virtual_tsc_shift;
    u32 virtual_tsc_mult;
    u32 virtual_tsc_khz;
    s64 ia32_tsc_adjust_msr;
    u64 msr_ia32_power_ctl;
    u64 tsc_scaling_ratio;
    atomic_t nmi_queued;
    unsigned int nmi_pending;
    bool nmi_injected;
    bool smi_pending;
    struct kvm_mtrr mtrr_state;
    u64 pat;
    unsigned int switch_db_regs;
    long unsigned int[4] db;
    long unsigned int dr6;
    long unsigned int dr7;
    long unsigned int[4] eff_db;
    long unsigned int guest_debug_dr7;
    u64 msr_platform_info;
    u64 msr_misc_features_enables;
    u64 mcg_cap;
    u64 mcg_status;
    u64 mcg_ctl;
    u64 mcg_ext_ctl;
    u64 * mce_banks;
    u64 mmio_gva;
    unsigned int mmio_access;
    gfn_t mmio_gfn;
    u64 mmio_gen;
    struct kvm_pmu pmu;
    long unsigned int singlestep_rip;
    bool hyperv_enabled;
    struct kvm_vcpu_hv * hyperv;
    struct kvm_vcpu_xen xen;
    cpumask_var_t wbinvd_dirty_mask;
    long unsigned int last_retry_eip;
    long unsigned int last_retry_addr;
    struct (anon) apf;
    struct (anon) osvw;
    struct (anon) pv_eoi;
    u64 msr_kvm_poll_control;
    bool write_fault_to_shadow_pgtable;
    long unsigned int exit_qualification;
    struct (anon) pv;
    int pending_ioapic_eoi;
    int pending_external_vector;
    bool preempted_in_kernel;
    bool l1tf_flush_l1d;
    unsigned int last_vmentry_cpu;
    u64 msr_hwcr;
    struct (anon) pv_cpuid;
    bool guest_state_protected;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_arch {
    long unsigned int[17] regs;
    u32 regs_avail;
    u32 regs_dirty;
    long unsigned int cr0;
    long unsigned int cr0_guest_owned_bits;
    long unsigned int cr2;
    long unsigned int cr3;
    long unsigned int cr4;
    long unsigned int cr4_guest_owned_bits;
    long unsigned int cr4_guest_rsvd_bits;
    long unsigned int cr8;
    u32 host_pkru;
    u32 pkru;
    u32 hflags;
    u64 efer;
    u64 apic_base;
    struct kvm_lapic * apic;
    bool apicv_active;
    bool load_eoi_exitmap_pending;
    long unsigned int[4] ioapic_handled_vectors;
    long unsigned int apic_attention;
    int32_t apic_arb_prio;
    int mp_state;
    u64 ia32_misc_enable_msr;
    u64 smbase;
    u64 smi_count;
    bool tpr_access_reporting;
    bool xsaves_enabled;
    u64 ia32_xss;
    u64 microcode_version;
    u64 arch_capabilities;
    u64 perf_capabilities;
    struct kvm_mmu * mmu;
    struct kvm_mmu root_mmu;
    struct kvm_mmu guest_mmu;
    struct kvm_mmu nested_mmu;
    struct kvm_mmu * walk_mmu;
    struct kvm_mmu_memory_cache mmu_pte_list_desc_cache;
    struct kvm_mmu_memory_cache mmu_shadow_page_cache;
    struct kvm_mmu_memory_cache mmu_gfn_array_cache;
    struct kvm_mmu_memory_cache mmu_page_header_cache;
    struct fpu * user_fpu;
    struct fpu * guest_fpu;
    u64 xcr0;
    u64 guest_supported_xcr0;
    struct kvm_pio_request pio;
    void * pio_data;
    void * sev_pio_data;
    unsigned int sev_pio_count;
    u8 event_exit_inst_len;
    struct kvm_queued_exception exception;
    struct kvm_queued_interrupt interrupt;
    int halt_request;
    int cpuid_nent;
    struct kvm_cpuid_entry2 * cpuid_entries;
    u64 reserved_gpa_bits;
    int maxphyaddr;
    struct x86_emulate_ctxt * emulate_ctxt;
    bool emulate_regs_need_sync_to_vcpu;
    bool emulate_regs_need_sync_from_vcpu;
    int (*)(struct kvm_vcpu *) complete_userspace_io;
    gpa_t time;
    struct pvclock_vcpu_time_info hv_clock;
    unsigned int hw_tsc_khz;
    struct gfn_to_hva_cache pv_time;
    bool pv_time_enabled;
    bool pvclock_set_guest_stopped_request;
    struct (anon) st;
    u64 l1_tsc_offset;
    u64 tsc_offset;
    u64 last_guest_tsc;
    u64 last_host_tsc;
    u64 tsc_offset_adjustment;
    u64 this_tsc_nsec;
    u64 this_tsc_write;
    u64 this_tsc_generation;
    bool tsc_catchup;
    bool tsc_always_catchup;
    s8 virtual_tsc_shift;
    u32 virtual_tsc_mult;
    u32 virtual_tsc_khz;
    s64 ia32_tsc_adjust_msr;
    u64 msr_ia32_power_ctl;
    u64 l1_tsc_scaling_ratio;
    u64 tsc_scaling_ratio;
    atomic_t nmi_queued;
    unsigned int nmi_pending;
    bool nmi_injected;
    bool smi_pending;
    struct kvm_mtrr mtrr_state;
    u64 pat;
    unsigned int switch_db_regs;
    long unsigned int[4] db;
    long unsigned int dr6;
    long unsigned int dr7;
    long unsigned int[4] eff_db;
    long unsigned int guest_debug_dr7;
    u64 msr_platform_info;
    u64 msr_misc_features_enables;
    u64 mcg_cap;
    u64 mcg_status;
    u64 mcg_ctl;
    u64 mcg_ext_ctl;
    u64 * mce_banks;
    u64 mmio_gva;
    unsigned int mmio_access;
    gfn_t mmio_gfn;
    u64 mmio_gen;
    struct kvm_pmu pmu;
    long unsigned int singlestep_rip;
    bool hyperv_enabled;
    struct kvm_vcpu_hv * hyperv;
    struct kvm_vcpu_xen xen;
    cpumask_var_t wbinvd_dirty_mask;
    long unsigned int last_retry_eip;
    long unsigned int last_retry_addr;
    struct (anon) apf;
    struct (anon) osvw;
    struct (anon) pv_eoi;
    u64 msr_kvm_poll_control;
    bool write_fault_to_shadow_pgtable;
    long unsigned int exit_qualification;
    struct (anon) pv;
    int pending_ioapic_eoi;
    int pending_external_vector;
    bool preempted_in_kernel;
    bool l1tf_flush_l1d;
    int last_vmentry_cpu;
    u64 msr_hwcr;
    struct (anon) pv_cpuid;
    bool guest_state_protected;
    bool pdptrs_from_userspace;
    hpa_t hv_root_tdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_arch {
    long unsigned int[17] regs;
    u32 regs_avail;
    u32 regs_dirty;
    long unsigned int cr0;
    long unsigned int cr0_guest_owned_bits;
    long unsigned int cr2;
    long unsigned int cr3;
    long unsigned int cr4;
    long unsigned int cr4_guest_owned_bits;
    long unsigned int cr4_guest_rsvd_bits;
    long unsigned int cr8;
    u32 host_pkru;
    u32 pkru;
    u32 hflags;
    u64 efer;
    u64 apic_base;
    struct kvm_lapic * apic;
    bool apicv_active;
    bool load_eoi_exitmap_pending;
    long unsigned int[4] ioapic_handled_vectors;
    long unsigned int apic_attention;
    int32_t apic_arb_prio;
    int mp_state;
    u64 ia32_misc_enable_msr;
    u64 smbase;
    u64 smi_count;
    bool at_instruction_boundary;
    bool tpr_access_reporting;
    bool xsaves_enabled;
    bool xfd_no_write_intercept;
    u64 ia32_xss;
    u64 microcode_version;
    u64 arch_capabilities;
    u64 perf_capabilities;
    struct kvm_mmu * mmu;
    struct kvm_mmu root_mmu;
    struct kvm_mmu guest_mmu;
    struct kvm_mmu nested_mmu;
    struct kvm_mmu * walk_mmu;
    struct kvm_mmu_memory_cache mmu_pte_list_desc_cache;
    struct kvm_mmu_memory_cache mmu_shadow_page_cache;
    struct kvm_mmu_memory_cache mmu_gfn_array_cache;
    struct kvm_mmu_memory_cache mmu_page_header_cache;
    struct fpu_guest guest_fpu;
    u64 xcr0;
    struct kvm_pio_request pio;
    void * pio_data;
    void * sev_pio_data;
    unsigned int sev_pio_count;
    u8 event_exit_inst_len;
    struct kvm_queued_exception exception;
    struct kvm_queued_interrupt interrupt;
    int halt_request;
    int cpuid_nent;
    struct kvm_cpuid_entry2 * cpuid_entries;
    u32 kvm_cpuid_base;
    u64 reserved_gpa_bits;
    int maxphyaddr;
    struct x86_emulate_ctxt * emulate_ctxt;
    bool emulate_regs_need_sync_to_vcpu;
    bool emulate_regs_need_sync_from_vcpu;
    int (*)(struct kvm_vcpu *) complete_userspace_io;
    gpa_t time;
    struct pvclock_vcpu_time_info hv_clock;
    unsigned int hw_tsc_khz;
    struct gfn_to_pfn_cache pv_time;
    bool pvclock_set_guest_stopped_request;
    struct (anon) st;
    u64 l1_tsc_offset;
    u64 tsc_offset;
    u64 last_guest_tsc;
    u64 last_host_tsc;
    u64 tsc_offset_adjustment;
    u64 this_tsc_nsec;
    u64 this_tsc_write;
    u64 this_tsc_generation;
    bool tsc_catchup;
    bool tsc_always_catchup;
    s8 virtual_tsc_shift;
    u32 virtual_tsc_mult;
    u32 virtual_tsc_khz;
    s64 ia32_tsc_adjust_msr;
    u64 msr_ia32_power_ctl;
    u64 l1_tsc_scaling_ratio;
    u64 tsc_scaling_ratio;
    atomic_t nmi_queued;
    unsigned int nmi_pending;
    bool nmi_injected;
    bool smi_pending;
    u8 handling_intr_from_guest;
    struct kvm_mtrr mtrr_state;
    u64 pat;
    unsigned int switch_db_regs;
    long unsigned int[4] db;
    long unsigned int dr6;
    long unsigned int dr7;
    long unsigned int[4] eff_db;
    long unsigned int guest_debug_dr7;
    u64 msr_platform_info;
    u64 msr_misc_features_enables;
    u64 mcg_cap;
    u64 mcg_status;
    u64 mcg_ctl;
    u64 mcg_ext_ctl;
    u64 * mce_banks;
    u64 mmio_gva;
    unsigned int mmio_access;
    gfn_t mmio_gfn;
    u64 mmio_gen;
    struct kvm_pmu pmu;
    long unsigned int singlestep_rip;
    bool hyperv_enabled;
    struct kvm_vcpu_hv * hyperv;
    struct kvm_vcpu_xen xen;
    cpumask_var_t wbinvd_dirty_mask;
    long unsigned int last_retry_eip;
    long unsigned int last_retry_addr;
    struct (anon) apf;
    struct (anon) osvw;
    struct (anon) pv_eoi;
    u64 msr_kvm_poll_control;
    bool write_fault_to_shadow_pgtable;
    long unsigned int exit_qualification;
    struct (anon) pv;
    int pending_ioapic_eoi;
    int pending_external_vector;
    bool preempted_in_kernel;
    bool l1tf_flush_l1d;
    int last_vmentry_cpu;
    u64 msr_hwcr;
    struct (anon) pv_cpuid;
    bool guest_state_protected;
    bool pdptrs_from_userspace;
    hpa_t hv_root_tdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_arch {
    long unsigned int[17] regs;
    u32 regs_avail;
    u32 regs_dirty;
    long unsigned int cr0;
    long unsigned int cr0_guest_owned_bits;
    long unsigned int cr2;
    long unsigned int cr3;
    long unsigned int cr4;
    long unsigned int cr4_guest_owned_bits;
    long unsigned int cr4_guest_rsvd_bits;
    long unsigned int cr8;
    u32 host_pkru;
    u32 pkru;
    u32 hflags;
    u64 efer;
    u64 apic_base;
    struct kvm_lapic * apic;
    bool load_eoi_exitmap_pending;
    long unsigned int[4] ioapic_handled_vectors;
    long unsigned int apic_attention;
    int32_t apic_arb_prio;
    int mp_state;
    u64 ia32_misc_enable_msr;
    u64 smbase;
    u64 smi_count;
    bool at_instruction_boundary;
    bool tpr_access_reporting;
    bool xsaves_enabled;
    bool xfd_no_write_intercept;
    u64 ia32_xss;
    u64 microcode_version;
    u64 arch_capabilities;
    u64 perf_capabilities;
    struct kvm_mmu * mmu;
    struct kvm_mmu root_mmu;
    struct kvm_mmu guest_mmu;
    struct kvm_mmu nested_mmu;
    struct kvm_mmu * walk_mmu;
    struct kvm_mmu_memory_cache mmu_pte_list_desc_cache;
    struct kvm_mmu_memory_cache mmu_shadow_page_cache;
    struct kvm_mmu_memory_cache mmu_shadowed_info_cache;
    struct kvm_mmu_memory_cache mmu_page_header_cache;
    struct fpu_guest guest_fpu;
    u64 xcr0;
    u64 guest_supported_xcr0;
    struct kvm_pio_request pio;
    void * pio_data;
    void * sev_pio_data;
    unsigned int sev_pio_count;
    u8 event_exit_inst_len;
    bool exception_from_userspace;
    struct kvm_queued_exception exception;
    struct kvm_queued_exception exception_vmexit;
    struct kvm_queued_interrupt interrupt;
    int halt_request;
    int cpuid_nent;
    struct kvm_cpuid_entry2 * cpuid_entries;
    u32 kvm_cpuid_base;
    u64 reserved_gpa_bits;
    int maxphyaddr;
    struct x86_emulate_ctxt * emulate_ctxt;
    bool emulate_regs_need_sync_to_vcpu;
    bool emulate_regs_need_sync_from_vcpu;
    int (*)(struct kvm_vcpu *) complete_userspace_io;
    gpa_t time;
    struct pvclock_vcpu_time_info hv_clock;
    unsigned int hw_tsc_khz;
    struct gfn_to_pfn_cache pv_time;
    bool pvclock_set_guest_stopped_request;
    struct (anon) st;
    u64 l1_tsc_offset;
    u64 tsc_offset;
    u64 last_guest_tsc;
    u64 last_host_tsc;
    u64 tsc_offset_adjustment;
    u64 this_tsc_nsec;
    u64 this_tsc_write;
    u64 this_tsc_generation;
    bool tsc_catchup;
    bool tsc_always_catchup;
    s8 virtual_tsc_shift;
    u32 virtual_tsc_mult;
    u32 virtual_tsc_khz;
    s64 ia32_tsc_adjust_msr;
    u64 msr_ia32_power_ctl;
    u64 l1_tsc_scaling_ratio;
    u64 tsc_scaling_ratio;
    atomic_t nmi_queued;
    unsigned int nmi_pending;
    bool nmi_injected;
    bool smi_pending;
    u8 handling_intr_from_guest;
    struct kvm_mtrr mtrr_state;
    u64 pat;
    unsigned int switch_db_regs;
    long unsigned int[4] db;
    long unsigned int dr6;
    long unsigned int dr7;
    long unsigned int[4] eff_db;
    long unsigned int guest_debug_dr7;
    u64 msr_platform_info;
    u64 msr_misc_features_enables;
    u64 mcg_cap;
    u64 mcg_status;
    u64 mcg_ctl;
    u64 mcg_ext_ctl;
    u64 * mce_banks;
    u64 * mci_ctl2_banks;
    u64 mmio_gva;
    unsigned int mmio_access;
    gfn_t mmio_gfn;
    u64 mmio_gen;
    struct kvm_pmu pmu;
    long unsigned int singlestep_rip;
    bool hyperv_enabled;
    struct kvm_vcpu_hv * hyperv;
    struct kvm_vcpu_xen xen;
    cpumask_var_t wbinvd_dirty_mask;
    long unsigned int last_retry_eip;
    long unsigned int last_retry_addr;
    struct (anon) apf;
    struct (anon) osvw;
    struct (anon) pv_eoi;
    u64 msr_kvm_poll_control;
    bool write_fault_to_shadow_pgtable;
    long unsigned int exit_qualification;
    struct (anon) pv;
    int pending_ioapic_eoi;
    int pending_external_vector;
    bool preempted_in_kernel;
    bool l1tf_flush_l1d;
    int last_vmentry_cpu;
    u64 msr_hwcr;
    struct (anon) pv_cpuid;
    bool guest_state_protected;
    bool pdptrs_from_userspace;
    hpa_t hv_root_tdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_arch {
    long unsigned int[17] regs;
    u32 regs_avail;
    u32 regs_dirty;
    long unsigned int cr0;
    long unsigned int cr0_guest_owned_bits;
    long unsigned int cr2;
    long unsigned int cr3;
    long unsigned int cr4;
    long unsigned int cr4_guest_owned_bits;
    long unsigned int cr4_guest_rsvd_bits;
    long unsigned int cr8;
    u32 host_pkru;
    u32 pkru;
    u32 hflags;
    u64 efer;
    u64 apic_base;
    struct kvm_lapic * apic;
    bool load_eoi_exitmap_pending;
    long unsigned int[4] ioapic_handled_vectors;
    long unsigned int apic_attention;
    int32_t apic_arb_prio;
    int mp_state;
    u64 ia32_misc_enable_msr;
    u64 smbase;
    u64 smi_count;
    bool at_instruction_boundary;
    bool tpr_access_reporting;
    bool xsaves_enabled;
    bool xfd_no_write_intercept;
    u64 ia32_xss;
    u64 microcode_version;
    u64 arch_capabilities;
    u64 perf_capabilities;
    struct kvm_mmu * mmu;
    struct kvm_mmu root_mmu;
    struct kvm_mmu guest_mmu;
    struct kvm_mmu nested_mmu;
    struct kvm_mmu * walk_mmu;
    struct kvm_mmu_memory_cache mmu_pte_list_desc_cache;
    struct kvm_mmu_memory_cache mmu_shadow_page_cache;
    struct kvm_mmu_memory_cache mmu_shadowed_info_cache;
    struct kvm_mmu_memory_cache mmu_page_header_cache;
    struct fpu_guest guest_fpu;
    u64 xcr0;
    u64 guest_supported_xcr0;
    struct kvm_pio_request pio;
    void * pio_data;
    void * sev_pio_data;
    unsigned int sev_pio_count;
    u8 event_exit_inst_len;
    bool exception_from_userspace;
    struct kvm_queued_exception exception;
    struct kvm_queued_exception exception_vmexit;
    struct kvm_queued_interrupt interrupt;
    int halt_request;
    int cpuid_nent;
    struct kvm_cpuid_entry2 * cpuid_entries;
    struct kvm_hypervisor_cpuid kvm_cpuid;
    u64 reserved_gpa_bits;
    int maxphyaddr;
    struct x86_emulate_ctxt * emulate_ctxt;
    bool emulate_regs_need_sync_to_vcpu;
    bool emulate_regs_need_sync_from_vcpu;
    int (*)(struct kvm_vcpu *) complete_userspace_io;
    gpa_t time;
    struct pvclock_vcpu_time_info hv_clock;
    unsigned int hw_tsc_khz;
    struct gfn_to_pfn_cache pv_time;
    bool pvclock_set_guest_stopped_request;
    struct (anon) st;
    u64 l1_tsc_offset;
    u64 tsc_offset;
    u64 last_guest_tsc;
    u64 last_host_tsc;
    u64 tsc_offset_adjustment;
    u64 this_tsc_nsec;
    u64 this_tsc_write;
    u64 this_tsc_generation;
    bool tsc_catchup;
    bool tsc_always_catchup;
    s8 virtual_tsc_shift;
    u32 virtual_tsc_mult;
    u32 virtual_tsc_khz;
    s64 ia32_tsc_adjust_msr;
    u64 msr_ia32_power_ctl;
    u64 l1_tsc_scaling_ratio;
    u64 tsc_scaling_ratio;
    atomic_t nmi_queued;
    unsigned int nmi_pending;
    bool nmi_injected;
    bool smi_pending;
    u8 handling_intr_from_guest;
    struct kvm_mtrr mtrr_state;
    u64 pat;
    unsigned int switch_db_regs;
    long unsigned int[4] db;
    long unsigned int dr6;
    long unsigned int dr7;
    long unsigned int[4] eff_db;
    long unsigned int guest_debug_dr7;
    u64 msr_platform_info;
    u64 msr_misc_features_enables;
    u64 mcg_cap;
    u64 mcg_status;
    u64 mcg_ctl;
    u64 mcg_ext_ctl;
    u64 * mce_banks;
    u64 * mci_ctl2_banks;
    u64 mmio_gva;
    unsigned int mmio_access;
    gfn_t mmio_gfn;
    u64 mmio_gen;
    struct kvm_pmu pmu;
    long unsigned int singlestep_rip;
    bool hyperv_enabled;
    struct kvm_vcpu_hv * hyperv;
    struct kvm_vcpu_xen xen;
    cpumask_var_t wbinvd_dirty_mask;
    long unsigned int last_retry_eip;
    long unsigned int last_retry_addr;
    struct (anon) apf;
    struct (anon) osvw;
    struct (anon) pv_eoi;
    u64 msr_kvm_poll_control;
    long unsigned int exit_qualification;
    struct (anon) pv;
    int pending_ioapic_eoi;
    int pending_external_vector;
    bool preempted_in_kernel;
    bool l1tf_flush_l1d;
    int last_vmentry_cpu;
    u64 msr_hwcr;
    struct (anon) pv_cpuid;
    bool guest_state_protected;
    bool pdptrs_from_userspace;
    hpa_t hv_root_tdp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu_arch {
    long unsigned int[17] regs;
    u32 regs_avail;
    u32 regs_dirty;
    long unsigned int cr0;
    long unsigned int cr0_guest_owned_bits;
    long unsigned int cr2;
    long unsigned int cr3;
    long unsigned int cr4;
    long unsigned int cr4_guest_owned_bits;
    long unsigned int cr4_guest_rsvd_bits;
    long unsigned int cr8;
    u32 host_pkru;
    u32 pkru;
    u32 hflags;
    u64 efer;
    u64 apic_base;
    struct kvm_lapic * apic;
    bool load_eoi_exitmap_pending;
    long unsigned int[4] ioapic_handled_vectors;
    long unsigned int apic_attention;
    int32_t apic_arb_prio;
    int mp_state;
    u64 ia32_misc_enable_msr;
    u64 smbase;
    u64 smi_count;
    bool at_instruction_boundary;
    bool tpr_access_reporting;
    bool xfd_no_write_intercept;
    u64 ia32_xss;
    u64 microcode_version;
    u64 arch_capabilities;
    u64 perf_capabilities;
    struct kvm_mmu * mmu;
    struct kvm_mmu root_mmu;
    struct kvm_mmu guest_mmu;
    struct kvm_mmu nested_mmu;
    struct kvm_mmu * walk_mmu;
    struct kvm_mmu_memory_cache mmu_pte_list_desc_cache;
    struct kvm_mmu_memory_cache mmu_shadow_page_cache;
    struct kvm_mmu_memory_cache mmu_shadowed_info_cache;
    struct kvm_mmu_memory_cache mmu_page_header_cache;
    struct fpu_guest guest_fpu;
    u64 xcr0;
    u64 guest_supported_xcr0;
    struct kvm_pio_request pio;
    void * pio_data;
    void * sev_pio_data;
    unsigned int sev_pio_count;
    u8 event_exit_inst_len;
    bool exception_from_userspace;
    struct kvm_queued_exception exception;
    struct kvm_queued_exception exception_vmexit;
    struct kvm_queued_interrupt interrupt;
    int halt_request;
    int cpuid_nent;
    struct kvm_cpuid_entry2 * cpuid_entries;
    struct kvm_hypervisor_cpuid kvm_cpuid;
    struct (anon) governed_features;
    u64 reserved_gpa_bits;
    int maxphyaddr;
    struct x86_emulate_ctxt * emulate_ctxt;
    bool emulate_regs_need_sync_to_vcpu;
    bool emulate_regs_need_sync_from_vcpu;
    int (*)(struct kvm_vcpu *) complete_userspace_io;
    gpa_t time;
    struct pvclock_vcpu_time_info hv_clock;
    unsigned int hw_tsc_khz;
    struct gfn_to_pfn_cache pv_time;
    bool pvclock_set_guest_stopped_request;
    struct (anon) st;
    u64 l1_tsc_offset;
    u64 tsc_offset;
    u64 last_guest_tsc;
    u64 last_host_tsc;
    u64 tsc_offset_adjustment;
    u64 this_tsc_nsec;
    u64 this_tsc_write;
    u64 this_tsc_generation;
    bool tsc_catchup;
    bool tsc_always_catchup;
    s8 virtual_tsc_shift;
    u32 virtual_tsc_mult;
    u32 virtual_tsc_khz;
    s64 ia32_tsc_adjust_msr;
    u64 msr_ia32_power_ctl;
    u64 l1_tsc_scaling_ratio;
    u64 tsc_scaling_ratio;
    atomic_t nmi_queued;
    unsigned int nmi_pending;
    bool nmi_injected;
    bool smi_pending;
    u8 handling_intr_from_guest;
    struct kvm_mtrr mtrr_state;
    u64 pat;
    unsigned int switch_db_regs;
    long unsigned int[4] db;
    long unsigned int dr6;
    long unsigned int dr7;
    long unsigned int[4] eff_db;
    long unsigned int guest_debug_dr7;
    u64 msr_platform_info;
    u64 msr_misc_features_enables;
    u64 mcg_cap;
    u64 mcg_status;
    u64 mcg_ctl;
    u64 mcg_ext_ctl;
    u64 * mce_banks;
    u64 * mci_ctl2_banks;
    u64 mmio_gva;
    unsigned int mmio_access;
    gfn_t mmio_gfn;
    u64 mmio_gen;
    struct kvm_pmu pmu;
    long unsigned int singlestep_rip;
    bool hyperv_enabled;
    struct kvm_vcpu_hv * hyperv;
    struct kvm_vcpu_xen xen;
    cpumask_var_t wbinvd_dirty_mask;
    long unsigned int last_retry_eip;
    long unsigned int last_retry_addr;
    struct (anon) apf;
    struct (anon) osvw;
    struct (anon) pv_eoi;
    u64 msr_kvm_poll_control;
    long unsigned int exit_qualification;
    struct (anon) pv;
    int pending_ioapic_eoi;
    int pending_external_vector;
    bool preempted_in_kernel;
    bool l1tf_flush_l1d;
    int last_vmentry_cpu;
    u64 msr_hwcr;
    struct (anon) pv_cpuid;
    bool guest_state_protected;
    bool pdptrs_from_userspace;
    hpa_t hv_root_tdp;
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
struct kvm_vcpu_arch {
    struct kvm_cpu_context ctxt;
    void * sve_state;
    unsigned int sve_max_vl;
    u64 hcr_el2;
    u32 mdcr_el2;
    struct kvm_vcpu_fault_info fault;
    u64 workaround_flags;
    u64 flags;
    struct kvm_guest_debug_arch * debug_ptr;
    struct kvm_guest_debug_arch vcpu_debug_state;
    struct kvm_guest_debug_arch external_debug_state;
    struct kvm_cpu_context * host_cpu_context;
    struct thread_info * host_thread_info;
    struct user_fpsimd_state * host_fpsimd_state;
    struct (anon) host_debug_state;
    struct vgic_cpu vgic_cpu;
    struct arch_timer_cpu timer_cpu;
    struct kvm_pmu pmu;
    struct (anon) guest_debug_preserved;
    bool power_off;
    bool pause;
    struct kvm_decode mmio_decode;
    struct kvm_mmu_memory_cache mmu_page_cache;
    int target;
    long unsigned int[1] features;
    bool has_run_once;
    u64 vsesr_el2;
    struct vcpu_reset_state reset_state;
    bool sysregs_loaded_on_cpu;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kvm_vcpu_arch {
    ulong host_stack;
    u32 host_pid;
    struct kvmppc_slb[64] slb;
    int slb_max;
    int slb_nr;
    struct kvmppc_mmu mmu;
    struct kvmppc_vcpu_book3s * book3s;
    struct pt_regs regs;
    struct thread_fp_state fp;
    struct thread_vr_state vr;
    u32[32] qpr;
    ulong tar;
    ulong hflags;
    ulong guest_owned_ext;
    ulong purr;
    ulong spurr;
    ulong ic;
    ulong dscr;
    ulong amr;
    ulong uamor;
    ulong iamr;
    u32 ctrl;
    u32 dabrx;
    ulong dabr;
    ulong dawr;
    ulong dawrx;
    ulong ciabr;
    ulong cfar;
    ulong ppr;
    u32 pspb;
    ulong fscr;
    ulong shadow_fscr;
    ulong ebbhr;
    ulong ebbrr;
    ulong bescr;
    ulong csigr;
    ulong tacr;
    ulong tcscr;
    ulong acop;
    ulong wort;
    ulong tid;
    ulong psscr;
    ulong hfscr;
    ulong shadow_srr1;
    u32 vrsave;
    u32 mmucr;
    ulong shadow_msr;
    ulong csrr0;
    ulong csrr1;
    ulong dsrr0;
    ulong dsrr1;
    ulong mcsrr0;
    ulong mcsrr1;
    ulong mcsr;
    ulong dec;
    u64 entry_tb;
    u64 entry_vtb;
    u64 entry_ic;
    u32 tcr;
    ulong tsr;
    u32[64] ivor;
    ulong ivpr;
    u32 pvr;
    u32 shadow_pid;
    u32 shadow_pid1;
    u32 pid;
    u32 swap_pid;
    u32 ccr0;
    u32 ccr1;
    u32 dbsr;
    u64[5] mmcr;
    u32[8] pmc;
    u32[2] spmc;
    u64 siar;
    u64 sdar;
    u64 sier;
    u64 tfhar;
    u64 texasr;
    u64 tfiar;
    u64 orig_texasr;
    u32 cr_tm;
    u64 xer_tm;
    u64 lr_tm;
    u64 ctr_tm;
    u64 amr_tm;
    u64 ppr_tm;
    u64 dscr_tm;
    u64 tar_tm;
    ulong[32] gpr_tm;
    struct thread_fp_state fp_tm;
    struct thread_vr_state vr_tm;
    u32 vrsave_tm;
    ulong fault_dar;
    u32 fault_dsisr;
    long unsigned int intr_msr;
    ulong fault_gpa;
    gpa_t paddr_accessed;
    gva_t vaddr_accessed;
    pgd_t * pgdir;
    u16 io_gpr;
    u8 mmio_host_swabbed;
    u8 mmio_sign_extend;
    u8 mmio_sp64_extend;
    u8 mmio_vsx_copy_nums;
    u8 mmio_vsx_offset;
    u8 mmio_vmx_copy_nums;
    u8 mmio_vmx_offset;
    u8 mmio_copy_type;
    u8 osi_needed;
    u8 osi_enabled;
    u8 papr_enabled;
    u8 watchdog_enabled;
    u8 sane;
    u8 cpu_type;
    u8 hcall_needed;
    u8 epr_flags;
    u8 epr_needed;
    u8 external_oneshot;
    u32 cpr0_cfgaddr;
    struct hrtimer dec_timer;
    u64 dec_jiffies;
    u64 dec_expires;
    long unsigned int pending_exceptions;
    u8 ceded;
    u8 prodded;
    u8 doorbell_request;
    u8 irq_pending;
    u32 last_inst;
    struct swait_queue_head * wqp;
    struct kvmppc_vcore * vcore;
    int ret;
    int trap;
    int state;
    int ptid;
    int thread_cpu;
    int prev_cpu;
    bool timer_running;
    wait_queue_head_t cpu_run;
    struct machine_check_event mce_evt;
    struct kvm_vcpu_arch_shared * shared;
    bool shared_big_endian;
    long unsigned int magic_page_pa;
    long unsigned int magic_page_ea;
    bool disable_kernel_nx;
    int irq_type;
    int irq_cpu_id;
    struct openpic * mpic;
    struct kvmppc_icp * icp;
    struct kvmppc_xive_vcpu * xive_vcpu;
    __be32 xive_cam_word;
    u8 xive_pushed;
    u8 xive_esc_on;
    union xive_tma_w01 xive_saved_state;
    u64 xive_esc_raddr;
    u64 xive_esc_vaddr;
    struct kvm_vcpu_arch_shared shregs;
    struct mmio_hpte_cache mmio_cache;
    long unsigned int pgfault_addr;
    long int pgfault_index;
    long unsigned int[2] pgfault_hpte;
    struct mmio_hpte_cache_entry * pgfault_cache;
    struct task_struct * run_task;
    struct kvm_run * kvm_run;
    spinlock_t vpa_update_lock;
    struct kvmppc_vpa vpa;
    struct kvmppc_vpa dtl;
    struct dtl_entry * dtl_ptr;
    long unsigned int dtl_index;
    u64 stolen_logged;
    struct kvmppc_vpa slb_shadow;
    spinlock_t tbacct_lock;
    u64 busy_stolen;
    u64 busy_preempt;
    u32 emul_inst;
    u32 online;
    struct kvm_nested_guest * nested;
    u32 nested_vcpu_id;
    gpa_t nested_io_gpr;
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct kvm_vcpu_arch {
    long unsigned int[17] regs;
    u32 regs_avail;
    u32 regs_dirty;
    long unsigned int cr0;
    long unsigned int cr0_guest_owned_bits;
    long unsigned int cr2;
    long unsigned int cr3;
    long unsigned int cr4;
    long unsigned int cr4_guest_owned_bits;
    long unsigned int cr4_guest_rsvd_bits;
    long unsigned int cr8;
    u32 host_pkru;
    u32 pkru;
    u32 hflags;
    u64 efer;
    u64 apic_base;
    struct kvm_lapic * apic;
    bool apicv_active;
    bool load_eoi_exitmap_pending;
    long unsigned int[4] ioapic_handled_vectors;
    long unsigned int apic_attention;
    int32_t apic_arb_prio;
    int mp_state;
    u64 ia32_misc_enable_msr;
    u64 smbase;
    u64 smi_count;
    bool tpr_access_reporting;
    bool xsaves_enabled;
    u64 ia32_xss;
    u64 microcode_version;
    u64 arch_capabilities;
    u64 perf_capabilities;
    struct kvm_mmu * mmu;
    struct kvm_mmu root_mmu;
    struct kvm_mmu guest_mmu;
    struct kvm_mmu nested_mmu;
    struct kvm_mmu * walk_mmu;
    struct kvm_mmu_memory_cache mmu_pte_list_desc_cache;
    struct kvm_mmu_memory_cache mmu_shadow_page_cache;
    struct kvm_mmu_memory_cache mmu_gfn_array_cache;
    struct kvm_mmu_memory_cache mmu_page_header_cache;
    struct fpu * user_fpu;
    struct fpu * guest_fpu;
    u64 xcr0;
    u64 guest_supported_xcr0;
    struct kvm_pio_request pio;
    void * pio_data;
    void * guest_ins_data;
    u8 event_exit_inst_len;
    struct kvm_queued_exception exception;
    struct kvm_queued_interrupt interrupt;
    int halt_request;
    int cpuid_nent;
    struct kvm_cpuid_entry2 * cpuid_entries;
    long unsigned int cr3_lm_rsvd_bits;
    int maxphyaddr;
    int max_tdp_level;
    struct x86_emulate_ctxt * emulate_ctxt;
    bool emulate_regs_need_sync_to_vcpu;
    bool emulate_regs_need_sync_from_vcpu;
    int (*)(struct kvm_vcpu *) complete_userspace_io;
    gpa_t time;
    struct pvclock_vcpu_time_info hv_clock;
    unsigned int hw_tsc_khz;
    struct gfn_to_hva_cache pv_time;
    bool pv_time_enabled;
    bool pvclock_set_guest_stopped_request;
    struct (anon) st;
    u64 l1_tsc_offset;
    u64 tsc_offset;
    u64 last_guest_tsc;
    u64 last_host_tsc;
    u64 tsc_offset_adjustment;
    u64 this_tsc_nsec;
    u64 this_tsc_write;
    u64 this_tsc_generation;
    bool tsc_catchup;
    bool tsc_always_catchup;
    s8 virtual_tsc_shift;
    u32 virtual_tsc_mult;
    u32 virtual_tsc_khz;
    s64 ia32_tsc_adjust_msr;
    u64 msr_ia32_power_ctl;
    u64 tsc_scaling_ratio;
    atomic_t nmi_queued;
    unsigned int nmi_pending;
    bool nmi_injected;
    bool smi_pending;
    struct kvm_mtrr mtrr_state;
    u64 pat;
    unsigned int switch_db_regs;
    long unsigned int[4] db;
    long unsigned int dr6;
    long unsigned int dr7;
    long unsigned int[4] eff_db;
    long unsigned int guest_debug_dr7;
    u64 msr_platform_info;
    u64 msr_misc_features_enables;
    u64 mcg_cap;
    u64 mcg_status;
    u64 mcg_ctl;
    u64 mcg_ext_ctl;
    u64 * mce_banks;
    u64 mmio_gva;
    unsigned int mmio_access;
    gfn_t mmio_gfn;
    u64 mmio_gen;
    struct kvm_pmu pmu;
    long unsigned int singlestep_rip;
    struct kvm_vcpu_hv hyperv;
    cpumask_var_t wbinvd_dirty_mask;
    long unsigned int last_retry_eip;
    long unsigned int last_retry_addr;
    struct (anon) apf;
    struct (anon) osvw;
    struct (anon) pv_eoi;
    u64 msr_kvm_poll_control;
    bool write_fault_to_shadow_pgtable;
    long unsigned int exit_qualification;
    struct (anon) pv;
    int pending_ioapic_eoi;
    int pending_external_vector;
    bool preempted_in_kernel;
    bool l1tf_flush_l1d;
    unsigned int last_vmentry_cpu;
    u64 msr_hwcr;
    struct (anon) pv_cpuid;
    bool guest_state_protected;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 reserved_gpa_bits</code>
</li>
<li>
<b>Field added. </b>
<code>bool hyperv_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>struct kvm_vcpu_xen xen</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int cr3_lm_rsvd_bits</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct kvm_vcpu_hv hyperv</code> ➡️ <code>struct kvm_vcpu_hv * hyperv</code>
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
<code>void * sev_pio_data</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int sev_pio_count</code>
</li>
<li>
<b>Field added. </b>
<code>u64 l1_tsc_scaling_ratio</code>
</li>
<li>
<b>Field added. </b>
<code>bool pdptrs_from_userspace</code>
</li>
<li>
<b>Field added. </b>
<code>hpa_t hv_root_tdp</code>
</li>
<li>
<b>Field removed. </b>
<code>void * guest_ins_data</code>
</li>
<li>
<b>Field removed. </b>
<code>int max_tdp_level</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int last_vmentry_cpu</code> ➡️ <code>int last_vmentry_cpu</code>
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
<code>bool at_instruction_boundary</code>
</li>
<li>
<b>Field added. </b>
<code>bool xfd_no_write_intercept</code>
</li>
<li>
<b>Field added. </b>
<code>u32 kvm_cpuid_base</code>
</li>
<li>
<b>Field added. </b>
<code>u8 handling_intr_from_guest</code>
</li>
<li>
<b>Field removed. </b>
<code>struct fpu * user_fpu</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 guest_supported_xcr0</code>
</li>
<li>
<b>Field removed. </b>
<code>bool pv_time_enabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fpu * guest_fpu</code> ➡️ <code>struct fpu_guest guest_fpu</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct gfn_to_hva_cache pv_time</code> ➡️ <code>struct gfn_to_pfn_cache pv_time</code>
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
<code>struct kvm_mmu_memory_cache mmu_shadowed_info_cache</code>
</li>
<li>
<b>Field added. </b>
<code>u64 guest_supported_xcr0</code>
</li>
<li>
<b>Field added. </b>
<code>bool exception_from_userspace</code>
</li>
<li>
<b>Field added. </b>
<code>struct kvm_queued_exception exception_vmexit</code>
</li>
<li>
<b>Field added. </b>
<code>u64 * mci_ctl2_banks</code>
</li>
<li>
<b>Field removed. </b>
<code>bool apicv_active</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kvm_mmu_memory_cache mmu_gfn_array_cache</code>
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
<code>struct kvm_hypervisor_cpuid kvm_cpuid</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 kvm_cpuid_base</code>
</li>
<li>
<b>Field removed. </b>
<code>bool write_fault_to_shadow_pgtable</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) governed_features</code>
</li>
<li>
<b>Field removed. </b>
<code>bool xsaves_enabled</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct kvm_vcpu_arch {
    struct kvm_cpu_context ctxt;
    void * sve_state;
    unsigned int sve_max_vl;
    u64 hcr_el2;
    u32 mdcr_el2;
    struct kvm_vcpu_fault_info fault;
    u64 workaround_flags;
    u64 flags;
    struct kvm_guest_debug_arch * debug_ptr;
    struct kvm_guest_debug_arch vcpu_debug_state;
    struct kvm_guest_debug_arch external_debug_state;
    struct kvm_cpu_context * host_cpu_context;
    struct thread_info * host_thread_info;
    struct user_fpsimd_state * host_fpsimd_state;
    struct (anon) host_debug_state;
    struct vgic_cpu vgic_cpu;
    struct arch_timer_cpu timer_cpu;
    struct kvm_pmu pmu;
    struct (anon) guest_debug_preserved;
    bool power_off;
    bool pause;
    struct kvm_decode mmio_decode;
    struct kvm_mmu_memory_cache mmu_page_cache;
    int target;
    long unsigned int[1] features;
    bool has_run_once;
    u64 vsesr_el2;
    struct vcpu_reset_state reset_state;
    bool sysregs_loaded_on_cpu;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvm_vcpu_arch {
    ulong host_stack;
    u32 host_pid;
    struct kvmppc_slb[64] slb;
    int slb_max;
    int slb_nr;
    struct kvmppc_mmu mmu;
    struct kvmppc_vcpu_book3s * book3s;
    struct pt_regs regs;
    struct thread_fp_state fp;
    struct thread_vr_state vr;
    u32[32] qpr;
    ulong tar;
    ulong hflags;
    ulong guest_owned_ext;
    ulong purr;
    ulong spurr;
    ulong ic;
    ulong dscr;
    ulong amr;
    ulong uamor;
    ulong iamr;
    u32 ctrl;
    u32 dabrx;
    ulong dabr;
    ulong dawr;
    ulong dawrx;
    ulong ciabr;
    ulong cfar;
    ulong ppr;
    u32 pspb;
    ulong fscr;
    ulong shadow_fscr;
    ulong ebbhr;
    ulong ebbrr;
    ulong bescr;
    ulong csigr;
    ulong tacr;
    ulong tcscr;
    ulong acop;
    ulong wort;
    ulong tid;
    ulong psscr;
    ulong hfscr;
    ulong shadow_srr1;
    u32 vrsave;
    u32 mmucr;
    ulong shadow_msr;
    ulong csrr0;
    ulong csrr1;
    ulong dsrr0;
    ulong dsrr1;
    ulong mcsrr0;
    ulong mcsrr1;
    ulong mcsr;
    ulong dec;
    u64 entry_tb;
    u64 entry_vtb;
    u64 entry_ic;
    u32 tcr;
    ulong tsr;
    u32[64] ivor;
    ulong ivpr;
    u32 pvr;
    u32 shadow_pid;
    u32 shadow_pid1;
    u32 pid;
    u32 swap_pid;
    u32 ccr0;
    u32 ccr1;
    u32 dbsr;
    u64[5] mmcr;
    u32[8] pmc;
    u32[2] spmc;
    u64 siar;
    u64 sdar;
    u64 sier;
    u64 tfhar;
    u64 texasr;
    u64 tfiar;
    u64 orig_texasr;
    u32 cr_tm;
    u64 xer_tm;
    u64 lr_tm;
    u64 ctr_tm;
    u64 amr_tm;
    u64 ppr_tm;
    u64 dscr_tm;
    u64 tar_tm;
    ulong[32] gpr_tm;
    struct thread_fp_state fp_tm;
    struct thread_vr_state vr_tm;
    u32 vrsave_tm;
    ulong fault_dar;
    u32 fault_dsisr;
    long unsigned int intr_msr;
    ulong fault_gpa;
    gpa_t paddr_accessed;
    gva_t vaddr_accessed;
    pgd_t * pgdir;
    u16 io_gpr;
    u8 mmio_host_swabbed;
    u8 mmio_sign_extend;
    u8 mmio_sp64_extend;
    u8 mmio_vsx_copy_nums;
    u8 mmio_vsx_offset;
    u8 mmio_vmx_copy_nums;
    u8 mmio_vmx_offset;
    u8 mmio_copy_type;
    u8 osi_needed;
    u8 osi_enabled;
    u8 papr_enabled;
    u8 watchdog_enabled;
    u8 sane;
    u8 cpu_type;
    u8 hcall_needed;
    u8 epr_flags;
    u8 epr_needed;
    u8 external_oneshot;
    u32 cpr0_cfgaddr;
    struct hrtimer dec_timer;
    u64 dec_jiffies;
    u64 dec_expires;
    long unsigned int pending_exceptions;
    u8 ceded;
    u8 prodded;
    u8 doorbell_request;
    u8 irq_pending;
    u32 last_inst;
    struct swait_queue_head * wqp;
    struct kvmppc_vcore * vcore;
    int ret;
    int trap;
    int state;
    int ptid;
    int thread_cpu;
    int prev_cpu;
    bool timer_running;
    wait_queue_head_t cpu_run;
    struct machine_check_event mce_evt;
    struct kvm_vcpu_arch_shared * shared;
    bool shared_big_endian;
    long unsigned int magic_page_pa;
    long unsigned int magic_page_ea;
    bool disable_kernel_nx;
    int irq_type;
    int irq_cpu_id;
    struct openpic * mpic;
    struct kvmppc_icp * icp;
    struct kvmppc_xive_vcpu * xive_vcpu;
    __be32 xive_cam_word;
    u8 xive_pushed;
    u8 xive_esc_on;
    union xive_tma_w01 xive_saved_state;
    u64 xive_esc_raddr;
    u64 xive_esc_vaddr;
    struct kvm_vcpu_arch_shared shregs;
    struct mmio_hpte_cache mmio_cache;
    long unsigned int pgfault_addr;
    long int pgfault_index;
    long unsigned int[2] pgfault_hpte;
    struct mmio_hpte_cache_entry * pgfault_cache;
    struct task_struct * run_task;
    struct kvm_run * kvm_run;
    spinlock_t vpa_update_lock;
    struct kvmppc_vpa vpa;
    struct kvmppc_vpa dtl;
    struct dtl_entry * dtl_ptr;
    long unsigned int dtl_index;
    u64 stolen_logged;
    struct kvmppc_vpa slb_shadow;
    spinlock_t tbacct_lock;
    u64 busy_stolen;
    u64 busy_preempt;
    u32 emul_inst;
    u32 online;
    struct kvm_nested_guest * nested;
    u32 nested_vcpu_id;
    gpa_t nested_io_gpr;
}
```
</details>
</li>
</ul>
