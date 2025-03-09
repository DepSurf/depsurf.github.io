# Struct: <code>kvm_x86_ops</code>

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
struct kvm_x86_ops {
    int (*)() hardware_enable;
    void (*)() hardware_disable;
    void (*)() hardware_unsetup;
    bool (*)() cpu_has_accelerated_tpr;
    bool (*)(struct kvm *, u32) has_emulated_msr;
    void (*)(struct kvm_vcpu *) vcpu_after_set_cpuid;
    unsigned int vm_size;
    int (*)(struct kvm *) vm_init;
    void (*)(struct kvm *) vm_destroy;
    int (*)(struct kvm_vcpu *) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    void (*)(struct kvm_vcpu *, bool) vcpu_reset;
    void (*)(struct kvm_vcpu *) prepare_guest_switch;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *) update_exception_bitmap;
    int (*)(struct kvm_vcpu *, struct msr_data *) get_msr;
    int (*)(struct kvm_vcpu *, struct msr_data *) set_msr;
    u64 (*)(struct kvm_vcpu *, int) get_segment_base;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) get_segment;
    int (*)(struct kvm_vcpu *) get_cpl;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) set_segment;
    void (*)(struct kvm_vcpu *, int *, int *) get_cs_db_l_bits;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr0;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr4;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr4;
    int (*)(struct kvm_vcpu *, u64) set_efer;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_gdt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_gdt;
    void (*)(struct kvm_vcpu *) sync_dirty_debug_regs;
    void (*)(struct kvm_vcpu *, long unsigned int) set_dr7;
    void (*)(struct kvm_vcpu *, enum kvm_reg) cache_reg;
    long unsigned int (*)(struct kvm_vcpu *) get_rflags;
    void (*)(struct kvm_vcpu *, long unsigned int) set_rflags;
    void (*)(struct kvm_vcpu *) tlb_flush_all;
    void (*)(struct kvm_vcpu *) tlb_flush_current;
    int (*)(struct kvm *) tlb_remote_flush;
    int (*)(struct kvm *, struct kvm_tlb_range *) tlb_remote_flush_with_range;
    void (*)(struct kvm_vcpu *, gva_t) tlb_flush_gva;
    void (*)(struct kvm_vcpu *) tlb_flush_guest;
    enum exit_fastpath_completion (*)(struct kvm_vcpu *) run;
    int (*)(struct kvm_vcpu *, enum exit_fastpath_completion) handle_exit;
    int (*)(struct kvm_vcpu *) skip_emulated_instruction;
    void (*)(struct kvm_vcpu *) update_emulated_instruction;
    void (*)(struct kvm_vcpu *, int) set_interrupt_shadow;
    u32 (*)(struct kvm_vcpu *) get_interrupt_shadow;
    void (*)(struct kvm_vcpu *, unsigned char *) patch_hypercall;
    void (*)(struct kvm_vcpu *) set_irq;
    void (*)(struct kvm_vcpu *) set_nmi;
    void (*)(struct kvm_vcpu *) queue_exception;
    void (*)(struct kvm_vcpu *) cancel_injection;
    int (*)(struct kvm_vcpu *, bool) interrupt_allowed;
    int (*)(struct kvm_vcpu *, bool) nmi_allowed;
    bool (*)(struct kvm_vcpu *) get_nmi_mask;
    void (*)(struct kvm_vcpu *, bool) set_nmi_mask;
    void (*)(struct kvm_vcpu *) enable_nmi_window;
    void (*)(struct kvm_vcpu *) enable_irq_window;
    void (*)(struct kvm_vcpu *, int, int) update_cr8_intercept;
    bool (*)(ulong) check_apicv_inhibit_reasons;
    void (*)(struct kvm *, bool) pre_update_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *) refresh_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *, int) hwapic_irr_update;
    void (*)(struct kvm_vcpu *, int) hwapic_isr_update;
    bool (*)(struct kvm_vcpu *) guest_apic_has_interrupt;
    void (*)(struct kvm_vcpu *, u64 *) load_eoi_exitmap;
    void (*)(struct kvm_vcpu *) set_virtual_apic_mode;
    void (*)(struct kvm_vcpu *) set_apic_access_page_addr;
    int (*)(struct kvm_vcpu *, int) deliver_posted_interrupt;
    int (*)(struct kvm_vcpu *) sync_pir_to_irr;
    int (*)(struct kvm *, unsigned int) set_tss_addr;
    int (*)(struct kvm *, u64) set_identity_map_addr;
    u64 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask;
    void (*)(struct kvm_vcpu *, hpa_t, int) load_mmu_pgd;
    bool (*)() has_wbinvd_exit;
    u64 (*)(struct kvm_vcpu *, u64) write_l1_tsc_offset;
    void (*)(struct kvm_vcpu *, u64 *, u64 *, u32 *, u32 *) get_exit_info;
    int (*)(struct kvm_vcpu *, struct x86_instruction_info *, enum x86_intercept_stage, struct x86_exception *) check_intercept;
    void (*)(struct kvm_vcpu *) handle_exit_irqoff;
    void (*)(struct kvm_vcpu *) request_immediate_exit;
    void (*)(struct kvm_vcpu *, int) sched_in;
    int cpu_dirty_log_size;
    void (*)(struct kvm_vcpu *) update_cpu_dirty_logging;
    const struct kvm_pmu_ops * pmu_ops;
    const struct kvm_x86_nested_ops * nested_ops;
    int (*)(struct kvm_vcpu *) pre_block;
    void (*)(struct kvm_vcpu *) post_block;
    void (*)(struct kvm_vcpu *) vcpu_blocking;
    void (*)(struct kvm_vcpu *) vcpu_unblocking;
    int (*)(struct kvm *, unsigned int, uint32_t, bool) update_pi_irte;
    void (*)(struct kvm *) start_assignment;
    void (*)(struct kvm_vcpu *) apicv_post_state_restore;
    bool (*)(struct kvm_vcpu *) dy_apicv_has_pending_interrupt;
    int (*)(struct kvm_vcpu *, u64, bool *) set_hv_timer;
    void (*)(struct kvm_vcpu *) cancel_hv_timer;
    void (*)(struct kvm_vcpu *) setup_mce;
    int (*)(struct kvm_vcpu *, bool) smi_allowed;
    int (*)(struct kvm_vcpu *, char *) pre_enter_smm;
    int (*)(struct kvm_vcpu *, const char *) pre_leave_smm;
    void (*)(struct kvm_vcpu *) enable_smi_window;
    int (*)(struct kvm *, void *) mem_enc_op;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_reg_region;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unreg_region;
    int (*)(struct kvm *, unsigned int) vm_copy_enc_context_from;
    int (*)(struct kvm_msr_entry *) get_msr_feature;
    bool (*)(struct kvm_vcpu *, void *, int) can_emulate_instruction;
    bool (*)(struct kvm_vcpu *) apic_init_signal_blocked;
    int (*)(struct kvm_vcpu *) enable_direct_tlbflush;
    void (*)(struct kvm_vcpu *) migrate_timers;
    void (*)(struct kvm_vcpu *) msr_filter_changed;
    int (*)(struct kvm_vcpu *, int) complete_emulated_msr;
    void (*)(struct kvm_vcpu *, u8) vcpu_deliver_sipi_vector;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_ops {
    int (*)() hardware_enable;
    void (*)() hardware_disable;
    void (*)() hardware_unsetup;
    bool (*)() cpu_has_accelerated_tpr;
    bool (*)(struct kvm *, u32) has_emulated_msr;
    void (*)(struct kvm_vcpu *) vcpu_after_set_cpuid;
    unsigned int vm_size;
    int (*)(struct kvm *) vm_init;
    void (*)(struct kvm *) vm_destroy;
    int (*)(struct kvm_vcpu *) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    void (*)(struct kvm_vcpu *, bool) vcpu_reset;
    void (*)(struct kvm_vcpu *) prepare_guest_switch;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *) update_exception_bitmap;
    int (*)(struct kvm_vcpu *, struct msr_data *) get_msr;
    int (*)(struct kvm_vcpu *, struct msr_data *) set_msr;
    u64 (*)(struct kvm_vcpu *, int) get_segment_base;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) get_segment;
    int (*)(struct kvm_vcpu *) get_cpl;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) set_segment;
    void (*)(struct kvm_vcpu *, int *, int *) get_cs_db_l_bits;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr0;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr4;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr4;
    int (*)(struct kvm_vcpu *, u64) set_efer;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_gdt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_gdt;
    void (*)(struct kvm_vcpu *) sync_dirty_debug_regs;
    void (*)(struct kvm_vcpu *, long unsigned int) set_dr7;
    void (*)(struct kvm_vcpu *, enum kvm_reg) cache_reg;
    long unsigned int (*)(struct kvm_vcpu *) get_rflags;
    void (*)(struct kvm_vcpu *, long unsigned int) set_rflags;
    bool (*)(struct kvm_vcpu *) get_if_flag;
    void (*)(struct kvm_vcpu *) tlb_flush_all;
    void (*)(struct kvm_vcpu *) tlb_flush_current;
    int (*)(struct kvm *) tlb_remote_flush;
    int (*)(struct kvm *, struct kvm_tlb_range *) tlb_remote_flush_with_range;
    void (*)(struct kvm_vcpu *, gva_t) tlb_flush_gva;
    void (*)(struct kvm_vcpu *) tlb_flush_guest;
    enum exit_fastpath_completion (*)(struct kvm_vcpu *) run;
    int (*)(struct kvm_vcpu *, enum exit_fastpath_completion) handle_exit;
    int (*)(struct kvm_vcpu *) skip_emulated_instruction;
    void (*)(struct kvm_vcpu *) update_emulated_instruction;
    void (*)(struct kvm_vcpu *, int) set_interrupt_shadow;
    u32 (*)(struct kvm_vcpu *) get_interrupt_shadow;
    void (*)(struct kvm_vcpu *, unsigned char *) patch_hypercall;
    void (*)(struct kvm_vcpu *) set_irq;
    void (*)(struct kvm_vcpu *) set_nmi;
    void (*)(struct kvm_vcpu *) queue_exception;
    void (*)(struct kvm_vcpu *) cancel_injection;
    int (*)(struct kvm_vcpu *, bool) interrupt_allowed;
    int (*)(struct kvm_vcpu *, bool) nmi_allowed;
    bool (*)(struct kvm_vcpu *) get_nmi_mask;
    void (*)(struct kvm_vcpu *, bool) set_nmi_mask;
    void (*)(struct kvm_vcpu *) enable_nmi_window;
    void (*)(struct kvm_vcpu *) enable_irq_window;
    void (*)(struct kvm_vcpu *, int, int) update_cr8_intercept;
    bool (*)(ulong) check_apicv_inhibit_reasons;
    void (*)(struct kvm_vcpu *) refresh_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *, int) hwapic_irr_update;
    void (*)(struct kvm_vcpu *, int) hwapic_isr_update;
    bool (*)(struct kvm_vcpu *) guest_apic_has_interrupt;
    void (*)(struct kvm_vcpu *, u64 *) load_eoi_exitmap;
    void (*)(struct kvm_vcpu *) set_virtual_apic_mode;
    void (*)(struct kvm_vcpu *) set_apic_access_page_addr;
    int (*)(struct kvm_vcpu *, int) deliver_posted_interrupt;
    int (*)(struct kvm_vcpu *) sync_pir_to_irr;
    int (*)(struct kvm *, unsigned int) set_tss_addr;
    int (*)(struct kvm *, u64) set_identity_map_addr;
    u64 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask;
    void (*)(struct kvm_vcpu *, hpa_t, int) load_mmu_pgd;
    bool (*)() has_wbinvd_exit;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_offset;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u64) write_tsc_offset;
    void (*)(struct kvm_vcpu *, u64) write_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u64 *, u64 *, u32 *, u32 *) get_exit_info;
    int (*)(struct kvm_vcpu *, struct x86_instruction_info *, enum x86_intercept_stage, struct x86_exception *) check_intercept;
    void (*)(struct kvm_vcpu *) handle_exit_irqoff;
    void (*)(struct kvm_vcpu *) request_immediate_exit;
    void (*)(struct kvm_vcpu *, int) sched_in;
    int cpu_dirty_log_size;
    void (*)(struct kvm_vcpu *) update_cpu_dirty_logging;
    const struct kvm_pmu_ops * pmu_ops;
    const struct kvm_x86_nested_ops * nested_ops;
    int (*)(struct kvm_vcpu *) pre_block;
    void (*)(struct kvm_vcpu *) post_block;
    void (*)(struct kvm_vcpu *) vcpu_blocking;
    void (*)(struct kvm_vcpu *) vcpu_unblocking;
    int (*)(struct kvm *, unsigned int, uint32_t, bool) update_pi_irte;
    void (*)(struct kvm *) start_assignment;
    void (*)(struct kvm_vcpu *) apicv_post_state_restore;
    bool (*)(struct kvm_vcpu *) dy_apicv_has_pending_interrupt;
    int (*)(struct kvm_vcpu *, u64, bool *) set_hv_timer;
    void (*)(struct kvm_vcpu *) cancel_hv_timer;
    void (*)(struct kvm_vcpu *) setup_mce;
    int (*)(struct kvm_vcpu *, bool) smi_allowed;
    int (*)(struct kvm_vcpu *, char *) enter_smm;
    int (*)(struct kvm_vcpu *, const char *) leave_smm;
    void (*)(struct kvm_vcpu *) enable_smi_window;
    int (*)(struct kvm *, void *) mem_enc_op;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_reg_region;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unreg_region;
    int (*)(struct kvm *, unsigned int) vm_copy_enc_context_from;
    int (*)(struct kvm_msr_entry *) get_msr_feature;
    bool (*)(struct kvm_vcpu *, void *, int) can_emulate_instruction;
    bool (*)(struct kvm_vcpu *) apic_init_signal_blocked;
    int (*)(struct kvm_vcpu *) enable_direct_tlbflush;
    void (*)(struct kvm_vcpu *) migrate_timers;
    void (*)(struct kvm_vcpu *) msr_filter_changed;
    int (*)(struct kvm_vcpu *, int) complete_emulated_msr;
    void (*)(struct kvm_vcpu *, u8) vcpu_deliver_sipi_vector;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_ops {
    const char * name;
    int (*)() hardware_enable;
    void (*)() hardware_disable;
    void (*)() hardware_unsetup;
    bool (*)(struct kvm *, u32) has_emulated_msr;
    void (*)(struct kvm_vcpu *) vcpu_after_set_cpuid;
    unsigned int vm_size;
    int (*)(struct kvm *) vm_init;
    void (*)(struct kvm *) vm_destroy;
    int (*)(struct kvm_vcpu *) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    void (*)(struct kvm_vcpu *, bool) vcpu_reset;
    void (*)(struct kvm_vcpu *) prepare_switch_to_guest;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *) update_exception_bitmap;
    int (*)(struct kvm_vcpu *, struct msr_data *) get_msr;
    int (*)(struct kvm_vcpu *, struct msr_data *) set_msr;
    u64 (*)(struct kvm_vcpu *, int) get_segment_base;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) get_segment;
    int (*)(struct kvm_vcpu *) get_cpl;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) set_segment;
    void (*)(struct kvm_vcpu *, int *, int *) get_cs_db_l_bits;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr0;
    void (*)(struct kvm_vcpu *, long unsigned int) post_set_cr3;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr4;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr4;
    int (*)(struct kvm_vcpu *, u64) set_efer;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_gdt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_gdt;
    void (*)(struct kvm_vcpu *) sync_dirty_debug_regs;
    void (*)(struct kvm_vcpu *, long unsigned int) set_dr7;
    void (*)(struct kvm_vcpu *, enum kvm_reg) cache_reg;
    long unsigned int (*)(struct kvm_vcpu *) get_rflags;
    void (*)(struct kvm_vcpu *, long unsigned int) set_rflags;
    bool (*)(struct kvm_vcpu *) get_if_flag;
    void (*)(struct kvm_vcpu *) flush_tlb_all;
    void (*)(struct kvm_vcpu *) flush_tlb_current;
    int (*)(struct kvm *) tlb_remote_flush;
    int (*)(struct kvm *, struct kvm_tlb_range *) tlb_remote_flush_with_range;
    void (*)(struct kvm_vcpu *, gva_t) flush_tlb_gva;
    void (*)(struct kvm_vcpu *) flush_tlb_guest;
    int (*)(struct kvm_vcpu *) vcpu_pre_run;
    enum exit_fastpath_completion (*)(struct kvm_vcpu *) vcpu_run;
    int (*)(struct kvm_vcpu *, enum exit_fastpath_completion) handle_exit;
    int (*)(struct kvm_vcpu *) skip_emulated_instruction;
    void (*)(struct kvm_vcpu *) update_emulated_instruction;
    void (*)(struct kvm_vcpu *, int) set_interrupt_shadow;
    u32 (*)(struct kvm_vcpu *) get_interrupt_shadow;
    void (*)(struct kvm_vcpu *, unsigned char *) patch_hypercall;
    void (*)(struct kvm_vcpu *) inject_irq;
    void (*)(struct kvm_vcpu *) inject_nmi;
    void (*)(struct kvm_vcpu *) queue_exception;
    void (*)(struct kvm_vcpu *) cancel_injection;
    int (*)(struct kvm_vcpu *, bool) interrupt_allowed;
    int (*)(struct kvm_vcpu *, bool) nmi_allowed;
    bool (*)(struct kvm_vcpu *) get_nmi_mask;
    void (*)(struct kvm_vcpu *, bool) set_nmi_mask;
    void (*)(struct kvm_vcpu *) enable_nmi_window;
    void (*)(struct kvm_vcpu *) enable_irq_window;
    void (*)(struct kvm_vcpu *, int, int) update_cr8_intercept;
    bool (*)(enum kvm_apicv_inhibit) check_apicv_inhibit_reasons;
    void (*)(struct kvm_vcpu *) refresh_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *, int) hwapic_irr_update;
    void (*)(struct kvm_vcpu *, int) hwapic_isr_update;
    bool (*)(struct kvm_vcpu *) guest_apic_has_interrupt;
    void (*)(struct kvm_vcpu *, u64 *) load_eoi_exitmap;
    void (*)(struct kvm_vcpu *) set_virtual_apic_mode;
    void (*)(struct kvm_vcpu *) set_apic_access_page_addr;
    void (*)(struct kvm_lapic *, int, int, int) deliver_interrupt;
    int (*)(struct kvm_vcpu *) sync_pir_to_irr;
    int (*)(struct kvm *, unsigned int) set_tss_addr;
    int (*)(struct kvm *, u64) set_identity_map_addr;
    u64 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask;
    void (*)(struct kvm_vcpu *, hpa_t, int) load_mmu_pgd;
    bool (*)() has_wbinvd_exit;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_offset;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u64) write_tsc_offset;
    void (*)(struct kvm_vcpu *, u64) write_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u32 *, u64 *, u64 *, u32 *, u32 *) get_exit_info;
    int (*)(struct kvm_vcpu *, struct x86_instruction_info *, enum x86_intercept_stage, struct x86_exception *) check_intercept;
    void (*)(struct kvm_vcpu *) handle_exit_irqoff;
    void (*)(struct kvm_vcpu *) request_immediate_exit;
    void (*)(struct kvm_vcpu *, int) sched_in;
    int cpu_dirty_log_size;
    void (*)(struct kvm_vcpu *) update_cpu_dirty_logging;
    const struct kvm_x86_nested_ops * nested_ops;
    void (*)(struct kvm_vcpu *) vcpu_blocking;
    void (*)(struct kvm_vcpu *) vcpu_unblocking;
    int (*)(struct kvm *, unsigned int, uint32_t, bool) pi_update_irte;
    void (*)(struct kvm *) pi_start_assignment;
    void (*)(struct kvm_vcpu *) apicv_post_state_restore;
    bool (*)(struct kvm_vcpu *) dy_apicv_has_pending_interrupt;
    int (*)(struct kvm_vcpu *, u64, bool *) set_hv_timer;
    void (*)(struct kvm_vcpu *) cancel_hv_timer;
    void (*)(struct kvm_vcpu *) setup_mce;
    int (*)(struct kvm_vcpu *, bool) smi_allowed;
    int (*)(struct kvm_vcpu *, char *) enter_smm;
    int (*)(struct kvm_vcpu *, const char *) leave_smm;
    void (*)(struct kvm_vcpu *) enable_smi_window;
    int (*)(struct kvm *, void *) mem_enc_ioctl;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_register_region;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unregister_region;
    int (*)(struct kvm *, unsigned int) vm_copy_enc_context_from;
    int (*)(struct kvm *, unsigned int) vm_move_enc_context_from;
    void (*)(struct kvm *) guest_memory_reclaimed;
    int (*)(struct kvm_msr_entry *) get_msr_feature;
    bool (*)(struct kvm_vcpu *, int, void *, int) can_emulate_instruction;
    bool (*)(struct kvm_vcpu *) apic_init_signal_blocked;
    int (*)(struct kvm_vcpu *) enable_direct_tlbflush;
    void (*)(struct kvm_vcpu *) migrate_timers;
    void (*)(struct kvm_vcpu *) msr_filter_changed;
    int (*)(struct kvm_vcpu *, int) complete_emulated_msr;
    void (*)(struct kvm_vcpu *, u8) vcpu_deliver_sipi_vector;
    long unsigned int (*)(struct kvm_vcpu *) vcpu_get_apicv_inhibit_reasons;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_ops {
    const char * name;
    int (*)() hardware_enable;
    void (*)() hardware_disable;
    void (*)() hardware_unsetup;
    bool (*)(struct kvm *, u32) has_emulated_msr;
    void (*)(struct kvm_vcpu *) vcpu_after_set_cpuid;
    unsigned int vm_size;
    int (*)(struct kvm *) vm_init;
    void (*)(struct kvm *) vm_destroy;
    int (*)(struct kvm *) vcpu_precreate;
    int (*)(struct kvm_vcpu *) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    void (*)(struct kvm_vcpu *, bool) vcpu_reset;
    void (*)(struct kvm_vcpu *) prepare_switch_to_guest;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *) update_exception_bitmap;
    int (*)(struct kvm_vcpu *, struct msr_data *) get_msr;
    int (*)(struct kvm_vcpu *, struct msr_data *) set_msr;
    u64 (*)(struct kvm_vcpu *, int) get_segment_base;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) get_segment;
    int (*)(struct kvm_vcpu *) get_cpl;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) set_segment;
    void (*)(struct kvm_vcpu *, int *, int *) get_cs_db_l_bits;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr0;
    void (*)(struct kvm_vcpu *, long unsigned int) post_set_cr3;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr4;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr4;
    int (*)(struct kvm_vcpu *, u64) set_efer;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_gdt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_gdt;
    void (*)(struct kvm_vcpu *) sync_dirty_debug_regs;
    void (*)(struct kvm_vcpu *, long unsigned int) set_dr7;
    void (*)(struct kvm_vcpu *, enum kvm_reg) cache_reg;
    long unsigned int (*)(struct kvm_vcpu *) get_rflags;
    void (*)(struct kvm_vcpu *, long unsigned int) set_rflags;
    bool (*)(struct kvm_vcpu *) get_if_flag;
    void (*)(struct kvm_vcpu *) flush_tlb_all;
    void (*)(struct kvm_vcpu *) flush_tlb_current;
    int (*)(struct kvm *) tlb_remote_flush;
    int (*)(struct kvm *, struct kvm_tlb_range *) tlb_remote_flush_with_range;
    void (*)(struct kvm_vcpu *, gva_t) flush_tlb_gva;
    void (*)(struct kvm_vcpu *) flush_tlb_guest;
    int (*)(struct kvm_vcpu *) vcpu_pre_run;
    enum exit_fastpath_completion (*)(struct kvm_vcpu *) vcpu_run;
    int (*)(struct kvm_vcpu *, enum exit_fastpath_completion) handle_exit;
    int (*)(struct kvm_vcpu *) skip_emulated_instruction;
    void (*)(struct kvm_vcpu *) update_emulated_instruction;
    void (*)(struct kvm_vcpu *, int) set_interrupt_shadow;
    u32 (*)(struct kvm_vcpu *) get_interrupt_shadow;
    void (*)(struct kvm_vcpu *, unsigned char *) patch_hypercall;
    void (*)(struct kvm_vcpu *, bool) inject_irq;
    void (*)(struct kvm_vcpu *) inject_nmi;
    void (*)(struct kvm_vcpu *) inject_exception;
    void (*)(struct kvm_vcpu *) cancel_injection;
    int (*)(struct kvm_vcpu *, bool) interrupt_allowed;
    int (*)(struct kvm_vcpu *, bool) nmi_allowed;
    bool (*)(struct kvm_vcpu *) get_nmi_mask;
    void (*)(struct kvm_vcpu *, bool) set_nmi_mask;
    void (*)(struct kvm_vcpu *) enable_nmi_window;
    void (*)(struct kvm_vcpu *) enable_irq_window;
    void (*)(struct kvm_vcpu *, int, int) update_cr8_intercept;
    bool (*)(enum kvm_apicv_inhibit) check_apicv_inhibit_reasons;
    void (*)(struct kvm_vcpu *) refresh_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *, int) hwapic_irr_update;
    void (*)(int) hwapic_isr_update;
    bool (*)(struct kvm_vcpu *) guest_apic_has_interrupt;
    void (*)(struct kvm_vcpu *, u64 *) load_eoi_exitmap;
    void (*)(struct kvm_vcpu *) set_virtual_apic_mode;
    void (*)(struct kvm_vcpu *) set_apic_access_page_addr;
    void (*)(struct kvm_lapic *, int, int, int) deliver_interrupt;
    int (*)(struct kvm_vcpu *) sync_pir_to_irr;
    int (*)(struct kvm *, unsigned int) set_tss_addr;
    int (*)(struct kvm *, u64) set_identity_map_addr;
    u8 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask;
    void (*)(struct kvm_vcpu *, hpa_t, int) load_mmu_pgd;
    bool (*)() has_wbinvd_exit;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_offset;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u64) write_tsc_offset;
    void (*)(struct kvm_vcpu *, u64) write_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u32 *, u64 *, u64 *, u32 *, u32 *) get_exit_info;
    int (*)(struct kvm_vcpu *, struct x86_instruction_info *, enum x86_intercept_stage, struct x86_exception *) check_intercept;
    void (*)(struct kvm_vcpu *) handle_exit_irqoff;
    void (*)(struct kvm_vcpu *) request_immediate_exit;
    void (*)(struct kvm_vcpu *, int) sched_in;
    int cpu_dirty_log_size;
    void (*)(struct kvm_vcpu *) update_cpu_dirty_logging;
    const struct kvm_x86_nested_ops * nested_ops;
    void (*)(struct kvm_vcpu *) vcpu_blocking;
    void (*)(struct kvm_vcpu *) vcpu_unblocking;
    int (*)(struct kvm *, unsigned int, uint32_t, bool) pi_update_irte;
    void (*)(struct kvm *) pi_start_assignment;
    void (*)(struct kvm_vcpu *) apicv_post_state_restore;
    bool (*)(struct kvm_vcpu *) dy_apicv_has_pending_interrupt;
    int (*)(struct kvm_vcpu *, u64, bool *) set_hv_timer;
    void (*)(struct kvm_vcpu *) cancel_hv_timer;
    void (*)(struct kvm_vcpu *) setup_mce;
    int (*)(struct kvm_vcpu *, bool) smi_allowed;
    int (*)(struct kvm_vcpu *, union kvm_smram *) enter_smm;
    int (*)(struct kvm_vcpu *, const union kvm_smram *) leave_smm;
    void (*)(struct kvm_vcpu *) enable_smi_window;
    int (*)(struct kvm *, void *) mem_enc_ioctl;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_register_region;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unregister_region;
    int (*)(struct kvm *, unsigned int) vm_copy_enc_context_from;
    int (*)(struct kvm *, unsigned int) vm_move_enc_context_from;
    void (*)(struct kvm *) guest_memory_reclaimed;
    int (*)(struct kvm_msr_entry *) get_msr_feature;
    bool (*)(struct kvm_vcpu *, int, void *, int) can_emulate_instruction;
    bool (*)(struct kvm_vcpu *) apic_init_signal_blocked;
    int (*)(struct kvm_vcpu *) enable_l2_tlb_flush;
    void (*)(struct kvm_vcpu *) migrate_timers;
    void (*)(struct kvm_vcpu *) msr_filter_changed;
    int (*)(struct kvm_vcpu *, int) complete_emulated_msr;
    void (*)(struct kvm_vcpu *, u8) vcpu_deliver_sipi_vector;
    long unsigned int (*)(struct kvm_vcpu *) vcpu_get_apicv_inhibit_reasons;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_ops {
    const char * name;
    int (*)() check_processor_compatibility;
    int (*)() hardware_enable;
    void (*)() hardware_disable;
    void (*)() hardware_unsetup;
    bool (*)(struct kvm *, u32) has_emulated_msr;
    void (*)(struct kvm_vcpu *) vcpu_after_set_cpuid;
    unsigned int vm_size;
    int (*)(struct kvm *) vm_init;
    void (*)(struct kvm *) vm_destroy;
    int (*)(struct kvm *) vcpu_precreate;
    int (*)(struct kvm_vcpu *) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    void (*)(struct kvm_vcpu *, bool) vcpu_reset;
    void (*)(struct kvm_vcpu *) prepare_switch_to_guest;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *) update_exception_bitmap;
    int (*)(struct kvm_vcpu *, struct msr_data *) get_msr;
    int (*)(struct kvm_vcpu *, struct msr_data *) set_msr;
    u64 (*)(struct kvm_vcpu *, int) get_segment_base;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) get_segment;
    int (*)(struct kvm_vcpu *) get_cpl;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) set_segment;
    void (*)(struct kvm_vcpu *, int *, int *) get_cs_db_l_bits;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr0;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr0;
    void (*)(struct kvm_vcpu *, long unsigned int) post_set_cr3;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr4;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr4;
    int (*)(struct kvm_vcpu *, u64) set_efer;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_gdt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_gdt;
    void (*)(struct kvm_vcpu *) sync_dirty_debug_regs;
    void (*)(struct kvm_vcpu *, long unsigned int) set_dr7;
    void (*)(struct kvm_vcpu *, enum kvm_reg) cache_reg;
    long unsigned int (*)(struct kvm_vcpu *) get_rflags;
    void (*)(struct kvm_vcpu *, long unsigned int) set_rflags;
    bool (*)(struct kvm_vcpu *) get_if_flag;
    void (*)(struct kvm_vcpu *) flush_tlb_all;
    void (*)(struct kvm_vcpu *) flush_tlb_current;
    int (*)(struct kvm *) flush_remote_tlbs;
    int (*)(struct kvm *, gfn_t, gfn_t) flush_remote_tlbs_range;
    void (*)(struct kvm_vcpu *, gva_t) flush_tlb_gva;
    void (*)(struct kvm_vcpu *) flush_tlb_guest;
    int (*)(struct kvm_vcpu *) vcpu_pre_run;
    enum exit_fastpath_completion (*)(struct kvm_vcpu *) vcpu_run;
    int (*)(struct kvm_vcpu *, enum exit_fastpath_completion) handle_exit;
    int (*)(struct kvm_vcpu *) skip_emulated_instruction;
    void (*)(struct kvm_vcpu *) update_emulated_instruction;
    void (*)(struct kvm_vcpu *, int) set_interrupt_shadow;
    u32 (*)(struct kvm_vcpu *) get_interrupt_shadow;
    void (*)(struct kvm_vcpu *, unsigned char *) patch_hypercall;
    void (*)(struct kvm_vcpu *, bool) inject_irq;
    void (*)(struct kvm_vcpu *) inject_nmi;
    void (*)(struct kvm_vcpu *) inject_exception;
    void (*)(struct kvm_vcpu *) cancel_injection;
    int (*)(struct kvm_vcpu *, bool) interrupt_allowed;
    int (*)(struct kvm_vcpu *, bool) nmi_allowed;
    bool (*)(struct kvm_vcpu *) get_nmi_mask;
    void (*)(struct kvm_vcpu *, bool) set_nmi_mask;
    bool (*)(struct kvm_vcpu *) is_vnmi_pending;
    bool (*)(struct kvm_vcpu *) set_vnmi_pending;
    void (*)(struct kvm_vcpu *) enable_nmi_window;
    void (*)(struct kvm_vcpu *) enable_irq_window;
    void (*)(struct kvm_vcpu *, int, int) update_cr8_intercept;
    bool (*)(enum kvm_apicv_inhibit) check_apicv_inhibit_reasons;
    const long unsigned int required_apicv_inhibits;
    bool allow_apicv_in_x2apic_without_x2apic_virtualization;
    void (*)(struct kvm_vcpu *) refresh_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *, int) hwapic_irr_update;
    void (*)(int) hwapic_isr_update;
    bool (*)(struct kvm_vcpu *) guest_apic_has_interrupt;
    void (*)(struct kvm_vcpu *, u64 *) load_eoi_exitmap;
    void (*)(struct kvm_vcpu *) set_virtual_apic_mode;
    void (*)(struct kvm_vcpu *) set_apic_access_page_addr;
    void (*)(struct kvm_lapic *, int, int, int) deliver_interrupt;
    int (*)(struct kvm_vcpu *) sync_pir_to_irr;
    int (*)(struct kvm *, unsigned int) set_tss_addr;
    int (*)(struct kvm *, u64) set_identity_map_addr;
    u8 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask;
    void (*)(struct kvm_vcpu *, hpa_t, int) load_mmu_pgd;
    bool (*)() has_wbinvd_exit;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_offset;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u64) write_tsc_offset;
    void (*)(struct kvm_vcpu *, u64) write_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u32 *, u64 *, u64 *, u32 *, u32 *) get_exit_info;
    int (*)(struct kvm_vcpu *, struct x86_instruction_info *, enum x86_intercept_stage, struct x86_exception *) check_intercept;
    void (*)(struct kvm_vcpu *) handle_exit_irqoff;
    void (*)(struct kvm_vcpu *) request_immediate_exit;
    void (*)(struct kvm_vcpu *, int) sched_in;
    int cpu_dirty_log_size;
    void (*)(struct kvm_vcpu *) update_cpu_dirty_logging;
    const struct kvm_x86_nested_ops * nested_ops;
    void (*)(struct kvm_vcpu *) vcpu_blocking;
    void (*)(struct kvm_vcpu *) vcpu_unblocking;
    int (*)(struct kvm *, unsigned int, uint32_t, bool) pi_update_irte;
    void (*)(struct kvm *) pi_start_assignment;
    void (*)(struct kvm_vcpu *) apicv_post_state_restore;
    bool (*)(struct kvm_vcpu *) dy_apicv_has_pending_interrupt;
    int (*)(struct kvm_vcpu *, u64, bool *) set_hv_timer;
    void (*)(struct kvm_vcpu *) cancel_hv_timer;
    void (*)(struct kvm_vcpu *) setup_mce;
    int (*)(struct kvm_vcpu *, bool) smi_allowed;
    int (*)(struct kvm_vcpu *, union kvm_smram *) enter_smm;
    int (*)(struct kvm_vcpu *, const union kvm_smram *) leave_smm;
    void (*)(struct kvm_vcpu *) enable_smi_window;
    int (*)(struct kvm *, void *) mem_enc_ioctl;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_register_region;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unregister_region;
    int (*)(struct kvm *, unsigned int) vm_copy_enc_context_from;
    int (*)(struct kvm *, unsigned int) vm_move_enc_context_from;
    void (*)(struct kvm *) guest_memory_reclaimed;
    int (*)(struct kvm_msr_entry *) get_msr_feature;
    bool (*)(struct kvm_vcpu *, int, void *, int) can_emulate_instruction;
    bool (*)(struct kvm_vcpu *) apic_init_signal_blocked;
    int (*)(struct kvm_vcpu *) enable_l2_tlb_flush;
    void (*)(struct kvm_vcpu *) migrate_timers;
    void (*)(struct kvm_vcpu *) msr_filter_changed;
    int (*)(struct kvm_vcpu *, int) complete_emulated_msr;
    void (*)(struct kvm_vcpu *, u8) vcpu_deliver_sipi_vector;
    long unsigned int (*)(struct kvm_vcpu *) vcpu_get_apicv_inhibit_reasons;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_x86_ops {
    const char * name;
    int (*)() check_processor_compatibility;
    int (*)() hardware_enable;
    void (*)() hardware_disable;
    void (*)() hardware_unsetup;
    bool (*)(struct kvm *, u32) has_emulated_msr;
    void (*)(struct kvm_vcpu *) vcpu_after_set_cpuid;
    unsigned int vm_size;
    int (*)(struct kvm *) vm_init;
    void (*)(struct kvm *) vm_destroy;
    int (*)(struct kvm *) vcpu_precreate;
    int (*)(struct kvm_vcpu *) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    void (*)(struct kvm_vcpu *, bool) vcpu_reset;
    void (*)(struct kvm_vcpu *) prepare_switch_to_guest;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *) update_exception_bitmap;
    int (*)(struct kvm_vcpu *, struct msr_data *) get_msr;
    int (*)(struct kvm_vcpu *, struct msr_data *) set_msr;
    u64 (*)(struct kvm_vcpu *, int) get_segment_base;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) get_segment;
    int (*)(struct kvm_vcpu *) get_cpl;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) set_segment;
    void (*)(struct kvm_vcpu *, int *, int *) get_cs_db_l_bits;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr0;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr0;
    void (*)(struct kvm_vcpu *, long unsigned int) post_set_cr3;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr4;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr4;
    int (*)(struct kvm_vcpu *, u64) set_efer;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_gdt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_gdt;
    void (*)(struct kvm_vcpu *) sync_dirty_debug_regs;
    void (*)(struct kvm_vcpu *, long unsigned int) set_dr7;
    void (*)(struct kvm_vcpu *, enum kvm_reg) cache_reg;
    long unsigned int (*)(struct kvm_vcpu *) get_rflags;
    void (*)(struct kvm_vcpu *, long unsigned int) set_rflags;
    bool (*)(struct kvm_vcpu *) get_if_flag;
    void (*)(struct kvm_vcpu *) flush_tlb_all;
    void (*)(struct kvm_vcpu *) flush_tlb_current;
    int (*)(struct kvm *) flush_remote_tlbs;
    int (*)(struct kvm *, gfn_t, gfn_t) flush_remote_tlbs_range;
    void (*)(struct kvm_vcpu *, gva_t) flush_tlb_gva;
    void (*)(struct kvm_vcpu *) flush_tlb_guest;
    int (*)(struct kvm_vcpu *) vcpu_pre_run;
    enum exit_fastpath_completion (*)(struct kvm_vcpu *) vcpu_run;
    int (*)(struct kvm_vcpu *, enum exit_fastpath_completion) handle_exit;
    int (*)(struct kvm_vcpu *) skip_emulated_instruction;
    void (*)(struct kvm_vcpu *) update_emulated_instruction;
    void (*)(struct kvm_vcpu *, int) set_interrupt_shadow;
    u32 (*)(struct kvm_vcpu *) get_interrupt_shadow;
    void (*)(struct kvm_vcpu *, unsigned char *) patch_hypercall;
    void (*)(struct kvm_vcpu *, bool) inject_irq;
    void (*)(struct kvm_vcpu *) inject_nmi;
    void (*)(struct kvm_vcpu *) inject_exception;
    void (*)(struct kvm_vcpu *) cancel_injection;
    int (*)(struct kvm_vcpu *, bool) interrupt_allowed;
    int (*)(struct kvm_vcpu *, bool) nmi_allowed;
    bool (*)(struct kvm_vcpu *) get_nmi_mask;
    void (*)(struct kvm_vcpu *, bool) set_nmi_mask;
    bool (*)(struct kvm_vcpu *) is_vnmi_pending;
    bool (*)(struct kvm_vcpu *) set_vnmi_pending;
    void (*)(struct kvm_vcpu *) enable_nmi_window;
    void (*)(struct kvm_vcpu *) enable_irq_window;
    void (*)(struct kvm_vcpu *, int, int) update_cr8_intercept;
    bool (*)(enum kvm_apicv_inhibit) check_apicv_inhibit_reasons;
    const long unsigned int required_apicv_inhibits;
    bool allow_apicv_in_x2apic_without_x2apic_virtualization;
    void (*)(struct kvm_vcpu *) refresh_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *, int) hwapic_irr_update;
    void (*)(int) hwapic_isr_update;
    bool (*)(struct kvm_vcpu *) guest_apic_has_interrupt;
    void (*)(struct kvm_vcpu *, u64 *) load_eoi_exitmap;
    void (*)(struct kvm_vcpu *) set_virtual_apic_mode;
    void (*)(struct kvm_vcpu *) set_apic_access_page_addr;
    void (*)(struct kvm_lapic *, int, int, int) deliver_interrupt;
    int (*)(struct kvm_vcpu *) sync_pir_to_irr;
    int (*)(struct kvm *, unsigned int) set_tss_addr;
    int (*)(struct kvm *, u64) set_identity_map_addr;
    u8 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask;
    void (*)(struct kvm_vcpu *, hpa_t, int) load_mmu_pgd;
    bool (*)() has_wbinvd_exit;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_offset;
    u64 (*)(struct kvm_vcpu *) get_l2_tsc_multiplier;
    void (*)(struct kvm_vcpu *) write_tsc_offset;
    void (*)(struct kvm_vcpu *) write_tsc_multiplier;
    void (*)(struct kvm_vcpu *, u32 *, u64 *, u64 *, u32 *, u32 *) get_exit_info;
    int (*)(struct kvm_vcpu *, struct x86_instruction_info *, enum x86_intercept_stage, struct x86_exception *) check_intercept;
    void (*)(struct kvm_vcpu *) handle_exit_irqoff;
    void (*)(struct kvm_vcpu *) request_immediate_exit;
    void (*)(struct kvm_vcpu *, int) sched_in;
    int cpu_dirty_log_size;
    void (*)(struct kvm_vcpu *) update_cpu_dirty_logging;
    const struct kvm_x86_nested_ops * nested_ops;
    void (*)(struct kvm_vcpu *) vcpu_blocking;
    void (*)(struct kvm_vcpu *) vcpu_unblocking;
    int (*)(struct kvm *, unsigned int, uint32_t, bool) pi_update_irte;
    void (*)(struct kvm *) pi_start_assignment;
    void (*)(struct kvm_vcpu *) apicv_pre_state_restore;
    void (*)(struct kvm_vcpu *) apicv_post_state_restore;
    bool (*)(struct kvm_vcpu *) dy_apicv_has_pending_interrupt;
    int (*)(struct kvm_vcpu *, u64, bool *) set_hv_timer;
    void (*)(struct kvm_vcpu *) cancel_hv_timer;
    void (*)(struct kvm_vcpu *) setup_mce;
    int (*)(struct kvm_vcpu *, bool) smi_allowed;
    int (*)(struct kvm_vcpu *, union kvm_smram *) enter_smm;
    int (*)(struct kvm_vcpu *, const union kvm_smram *) leave_smm;
    void (*)(struct kvm_vcpu *) enable_smi_window;
    int (*)(struct kvm *, void *) mem_enc_ioctl;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_register_region;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unregister_region;
    int (*)(struct kvm *, unsigned int) vm_copy_enc_context_from;
    int (*)(struct kvm *, unsigned int) vm_move_enc_context_from;
    void (*)(struct kvm *) guest_memory_reclaimed;
    int (*)(struct kvm_msr_entry *) get_msr_feature;
    int (*)(struct kvm_vcpu *, int, void *, int) check_emulate_instruction;
    bool (*)(struct kvm_vcpu *) apic_init_signal_blocked;
    int (*)(struct kvm_vcpu *) enable_l2_tlb_flush;
    void (*)(struct kvm_vcpu *) migrate_timers;
    void (*)(struct kvm_vcpu *) msr_filter_changed;
    int (*)(struct kvm_vcpu *, int) complete_emulated_msr;
    void (*)(struct kvm_vcpu *, u8) vcpu_deliver_sipi_vector;
    long unsigned int (*)(struct kvm_vcpu *) vcpu_get_apicv_inhibit_reasons;
    gva_t (*)(struct kvm_vcpu *, gva_t, unsigned int) get_untagged_addr;
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
struct kvm_x86_ops {
    int (*)() hardware_enable;
    void (*)() hardware_disable;
    void (*)() hardware_unsetup;
    bool (*)() cpu_has_accelerated_tpr;
    bool (*)(struct kvm *, u32) has_emulated_msr;
    void (*)(struct kvm_vcpu *) vcpu_after_set_cpuid;
    unsigned int vm_size;
    int (*)(struct kvm *) vm_init;
    void (*)(struct kvm *) vm_destroy;
    int (*)(struct kvm_vcpu *) vcpu_create;
    void (*)(struct kvm_vcpu *) vcpu_free;
    void (*)(struct kvm_vcpu *, bool) vcpu_reset;
    void (*)(struct kvm_vcpu *) prepare_guest_switch;
    void (*)(struct kvm_vcpu *, int) vcpu_load;
    void (*)(struct kvm_vcpu *) vcpu_put;
    void (*)(struct kvm_vcpu *) update_exception_bitmap;
    int (*)(struct kvm_vcpu *, struct msr_data *) get_msr;
    int (*)(struct kvm_vcpu *, struct msr_data *) set_msr;
    u64 (*)(struct kvm_vcpu *, int) get_segment_base;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) get_segment;
    int (*)(struct kvm_vcpu *) get_cpl;
    void (*)(struct kvm_vcpu *, struct kvm_segment *, int) set_segment;
    void (*)(struct kvm_vcpu *, int *, int *) get_cs_db_l_bits;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr0;
    bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr4;
    void (*)(struct kvm_vcpu *, long unsigned int) set_cr4;
    int (*)(struct kvm_vcpu *, u64) set_efer;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_idt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) get_gdt;
    void (*)(struct kvm_vcpu *, struct desc_ptr *) set_gdt;
    void (*)(struct kvm_vcpu *) sync_dirty_debug_regs;
    void (*)(struct kvm_vcpu *, long unsigned int) set_dr7;
    void (*)(struct kvm_vcpu *, enum kvm_reg) cache_reg;
    long unsigned int (*)(struct kvm_vcpu *) get_rflags;
    void (*)(struct kvm_vcpu *, long unsigned int) set_rflags;
    void (*)(struct kvm_vcpu *) tlb_flush_all;
    void (*)(struct kvm_vcpu *) tlb_flush_current;
    int (*)(struct kvm *) tlb_remote_flush;
    int (*)(struct kvm *, struct kvm_tlb_range *) tlb_remote_flush_with_range;
    void (*)(struct kvm_vcpu *, gva_t) tlb_flush_gva;
    void (*)(struct kvm_vcpu *) tlb_flush_guest;
    enum exit_fastpath_completion (*)(struct kvm_vcpu *) run;
    int (*)(struct kvm_vcpu *, enum exit_fastpath_completion) handle_exit;
    int (*)(struct kvm_vcpu *) skip_emulated_instruction;
    void (*)(struct kvm_vcpu *) update_emulated_instruction;
    void (*)(struct kvm_vcpu *, int) set_interrupt_shadow;
    u32 (*)(struct kvm_vcpu *) get_interrupt_shadow;
    void (*)(struct kvm_vcpu *, unsigned char *) patch_hypercall;
    void (*)(struct kvm_vcpu *) set_irq;
    void (*)(struct kvm_vcpu *) set_nmi;
    void (*)(struct kvm_vcpu *) queue_exception;
    void (*)(struct kvm_vcpu *) cancel_injection;
    int (*)(struct kvm_vcpu *, bool) interrupt_allowed;
    int (*)(struct kvm_vcpu *, bool) nmi_allowed;
    bool (*)(struct kvm_vcpu *) get_nmi_mask;
    void (*)(struct kvm_vcpu *, bool) set_nmi_mask;
    void (*)(struct kvm_vcpu *) enable_nmi_window;
    void (*)(struct kvm_vcpu *) enable_irq_window;
    void (*)(struct kvm_vcpu *, int, int) update_cr8_intercept;
    bool (*)(ulong) check_apicv_inhibit_reasons;
    void (*)(struct kvm *, bool) pre_update_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *) refresh_apicv_exec_ctrl;
    void (*)(struct kvm_vcpu *, int) hwapic_irr_update;
    void (*)(struct kvm_vcpu *, int) hwapic_isr_update;
    bool (*)(struct kvm_vcpu *) guest_apic_has_interrupt;
    void (*)(struct kvm_vcpu *, u64 *) load_eoi_exitmap;
    void (*)(struct kvm_vcpu *) set_virtual_apic_mode;
    void (*)(struct kvm_vcpu *) set_apic_access_page_addr;
    int (*)(struct kvm_vcpu *, int) deliver_posted_interrupt;
    int (*)(struct kvm_vcpu *) sync_pir_to_irr;
    int (*)(struct kvm *, unsigned int) set_tss_addr;
    int (*)(struct kvm *, u64) set_identity_map_addr;
    u64 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask;
    void (*)(struct kvm_vcpu *, hpa_t, int) load_mmu_pgd;
    bool (*)() has_wbinvd_exit;
    u64 (*)(struct kvm_vcpu *, u64) write_l1_tsc_offset;
    void (*)(struct kvm_vcpu *, u64 *, u64 *, u32 *, u32 *) get_exit_info;
    int (*)(struct kvm_vcpu *, struct x86_instruction_info *, enum x86_intercept_stage, struct x86_exception *) check_intercept;
    void (*)(struct kvm_vcpu *) handle_exit_irqoff;
    void (*)(struct kvm_vcpu *) request_immediate_exit;
    void (*)(struct kvm_vcpu *, int) sched_in;
    int cpu_dirty_log_size;
    void (*)(struct kvm_vcpu *) update_cpu_dirty_logging;
    const struct kvm_pmu_ops * pmu_ops;
    const struct kvm_x86_nested_ops * nested_ops;
    int (*)(struct kvm_vcpu *) pre_block;
    void (*)(struct kvm_vcpu *) post_block;
    void (*)(struct kvm_vcpu *) vcpu_blocking;
    void (*)(struct kvm_vcpu *) vcpu_unblocking;
    int (*)(struct kvm *, unsigned int, uint32_t, bool) update_pi_irte;
    void (*)(struct kvm *) start_assignment;
    void (*)(struct kvm_vcpu *) apicv_post_state_restore;
    bool (*)(struct kvm_vcpu *) dy_apicv_has_pending_interrupt;
    int (*)(struct kvm_vcpu *, u64, bool *) set_hv_timer;
    void (*)(struct kvm_vcpu *) cancel_hv_timer;
    void (*)(struct kvm_vcpu *) setup_mce;
    int (*)(struct kvm_vcpu *, bool) smi_allowed;
    int (*)(struct kvm_vcpu *, char *) pre_enter_smm;
    int (*)(struct kvm_vcpu *, const char *) pre_leave_smm;
    void (*)(struct kvm_vcpu *) enable_smi_window;
    int (*)(struct kvm *, void *) mem_enc_op;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_reg_region;
    int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unreg_region;
    int (*)(struct kvm *, unsigned int) vm_copy_enc_context_from;
    int (*)(struct kvm_msr_entry *) get_msr_feature;
    bool (*)(struct kvm_vcpu *, void *, int) can_emulate_instruction;
    bool (*)(struct kvm_vcpu *) apic_init_signal_blocked;
    int (*)(struct kvm_vcpu *) enable_direct_tlbflush;
    void (*)(struct kvm_vcpu *) migrate_timers;
    void (*)(struct kvm_vcpu *) msr_filter_changed;
    int (*)(struct kvm_vcpu *, int) complete_emulated_msr;
    void (*)(struct kvm_vcpu *, u8) vcpu_deliver_sipi_vector;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct kvm_vcpu *) get_if_flag</code>
</li>
<li>
<b>Field added. </b>
<code>u64 (*)(struct kvm_vcpu *) get_l2_tsc_offset</code>
</li>
<li>
<b>Field added. </b>
<code>u64 (*)(struct kvm_vcpu *) get_l2_tsc_multiplier</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *, u64) write_tsc_offset</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *, u64) write_tsc_multiplier</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm_vcpu *, char *) enter_smm</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm_vcpu *, const char *) leave_smm</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm *, bool) pre_update_apicv_exec_ctrl</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 (*)(struct kvm_vcpu *, u64) write_l1_tsc_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm_vcpu *, char *) pre_enter_smm</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm_vcpu *, const char *) pre_leave_smm</code>
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
<code>const char * name</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) prepare_switch_to_guest</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *, long unsigned int) post_set_cr3</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) flush_tlb_all</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) flush_tlb_current</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *, gva_t) flush_tlb_gva</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) flush_tlb_guest</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm_vcpu *) vcpu_pre_run</code>
</li>
<li>
<b>Field added. </b>
<code>enum exit_fastpath_completion (*)(struct kvm_vcpu *) vcpu_run</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) inject_irq</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) inject_nmi</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_lapic *, int, int, int) deliver_interrupt</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm *, unsigned int, uint32_t, bool) pi_update_irte</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm *) pi_start_assignment</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm *, void *) mem_enc_ioctl</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_register_region</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unregister_region</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm *, unsigned int) vm_move_enc_context_from</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm *) guest_memory_reclaimed</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int (*)(struct kvm_vcpu *) vcpu_get_apicv_inhibit_reasons</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)() cpu_has_accelerated_tpr</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *) prepare_guest_switch</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *) tlb_flush_all</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *) tlb_flush_current</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *, gva_t) tlb_flush_gva</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *) tlb_flush_guest</code>
</li>
<li>
<b>Field removed. </b>
<code>enum exit_fastpath_completion (*)(struct kvm_vcpu *) run</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *) set_irq</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *) set_nmi</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm_vcpu *, int) deliver_posted_interrupt</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct kvm_pmu_ops * pmu_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm_vcpu *) pre_block</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *) post_block</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm *, unsigned int, uint32_t, bool) update_pi_irte</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm *) start_assignment</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm *, void *) mem_enc_op</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_reg_region</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm *, struct kvm_enc_region *) mem_enc_unreg_region</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(ulong) check_apicv_inhibit_reasons</code> ➡️ <code>bool (*)(enum kvm_apicv_inhibit) check_apicv_inhibit_reasons</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct kvm_vcpu *, u64 *, u64 *, u32 *, u32 *) get_exit_info</code> ➡️ <code>void (*)(struct kvm_vcpu *, u32 *, u64 *, u64 *, u32 *, u32 *) get_exit_info</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct kvm_vcpu *, void *, int) can_emulate_instruction</code> ➡️ <code>bool (*)(struct kvm_vcpu *, int, void *, int) can_emulate_instruction</code>
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
<code>int (*)(struct kvm *) vcpu_precreate</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kvm_vcpu *) inject_exception</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm_vcpu *) enable_l2_tlb_flush</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kvm_vcpu *) queue_exception</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm_vcpu *) enable_direct_tlbflush</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct kvm_vcpu *) inject_irq</code> ➡️ <code>void (*)(struct kvm_vcpu *, bool) inject_irq</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct kvm_vcpu *, int) hwapic_isr_update</code> ➡️ <code>void (*)(int) hwapic_isr_update</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask</code> ➡️ <code>u8 (*)(struct kvm_vcpu *, gfn_t, bool) get_mt_mask</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct kvm_vcpu *, char *) enter_smm</code> ➡️ <code>int (*)(struct kvm_vcpu *, union kvm_smram *) enter_smm</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct kvm_vcpu *, const char *) leave_smm</code> ➡️ <code>int (*)(struct kvm_vcpu *, const union kvm_smram *) leave_smm</code>
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
<code>int (*)() check_processor_compatibility</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct kvm_vcpu *, long unsigned int) is_valid_cr0</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm *) flush_remote_tlbs</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm *, gfn_t, gfn_t) flush_remote_tlbs_range</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct kvm_vcpu *) is_vnmi_pending</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct kvm_vcpu *) set_vnmi_pending</code>
</li>
<li>
<b>Field added. </b>
<code>const long unsigned int required_apicv_inhibits</code>
</li>
<li>
<b>Field added. </b>
<code>bool allow_apicv_in_x2apic_without_x2apic_virtualization</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm *) tlb_remote_flush</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct kvm *, struct kvm_tlb_range *) tlb_remote_flush_with_range</code>
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
<code>void (*)(struct kvm_vcpu *) apicv_pre_state_restore</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct kvm_vcpu *, int, void *, int) check_emulate_instruction</code>
</li>
<li>
<b>Field added. </b>
<code>gva_t (*)(struct kvm_vcpu *, gva_t, unsigned int) get_untagged_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct kvm_vcpu *, int, void *, int) can_emulate_instruction</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct kvm_vcpu *, u64) write_tsc_offset</code> ➡️ <code>void (*)(struct kvm_vcpu *) write_tsc_offset</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct kvm_vcpu *, u64) write_tsc_multiplier</code> ➡️ <code>void (*)(struct kvm_vcpu *) write_tsc_multiplier</code>
</li>
</ul>
</details>
</li>
</ul>
