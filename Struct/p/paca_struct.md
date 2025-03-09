# Struct: <code>paca_struct</code>

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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct paca_struct {
    struct lppaca * lppaca_ptr;
    u16 paca_index;
    u16 lock_token;
    u64 kernel_toc;
    u64 kernelbase;
    u64 kernel_msr;
    void * emergency_sp;
    u64 data_offset;
    s16 hw_cpu_id;
    u8 cpu_start;
    u8 kexec_state;
    struct slb_shadow * slb_shadow_ptr;
    struct dtl_entry * dispatch_log;
    struct dtl_entry * dispatch_log_end;
    u64 dscr_default;
    u64[10] exgen;
    u64[10] exslb;
    u16 vmalloc_sllp;
    u8 slb_cache_ptr;
    u8 stab_rr;
    u32 slb_used_bitmap;
    u32 slb_kern_bitmap;
    u32[8] slb_cache;
    mm_context_id_t mm_ctx_id;
    unsigned char[8] mm_ctx_low_slices_psize;
    unsigned char[2048] mm_ctx_high_slices_psize;
    long unsigned int mm_ctx_slb_addr_limit;
    struct task_struct * __current;
    u64 kstack;
    u64 saved_r1;
    u64 saved_msr;
    u8 irq_soft_mask;
    u8 irq_happened;
    u8 irq_work_pending;
    u8 pmcregs_in_use;
    u64 sprg_vdso;
    u64 tm_scratch;
    long unsigned int idle_state;
    u8 thread_idle_state;
    u8 subcore_sibling_mask;
    u64 requested_psscr;
    atomic_t dont_stop;
    u64[10] exnmi;
    u64[10] exmc;
    void * nmi_emergency_sp;
    void * mc_emergency_sp;
    u16 in_nmi;
    u16 in_mce;
    u8 hmi_event_available;
    u8 hmi_p9_special_emu;
    u8 ftrace_enabled;
    struct cpu_accounting_data accounting;
    u64 dtl_ridx;
    struct dtl_entry * dtl_curr;
    struct kvmppc_book3s_shadow_vcpu shadow_vcpu;
    struct kvmppc_host_state kvm_hstate;
    struct sibling_subcore_state * sibling_subcore_state;
    u64[10] exrfi;
    void * rfi_flush_fallback_area;
    u64 l1d_flush_size;
    u8 * mce_data_buf;
    struct slb_entry * mce_faulty_slbs;
    u16 slb_save_cache_ptr;
    long unsigned int canary;
    struct mmiowb_state mmiowb_state;
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct paca_struct {
    struct lppaca * lppaca_ptr;
    u16 paca_index;
    u16 lock_token;
    u64 kernel_toc;
    u64 kernelbase;
    u64 kernel_msr;
    void * emergency_sp;
    u64 data_offset;
    s16 hw_cpu_id;
    u8 cpu_start;
    u8 kexec_state;
    struct slb_shadow * slb_shadow_ptr;
    struct dtl_entry * dispatch_log;
    struct dtl_entry * dispatch_log_end;
    u64 dscr_default;
    u64[10] exgen;
    u64[10] exslb;
    u16 vmalloc_sllp;
    u8 slb_cache_ptr;
    u8 stab_rr;
    u32 slb_used_bitmap;
    u32 slb_kern_bitmap;
    u32[8] slb_cache;
    mm_context_id_t mm_ctx_id;
    unsigned char[8] mm_ctx_low_slices_psize;
    unsigned char[2048] mm_ctx_high_slices_psize;
    long unsigned int mm_ctx_slb_addr_limit;
    struct task_struct * __current;
    u64 kstack;
    u64 saved_r1;
    u64 saved_msr;
    u8 irq_soft_mask;
    u8 irq_happened;
    u8 irq_work_pending;
    u8 pmcregs_in_use;
    u64 sprg_vdso;
    u64 tm_scratch;
    long unsigned int idle_state;
    u8 thread_idle_state;
    u8 subcore_sibling_mask;
    u64 requested_psscr;
    atomic_t dont_stop;
    u64[10] exnmi;
    u64[10] exmc;
    void * nmi_emergency_sp;
    void * mc_emergency_sp;
    u16 in_nmi;
    u16 in_mce;
    u8 hmi_event_available;
    u8 hmi_p9_special_emu;
    u8 ftrace_enabled;
    struct cpu_accounting_data accounting;
    u64 dtl_ridx;
    struct dtl_entry * dtl_curr;
    struct kvmppc_book3s_shadow_vcpu shadow_vcpu;
    struct kvmppc_host_state kvm_hstate;
    struct sibling_subcore_state * sibling_subcore_state;
    u64[10] exrfi;
    void * rfi_flush_fallback_area;
    u64 l1d_flush_size;
    u8 * mce_data_buf;
    struct slb_entry * mce_faulty_slbs;
    u16 slb_save_cache_ptr;
    long unsigned int canary;
    struct mmiowb_state mmiowb_state;
}
```
</details>
</li>
</ul>
