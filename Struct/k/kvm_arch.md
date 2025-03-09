# Struct: <code>kvm_arch</code>

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
struct kvm_arch {
    long unsigned int n_used_mmu_pages;
    long unsigned int n_requested_mmu_pages;
    long unsigned int n_max_mmu_pages;
    unsigned int indirect_shadow_pages;
    u8 mmu_valid_gen;
    struct hlist_head[4096] mmu_page_hash;
    struct list_head active_mmu_pages;
    struct list_head zapped_obsolete_pages;
    struct list_head lpage_disallowed_mmu_pages;
    struct kvm_page_track_notifier_node mmu_sp_tracker;
    struct kvm_page_track_notifier_head track_notifier_head;
    struct list_head assigned_dev_head;
    struct iommu_domain * iommu_domain;
    bool iommu_noncoherent;
    atomic_t noncoherent_dma_count;
    atomic_t assigned_device_count;
    struct kvm_pic * vpic;
    struct kvm_ioapic * vioapic;
    struct kvm_pit * vpit;
    atomic_t vapics_in_nmi_mode;
    struct mutex apic_map_lock;
    struct kvm_apic_map * apic_map;
    atomic_t apic_map_dirty;
    bool apic_access_page_done;
    long unsigned int apicv_inhibit_reasons;
    gpa_t wall_clock;
    bool mwait_in_guest;
    bool hlt_in_guest;
    bool pause_in_guest;
    bool cstate_in_guest;
    long unsigned int irq_sources_bitmap;
    s64 kvmclock_offset;
    raw_spinlock_t tsc_write_lock;
    u64 last_tsc_nsec;
    u64 last_tsc_write;
    u32 last_tsc_khz;
    u64 cur_tsc_nsec;
    u64 cur_tsc_write;
    u64 cur_tsc_offset;
    u64 cur_tsc_generation;
    int nr_vcpus_matched_tsc;
    spinlock_t pvclock_gtod_sync_lock;
    bool use_master_clock;
    u64 master_kernel_ns;
    u64 master_cycle_now;
    struct delayed_work kvmclock_update_work;
    struct delayed_work kvmclock_sync_work;
    struct kvm_xen_hvm_config xen_hvm_config;
    struct hlist_head mask_notifier_list;
    struct kvm_hv hyperv;
    bool backwards_tsc_observed;
    bool boot_vcpu_runs_old_kvmclock;
    u32 bsp_vcpu_id;
    u64 disabled_quirks;
    enum kvm_irqchip_mode irqchip_mode;
    u8 nr_reserved_ioapic_pins;
    bool disabled_lapic_found;
    bool x2apic_format;
    bool x2apic_broadcast_quirk_disabled;
    bool guest_can_read_msr_platform_info;
    bool exception_payload_enabled;
    bool bus_lock_detection_enabled;
    u32 user_space_msr_mask;
    struct kvm_x86_msr_filter * msr_filter;
    struct kvm_pmu_event_filter * pmu_event_filter;
    struct task_struct * nx_lpage_recovery_thread;
    bool tdp_mmu_enabled;
    struct list_head tdp_mmu_roots;
    struct list_head tdp_mmu_pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_arch {
    long unsigned int n_used_mmu_pages;
    long unsigned int n_requested_mmu_pages;
    long unsigned int n_max_mmu_pages;
    unsigned int indirect_shadow_pages;
    u8 mmu_valid_gen;
    struct hlist_head[4096] mmu_page_hash;
    struct list_head active_mmu_pages;
    struct list_head zapped_obsolete_pages;
    struct list_head lpage_disallowed_mmu_pages;
    struct kvm_page_track_notifier_node mmu_sp_tracker;
    struct kvm_page_track_notifier_head track_notifier_head;
    spinlock_t mmu_unsync_pages_lock;
    struct list_head assigned_dev_head;
    struct iommu_domain * iommu_domain;
    bool iommu_noncoherent;
    atomic_t noncoherent_dma_count;
    atomic_t assigned_device_count;
    struct kvm_pic * vpic;
    struct kvm_ioapic * vioapic;
    struct kvm_pit * vpit;
    atomic_t vapics_in_nmi_mode;
    struct mutex apic_map_lock;
    struct kvm_apic_map * apic_map;
    atomic_t apic_map_dirty;
    bool apic_access_page_done;
    long unsigned int apicv_inhibit_reasons;
    gpa_t wall_clock;
    bool mwait_in_guest;
    bool hlt_in_guest;
    bool pause_in_guest;
    bool cstate_in_guest;
    long unsigned int irq_sources_bitmap;
    s64 kvmclock_offset;
    raw_spinlock_t tsc_write_lock;
    u64 last_tsc_nsec;
    u64 last_tsc_write;
    u32 last_tsc_khz;
    u64 cur_tsc_nsec;
    u64 cur_tsc_write;
    u64 cur_tsc_offset;
    u64 cur_tsc_generation;
    int nr_vcpus_matched_tsc;
    spinlock_t pvclock_gtod_sync_lock;
    bool use_master_clock;
    u64 master_kernel_ns;
    u64 master_cycle_now;
    struct delayed_work kvmclock_update_work;
    struct delayed_work kvmclock_sync_work;
    struct kvm_xen_hvm_config xen_hvm_config;
    struct hlist_head mask_notifier_list;
    struct kvm_hv hyperv;
    struct kvm_xen xen;
    bool backwards_tsc_observed;
    bool boot_vcpu_runs_old_kvmclock;
    u32 bsp_vcpu_id;
    u64 disabled_quirks;
    int cpu_dirty_logging_count;
    enum kvm_irqchip_mode irqchip_mode;
    u8 nr_reserved_ioapic_pins;
    bool disabled_lapic_found;
    bool x2apic_format;
    bool x2apic_broadcast_quirk_disabled;
    bool guest_can_read_msr_platform_info;
    bool exception_payload_enabled;
    bool bus_lock_detection_enabled;
    u32 user_space_msr_mask;
    struct kvm_x86_msr_filter * msr_filter;
    bool sgx_provisioning_allowed;
    struct kvm_pmu_event_filter * pmu_event_filter;
    struct task_struct * nx_lpage_recovery_thread;
    bool tdp_mmu_enabled;
    struct list_head tdp_mmu_roots;
    struct list_head tdp_mmu_pages;
    spinlock_t tdp_mmu_pages_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_arch {
    long unsigned int n_used_mmu_pages;
    long unsigned int n_requested_mmu_pages;
    long unsigned int n_max_mmu_pages;
    unsigned int indirect_shadow_pages;
    u8 mmu_valid_gen;
    struct hlist_head[4096] mmu_page_hash;
    struct list_head active_mmu_pages;
    struct list_head zapped_obsolete_pages;
    struct list_head lpage_disallowed_mmu_pages;
    struct kvm_page_track_notifier_node mmu_sp_tracker;
    struct kvm_page_track_notifier_head track_notifier_head;
    spinlock_t mmu_unsync_pages_lock;
    struct list_head assigned_dev_head;
    struct iommu_domain * iommu_domain;
    bool iommu_noncoherent;
    atomic_t noncoherent_dma_count;
    atomic_t assigned_device_count;
    struct kvm_pic * vpic;
    struct kvm_ioapic * vioapic;
    struct kvm_pit * vpit;
    atomic_t vapics_in_nmi_mode;
    struct mutex apic_map_lock;
    struct kvm_apic_map * apic_map;
    atomic_t apic_map_dirty;
    struct mutex apicv_update_lock;
    bool apic_access_memslot_enabled;
    long unsigned int apicv_inhibit_reasons;
    gpa_t wall_clock;
    bool mwait_in_guest;
    bool hlt_in_guest;
    bool pause_in_guest;
    bool cstate_in_guest;
    long unsigned int irq_sources_bitmap;
    s64 kvmclock_offset;
    raw_spinlock_t tsc_write_lock;
    u64 last_tsc_nsec;
    u64 last_tsc_write;
    u32 last_tsc_khz;
    u64 cur_tsc_nsec;
    u64 cur_tsc_write;
    u64 cur_tsc_offset;
    u64 cur_tsc_generation;
    int nr_vcpus_matched_tsc;
    raw_spinlock_t pvclock_gtod_sync_lock;
    bool use_master_clock;
    u64 master_kernel_ns;
    u64 master_cycle_now;
    struct delayed_work kvmclock_update_work;
    struct delayed_work kvmclock_sync_work;
    struct kvm_xen_hvm_config xen_hvm_config;
    struct hlist_head mask_notifier_list;
    struct kvm_hv hyperv;
    struct kvm_xen xen;
    bool backwards_tsc_observed;
    bool boot_vcpu_runs_old_kvmclock;
    u32 bsp_vcpu_id;
    u64 disabled_quirks;
    int cpu_dirty_logging_count;
    enum kvm_irqchip_mode irqchip_mode;
    u8 nr_reserved_ioapic_pins;
    bool disabled_lapic_found;
    bool x2apic_format;
    bool x2apic_broadcast_quirk_disabled;
    bool guest_can_read_msr_platform_info;
    bool exception_payload_enabled;
    bool bus_lock_detection_enabled;
    bool exit_on_emulation_error;
    u32 user_space_msr_mask;
    struct kvm_x86_msr_filter * msr_filter;
    u32 hypercall_exit_enabled;
    bool sgx_provisioning_allowed;
    struct kvm_pmu_event_filter * pmu_event_filter;
    struct task_struct * nx_lpage_recovery_thread;
    bool tdp_mmu_enabled;
    struct list_head tdp_mmu_roots;
    struct list_head tdp_mmu_pages;
    spinlock_t tdp_mmu_pages_lock;
    bool memslots_have_rmaps;
    hpa_t hv_root_tdp;
    spinlock_t hv_root_tdp_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_arch {
    long unsigned int n_used_mmu_pages;
    long unsigned int n_requested_mmu_pages;
    long unsigned int n_max_mmu_pages;
    unsigned int indirect_shadow_pages;
    u8 mmu_valid_gen;
    struct hlist_head[4096] mmu_page_hash;
    struct list_head active_mmu_pages;
    struct list_head zapped_obsolete_pages;
    struct list_head lpage_disallowed_mmu_pages;
    struct kvm_page_track_notifier_node mmu_sp_tracker;
    struct kvm_page_track_notifier_head track_notifier_head;
    spinlock_t mmu_unsync_pages_lock;
    struct list_head assigned_dev_head;
    struct iommu_domain * iommu_domain;
    bool iommu_noncoherent;
    atomic_t noncoherent_dma_count;
    atomic_t assigned_device_count;
    struct kvm_pic * vpic;
    struct kvm_ioapic * vioapic;
    struct kvm_pit * vpit;
    atomic_t vapics_in_nmi_mode;
    struct mutex apic_map_lock;
    struct kvm_apic_map * apic_map;
    atomic_t apic_map_dirty;
    struct rw_semaphore apicv_update_lock;
    bool apic_access_memslot_enabled;
    long unsigned int apicv_inhibit_reasons;
    gpa_t wall_clock;
    bool mwait_in_guest;
    bool hlt_in_guest;
    bool pause_in_guest;
    bool cstate_in_guest;
    long unsigned int irq_sources_bitmap;
    s64 kvmclock_offset;
    raw_spinlock_t tsc_write_lock;
    u64 last_tsc_nsec;
    u64 last_tsc_write;
    u32 last_tsc_khz;
    u64 last_tsc_offset;
    u64 cur_tsc_nsec;
    u64 cur_tsc_write;
    u64 cur_tsc_offset;
    u64 cur_tsc_generation;
    int nr_vcpus_matched_tsc;
    u32 default_tsc_khz;
    seqcount_raw_spinlock_t pvclock_sc;
    bool use_master_clock;
    u64 master_kernel_ns;
    u64 master_cycle_now;
    struct delayed_work kvmclock_update_work;
    struct delayed_work kvmclock_sync_work;
    struct kvm_xen_hvm_config xen_hvm_config;
    struct hlist_head mask_notifier_list;
    struct kvm_hv hyperv;
    struct kvm_xen xen;
    bool backwards_tsc_observed;
    bool boot_vcpu_runs_old_kvmclock;
    u32 bsp_vcpu_id;
    u64 disabled_quirks;
    int cpu_dirty_logging_count;
    enum kvm_irqchip_mode irqchip_mode;
    u8 nr_reserved_ioapic_pins;
    bool disabled_lapic_found;
    bool x2apic_format;
    bool x2apic_broadcast_quirk_disabled;
    bool guest_can_read_msr_platform_info;
    bool exception_payload_enabled;
    bool bus_lock_detection_enabled;
    bool enable_pmu;
    bool exit_on_emulation_error;
    u32 user_space_msr_mask;
    struct kvm_x86_msr_filter * msr_filter;
    u32 hypercall_exit_enabled;
    bool sgx_provisioning_allowed;
    struct kvm_pmu_event_filter * pmu_event_filter;
    struct task_struct * nx_lpage_recovery_thread;
    bool tdp_mmu_enabled;
    struct list_head tdp_mmu_roots;
    struct list_head tdp_mmu_pages;
    spinlock_t tdp_mmu_pages_lock;
    struct workqueue_struct * tdp_mmu_zap_wq;
    bool shadow_root_allocated;
    hpa_t hv_root_tdp;
    spinlock_t hv_root_tdp_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_arch {
    long unsigned int n_used_mmu_pages;
    long unsigned int n_requested_mmu_pages;
    long unsigned int n_max_mmu_pages;
    unsigned int indirect_shadow_pages;
    u8 mmu_valid_gen;
    struct hlist_head[4096] mmu_page_hash;
    struct list_head active_mmu_pages;
    struct list_head zapped_obsolete_pages;
    struct list_head possible_nx_huge_pages;
    struct kvm_page_track_notifier_node mmu_sp_tracker;
    struct kvm_page_track_notifier_head track_notifier_head;
    spinlock_t mmu_unsync_pages_lock;
    struct list_head assigned_dev_head;
    struct iommu_domain * iommu_domain;
    bool iommu_noncoherent;
    atomic_t noncoherent_dma_count;
    atomic_t assigned_device_count;
    struct kvm_pic * vpic;
    struct kvm_ioapic * vioapic;
    struct kvm_pit * vpit;
    atomic_t vapics_in_nmi_mode;
    struct mutex apic_map_lock;
    struct kvm_apic_map * apic_map;
    atomic_t apic_map_dirty;
    struct rw_semaphore apicv_update_lock;
    bool apic_access_memslot_enabled;
    long unsigned int apicv_inhibit_reasons;
    gpa_t wall_clock;
    bool mwait_in_guest;
    bool hlt_in_guest;
    bool pause_in_guest;
    bool cstate_in_guest;
    long unsigned int irq_sources_bitmap;
    s64 kvmclock_offset;
    raw_spinlock_t tsc_write_lock;
    u64 last_tsc_nsec;
    u64 last_tsc_write;
    u32 last_tsc_khz;
    u64 last_tsc_offset;
    u64 cur_tsc_nsec;
    u64 cur_tsc_write;
    u64 cur_tsc_offset;
    u64 cur_tsc_generation;
    int nr_vcpus_matched_tsc;
    u32 default_tsc_khz;
    seqcount_raw_spinlock_t pvclock_sc;
    bool use_master_clock;
    u64 master_kernel_ns;
    u64 master_cycle_now;
    struct delayed_work kvmclock_update_work;
    struct delayed_work kvmclock_sync_work;
    struct kvm_xen_hvm_config xen_hvm_config;
    struct hlist_head mask_notifier_list;
    struct kvm_hv hyperv;
    struct kvm_xen xen;
    bool backwards_tsc_observed;
    bool boot_vcpu_runs_old_kvmclock;
    u32 bsp_vcpu_id;
    u64 disabled_quirks;
    int cpu_dirty_logging_count;
    enum kvm_irqchip_mode irqchip_mode;
    u8 nr_reserved_ioapic_pins;
    bool disabled_lapic_found;
    bool x2apic_format;
    bool x2apic_broadcast_quirk_disabled;
    bool guest_can_read_msr_platform_info;
    bool exception_payload_enabled;
    bool triple_fault_event;
    bool bus_lock_detection_enabled;
    bool enable_pmu;
    u32 notify_window;
    u32 notify_vmexit_flags;
    bool exit_on_emulation_error;
    u32 user_space_msr_mask;
    struct kvm_x86_msr_filter * msr_filter;
    u32 hypercall_exit_enabled;
    bool sgx_provisioning_allowed;
    struct kvm_pmu_event_filter * pmu_event_filter;
    struct task_struct * nx_huge_page_recovery_thread;
    bool tdp_mmu_enabled;
    atomic64_t tdp_mmu_pages;
    struct list_head tdp_mmu_roots;
    spinlock_t tdp_mmu_pages_lock;
    struct workqueue_struct * tdp_mmu_zap_wq;
    bool shadow_root_allocated;
    hpa_t hv_root_tdp;
    spinlock_t hv_root_tdp_lock;
    u32 max_vcpu_ids;
    bool disable_nx_huge_pages;
    struct kvm_mmu_memory_cache split_shadow_page_cache;
    struct kvm_mmu_memory_cache split_page_header_cache;
    struct kvm_mmu_memory_cache split_desc_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_arch {
    long unsigned int n_used_mmu_pages;
    long unsigned int n_requested_mmu_pages;
    long unsigned int n_max_mmu_pages;
    unsigned int indirect_shadow_pages;
    u8 mmu_valid_gen;
    struct hlist_head[4096] mmu_page_hash;
    struct list_head active_mmu_pages;
    struct list_head zapped_obsolete_pages;
    struct list_head possible_nx_huge_pages;
    struct kvm_page_track_notifier_node mmu_sp_tracker;
    struct kvm_page_track_notifier_head track_notifier_head;
    spinlock_t mmu_unsync_pages_lock;
    struct list_head assigned_dev_head;
    struct iommu_domain * iommu_domain;
    bool iommu_noncoherent;
    atomic_t noncoherent_dma_count;
    atomic_t assigned_device_count;
    struct kvm_pic * vpic;
    struct kvm_ioapic * vioapic;
    struct kvm_pit * vpit;
    atomic_t vapics_in_nmi_mode;
    struct mutex apic_map_lock;
    struct kvm_apic_map * apic_map;
    atomic_t apic_map_dirty;
    bool apic_access_memslot_enabled;
    bool apic_access_memslot_inhibited;
    struct rw_semaphore apicv_update_lock;
    long unsigned int apicv_inhibit_reasons;
    gpa_t wall_clock;
    bool mwait_in_guest;
    bool hlt_in_guest;
    bool pause_in_guest;
    bool cstate_in_guest;
    long unsigned int irq_sources_bitmap;
    s64 kvmclock_offset;
    raw_spinlock_t tsc_write_lock;
    u64 last_tsc_nsec;
    u64 last_tsc_write;
    u32 last_tsc_khz;
    u64 last_tsc_offset;
    u64 cur_tsc_nsec;
    u64 cur_tsc_write;
    u64 cur_tsc_offset;
    u64 cur_tsc_generation;
    int nr_vcpus_matched_tsc;
    u32 default_tsc_khz;
    seqcount_raw_spinlock_t pvclock_sc;
    bool use_master_clock;
    u64 master_kernel_ns;
    u64 master_cycle_now;
    struct delayed_work kvmclock_update_work;
    struct delayed_work kvmclock_sync_work;
    struct kvm_xen_hvm_config xen_hvm_config;
    struct hlist_head mask_notifier_list;
    struct kvm_hv hyperv;
    struct kvm_xen xen;
    bool backwards_tsc_observed;
    bool boot_vcpu_runs_old_kvmclock;
    u32 bsp_vcpu_id;
    u64 disabled_quirks;
    enum kvm_irqchip_mode irqchip_mode;
    u8 nr_reserved_ioapic_pins;
    bool disabled_lapic_found;
    bool x2apic_format;
    bool x2apic_broadcast_quirk_disabled;
    bool guest_can_read_msr_platform_info;
    bool exception_payload_enabled;
    bool triple_fault_event;
    bool bus_lock_detection_enabled;
    bool enable_pmu;
    u32 notify_window;
    u32 notify_vmexit_flags;
    bool exit_on_emulation_error;
    u32 user_space_msr_mask;
    struct kvm_x86_msr_filter * msr_filter;
    u32 hypercall_exit_enabled;
    bool sgx_provisioning_allowed;
    struct kvm_x86_pmu_event_filter * pmu_event_filter;
    struct task_struct * nx_huge_page_recovery_thread;
    atomic64_t tdp_mmu_pages;
    struct list_head tdp_mmu_roots;
    spinlock_t tdp_mmu_pages_lock;
    struct workqueue_struct * tdp_mmu_zap_wq;
    bool shadow_root_allocated;
    hpa_t hv_root_tdp;
    spinlock_t hv_root_tdp_lock;
    u32 max_vcpu_ids;
    bool disable_nx_huge_pages;
    struct kvm_mmu_memory_cache split_shadow_page_cache;
    struct kvm_mmu_memory_cache split_page_header_cache;
    struct kvm_mmu_memory_cache split_desc_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_arch {
    long unsigned int vm_type;
    long unsigned int n_used_mmu_pages;
    long unsigned int n_requested_mmu_pages;
    long unsigned int n_max_mmu_pages;
    unsigned int indirect_shadow_pages;
    u8 mmu_valid_gen;
    struct hlist_head[4096] mmu_page_hash;
    struct list_head active_mmu_pages;
    struct list_head zapped_obsolete_pages;
    struct list_head possible_nx_huge_pages;
    struct kvm_page_track_notifier_head track_notifier_head;
    spinlock_t mmu_unsync_pages_lock;
    struct iommu_domain * iommu_domain;
    bool iommu_noncoherent;
    atomic_t noncoherent_dma_count;
    atomic_t assigned_device_count;
    struct kvm_pic * vpic;
    struct kvm_ioapic * vioapic;
    struct kvm_pit * vpit;
    atomic_t vapics_in_nmi_mode;
    struct mutex apic_map_lock;
    struct kvm_apic_map * apic_map;
    atomic_t apic_map_dirty;
    bool apic_access_memslot_enabled;
    bool apic_access_memslot_inhibited;
    struct rw_semaphore apicv_update_lock;
    long unsigned int apicv_inhibit_reasons;
    gpa_t wall_clock;
    bool mwait_in_guest;
    bool hlt_in_guest;
    bool pause_in_guest;
    bool cstate_in_guest;
    long unsigned int irq_sources_bitmap;
    s64 kvmclock_offset;
    raw_spinlock_t tsc_write_lock;
    u64 last_tsc_nsec;
    u64 last_tsc_write;
    u32 last_tsc_khz;
    u64 last_tsc_offset;
    u64 cur_tsc_nsec;
    u64 cur_tsc_write;
    u64 cur_tsc_offset;
    u64 cur_tsc_generation;
    int nr_vcpus_matched_tsc;
    u32 default_tsc_khz;
    bool user_set_tsc;
    seqcount_raw_spinlock_t pvclock_sc;
    bool use_master_clock;
    u64 master_kernel_ns;
    u64 master_cycle_now;
    struct delayed_work kvmclock_update_work;
    struct delayed_work kvmclock_sync_work;
    struct kvm_xen_hvm_config xen_hvm_config;
    struct hlist_head mask_notifier_list;
    struct kvm_hv hyperv;
    struct kvm_xen xen;
    bool backwards_tsc_observed;
    bool boot_vcpu_runs_old_kvmclock;
    u32 bsp_vcpu_id;
    u64 disabled_quirks;
    enum kvm_irqchip_mode irqchip_mode;
    u8 nr_reserved_ioapic_pins;
    bool disabled_lapic_found;
    bool x2apic_format;
    bool x2apic_broadcast_quirk_disabled;
    bool guest_can_read_msr_platform_info;
    bool exception_payload_enabled;
    bool triple_fault_event;
    bool bus_lock_detection_enabled;
    bool enable_pmu;
    u32 notify_window;
    u32 notify_vmexit_flags;
    bool exit_on_emulation_error;
    u32 user_space_msr_mask;
    struct kvm_x86_msr_filter * msr_filter;
    u32 hypercall_exit_enabled;
    bool sgx_provisioning_allowed;
    struct kvm_x86_pmu_event_filter * pmu_event_filter;
    struct task_struct * nx_huge_page_recovery_thread;
    atomic64_t tdp_mmu_pages;
    struct list_head tdp_mmu_roots;
    spinlock_t tdp_mmu_pages_lock;
    bool shadow_root_allocated;
    hpa_t hv_root_tdp;
    spinlock_t hv_root_tdp_lock;
    struct hv_partition_assist_pg * hv_pa_pg;
    u32 max_vcpu_ids;
    bool disable_nx_huge_pages;
    struct kvm_mmu_memory_cache split_shadow_page_cache;
    struct kvm_mmu_memory_cache split_page_header_cache;
    struct kvm_mmu_memory_cache split_desc_cache;
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
struct kvm_arch {
    struct kvm_vmid vmid;
    pgd_t * pgd;
    phys_addr_t pgd_phys;
    u64 vtcr;
    int * last_vcpu_ran;
    int max_vcpus;
    struct vgic_dist vgic;
    u32 psci_version;
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
struct kvm_arch {
    unsigned int lpid;
    unsigned int smt_mode;
    unsigned int emul_smt_mode;
    unsigned int tlb_sets;
    struct kvm_hpt_info hpt;
    atomic64_t mmio_update;
    unsigned int host_lpid;
    long unsigned int host_lpcr;
    long unsigned int sdr1;
    long unsigned int host_sdr1;
    long unsigned int lpcr;
    long unsigned int vrma_slb_v;
    int mmu_ready;
    atomic_t vcpus_running;
    u32 online_vcores;
    atomic_t hpte_mod_interest;
    cpumask_t need_tlb_flush;
    cpumask_t cpu_in_guest;
    u8 radix;
    u8 fwnmi_enabled;
    u8 secure_guest;
    bool threads_indep;
    bool nested_enable;
    pgd_t * pgtable;
    u64 process_table;
    struct dentry * debugfs_dir;
    struct dentry * htab_dentry;
    struct dentry * radix_dentry;
    struct kvm_resize_hpt * resize_hpt;
    struct mutex hpt_mutex;
    struct list_head spapr_tce_tables;
    struct list_head rtas_tokens;
    struct mutex rtas_token_lock;
    long unsigned int[5] enabled_hcalls;
    struct kvmppc_xics * xics;
    struct kvmppc_xive * xive;
    struct (anon) xive_devices;
    struct kvmppc_passthru_irqmap * pimap;
    struct kvmppc_ops * kvm_ops;
    struct mutex mmu_setup_lock;
    u64 l1_ptcr;
    int max_nested_lpid;
    struct kvm_nested_guest *[1024] nested_guests;
    struct kvmppc_vcore *[2048] vcores;
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
struct kvm_arch {
    long unsigned int n_used_mmu_pages;
    long unsigned int n_requested_mmu_pages;
    long unsigned int n_max_mmu_pages;
    unsigned int indirect_shadow_pages;
    u8 mmu_valid_gen;
    struct hlist_head[4096] mmu_page_hash;
    struct list_head active_mmu_pages;
    struct list_head zapped_obsolete_pages;
    struct list_head lpage_disallowed_mmu_pages;
    struct kvm_page_track_notifier_node mmu_sp_tracker;
    struct kvm_page_track_notifier_head track_notifier_head;
    struct list_head assigned_dev_head;
    struct iommu_domain * iommu_domain;
    bool iommu_noncoherent;
    atomic_t noncoherent_dma_count;
    atomic_t assigned_device_count;
    struct kvm_pic * vpic;
    struct kvm_ioapic * vioapic;
    struct kvm_pit * vpit;
    atomic_t vapics_in_nmi_mode;
    struct mutex apic_map_lock;
    struct kvm_apic_map * apic_map;
    atomic_t apic_map_dirty;
    bool apic_access_page_done;
    long unsigned int apicv_inhibit_reasons;
    gpa_t wall_clock;
    bool mwait_in_guest;
    bool hlt_in_guest;
    bool pause_in_guest;
    bool cstate_in_guest;
    long unsigned int irq_sources_bitmap;
    s64 kvmclock_offset;
    raw_spinlock_t tsc_write_lock;
    u64 last_tsc_nsec;
    u64 last_tsc_write;
    u32 last_tsc_khz;
    u64 cur_tsc_nsec;
    u64 cur_tsc_write;
    u64 cur_tsc_offset;
    u64 cur_tsc_generation;
    int nr_vcpus_matched_tsc;
    spinlock_t pvclock_gtod_sync_lock;
    bool use_master_clock;
    u64 master_kernel_ns;
    u64 master_cycle_now;
    struct delayed_work kvmclock_update_work;
    struct delayed_work kvmclock_sync_work;
    struct kvm_xen_hvm_config xen_hvm_config;
    struct hlist_head mask_notifier_list;
    struct kvm_hv hyperv;
    bool backwards_tsc_observed;
    bool boot_vcpu_runs_old_kvmclock;
    u32 bsp_vcpu_id;
    u64 disabled_quirks;
    enum kvm_irqchip_mode irqchip_mode;
    u8 nr_reserved_ioapic_pins;
    bool disabled_lapic_found;
    bool x2apic_format;
    bool x2apic_broadcast_quirk_disabled;
    bool guest_can_read_msr_platform_info;
    bool exception_payload_enabled;
    bool bus_lock_detection_enabled;
    u32 user_space_msr_mask;
    struct kvm_x86_msr_filter * msr_filter;
    struct kvm_pmu_event_filter * pmu_event_filter;
    struct task_struct * nx_lpage_recovery_thread;
    bool tdp_mmu_enabled;
    struct list_head tdp_mmu_roots;
    struct list_head tdp_mmu_pages;
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
<code>spinlock_t mmu_unsync_pages_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct kvm_xen xen</code>
</li>
<li>
<b>Field added. </b>
<code>int cpu_dirty_logging_count</code>
</li>
<li>
<b>Field added. </b>
<code>bool sgx_provisioning_allowed</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t tdp_mmu_pages_lock</code>
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
<code>struct mutex apicv_update_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool apic_access_memslot_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>bool exit_on_emulation_error</code>
</li>
<li>
<b>Field added. </b>
<code>u32 hypercall_exit_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>bool memslots_have_rmaps</code>
</li>
<li>
<b>Field added. </b>
<code>hpa_t hv_root_tdp</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t hv_root_tdp_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>bool apic_access_page_done</code>
</li>
<li>
<b>Field type changed. </b>
<code>spinlock_t pvclock_gtod_sync_lock</code> ➡️ <code>raw_spinlock_t pvclock_gtod_sync_lock</code>
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
<code>u64 last_tsc_offset</code>
</li>
<li>
<b>Field added. </b>
<code>u32 default_tsc_khz</code>
</li>
<li>
<b>Field added. </b>
<code>seqcount_raw_spinlock_t pvclock_sc</code>
</li>
<li>
<b>Field added. </b>
<code>bool enable_pmu</code>
</li>
<li>
<b>Field added. </b>
<code>struct workqueue_struct * tdp_mmu_zap_wq</code>
</li>
<li>
<b>Field added. </b>
<code>bool shadow_root_allocated</code>
</li>
<li>
<b>Field removed. </b>
<code>raw_spinlock_t pvclock_gtod_sync_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>bool memslots_have_rmaps</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct mutex apicv_update_lock</code> ➡️ <code>struct rw_semaphore apicv_update_lock</code>
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
<code>struct list_head possible_nx_huge_pages</code>
</li>
<li>
<b>Field added. </b>
<code>bool triple_fault_event</code>
</li>
<li>
<b>Field added. </b>
<code>u32 notify_window</code>
</li>
<li>
<b>Field added. </b>
<code>u32 notify_vmexit_flags</code>
</li>
<li>
<b>Field added. </b>
<code>struct task_struct * nx_huge_page_recovery_thread</code>
</li>
<li>
<b>Field added. </b>
<code>u32 max_vcpu_ids</code>
</li>
<li>
<b>Field added. </b>
<code>bool disable_nx_huge_pages</code>
</li>
<li>
<b>Field added. </b>
<code>struct kvm_mmu_memory_cache split_shadow_page_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct kvm_mmu_memory_cache split_page_header_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct kvm_mmu_memory_cache split_desc_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head lpage_disallowed_mmu_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * nx_lpage_recovery_thread</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head tdp_mmu_pages</code> ➡️ <code>atomic64_t tdp_mmu_pages</code>
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
<code>bool apic_access_memslot_inhibited</code>
</li>
<li>
<b>Field removed. </b>
<code>int cpu_dirty_logging_count</code>
</li>
<li>
<b>Field removed. </b>
<code>bool tdp_mmu_enabled</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct kvm_pmu_event_filter * pmu_event_filter</code> ➡️ <code>struct kvm_x86_pmu_event_filter * pmu_event_filter</code>
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
<code>long unsigned int vm_type</code>
</li>
<li>
<b>Field added. </b>
<code>bool user_set_tsc</code>
</li>
<li>
<b>Field added. </b>
<code>struct hv_partition_assist_pg * hv_pa_pg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kvm_page_track_notifier_node mmu_sp_tracker</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head assigned_dev_head</code>
</li>
<li>
<b>Field removed. </b>
<code>struct workqueue_struct * tdp_mmu_zap_wq</code>
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
struct kvm_arch {
    struct kvm_vmid vmid;
    pgd_t * pgd;
    phys_addr_t pgd_phys;
    u64 vtcr;
    int * last_vcpu_ran;
    int max_vcpus;
    struct vgic_dist vgic;
    u32 psci_version;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvm_arch {
    unsigned int lpid;
    unsigned int smt_mode;
    unsigned int emul_smt_mode;
    unsigned int tlb_sets;
    struct kvm_hpt_info hpt;
    atomic64_t mmio_update;
    unsigned int host_lpid;
    long unsigned int host_lpcr;
    long unsigned int sdr1;
    long unsigned int host_sdr1;
    long unsigned int lpcr;
    long unsigned int vrma_slb_v;
    int mmu_ready;
    atomic_t vcpus_running;
    u32 online_vcores;
    atomic_t hpte_mod_interest;
    cpumask_t need_tlb_flush;
    cpumask_t cpu_in_guest;
    u8 radix;
    u8 fwnmi_enabled;
    u8 secure_guest;
    bool threads_indep;
    bool nested_enable;
    pgd_t * pgtable;
    u64 process_table;
    struct dentry * debugfs_dir;
    struct dentry * htab_dentry;
    struct dentry * radix_dentry;
    struct kvm_resize_hpt * resize_hpt;
    struct mutex hpt_mutex;
    struct list_head spapr_tce_tables;
    struct list_head rtas_tokens;
    struct mutex rtas_token_lock;
    long unsigned int[5] enabled_hcalls;
    struct kvmppc_xics * xics;
    struct kvmppc_xive * xive;
    struct (anon) xive_devices;
    struct kvmppc_passthru_irqmap * pimap;
    struct kvmppc_ops * kvm_ops;
    struct mutex mmu_setup_lock;
    u64 l1_ptcr;
    int max_nested_lpid;
    struct kvm_nested_guest *[1024] nested_guests;
    struct kvmppc_vcore *[2048] vcores;
}
```
</details>
</li>
</ul>
