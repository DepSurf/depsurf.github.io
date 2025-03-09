# Struct: <code>kvm</code>

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
struct kvm {
    spinlock_t mmu_lock;
    struct mutex slots_lock;
    struct mm_struct * mm;
    struct kvm_memslots *[2] memslots;
    struct kvm_vcpu *[288] vcpus;
    atomic_t online_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long int tlbs_dirty;
    struct list_head devices;
    u64 manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
    unsigned int max_halt_poll_ns;
    u32 dirty_ring_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm {
    rwlock_t mmu_lock;
    struct mutex slots_lock;
    struct mm_struct * mm;
    struct kvm_memslots *[2] memslots;
    struct kvm_vcpu *[288] vcpus;
    atomic_t online_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long unsigned int mmu_notifier_range_start;
    long unsigned int mmu_notifier_range_end;
    long int tlbs_dirty;
    struct list_head devices;
    u64 manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
    unsigned int max_halt_poll_ns;
    u32 dirty_ring_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm {
    rwlock_t mmu_lock;
    struct mutex slots_lock;
    struct mutex slots_arch_lock;
    struct mm_struct * mm;
    struct kvm_memslots *[2] memslots;
    struct kvm_vcpu *[1024] vcpus;
    spinlock_t mn_invalidate_lock;
    long unsigned int mn_active_invalidate_count;
    struct rcuwait mn_memslots_update_rcuwait;
    atomic_t online_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long unsigned int mmu_notifier_range_start;
    long unsigned int mmu_notifier_range_end;
    struct list_head devices;
    u64 manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
    unsigned int max_halt_poll_ns;
    u32 dirty_ring_size;
    bool vm_bugged;
    struct notifier_block pm_notifier;
    char[48] stats_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm {
    rwlock_t mmu_lock;
    struct mutex slots_lock;
    struct mutex slots_arch_lock;
    struct mm_struct * mm;
    long unsigned int nr_memslot_pages;
    struct kvm_memslots[4] __memslots;
    struct kvm_memslots *[2] memslots;
    struct xarray vcpu_array;
    spinlock_t mn_invalidate_lock;
    long unsigned int mn_active_invalidate_count;
    struct rcuwait mn_memslots_update_rcuwait;
    spinlock_t gpc_lock;
    struct list_head gpc_list;
    atomic_t online_vcpus;
    int max_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long unsigned int mmu_notifier_range_start;
    long unsigned int mmu_notifier_range_end;
    struct list_head devices;
    u64 manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
    unsigned int max_halt_poll_ns;
    u32 dirty_ring_size;
    bool vm_bugged;
    bool vm_dead;
    struct notifier_block pm_notifier;
    char[48] stats_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm {
    rwlock_t mmu_lock;
    struct mutex slots_lock;
    struct mutex slots_arch_lock;
    struct mm_struct * mm;
    long unsigned int nr_memslot_pages;
    struct kvm_memslots[4] __memslots;
    struct kvm_memslots *[2] memslots;
    struct xarray vcpu_array;
    atomic_t nr_memslots_dirty_logging;
    spinlock_t mn_invalidate_lock;
    long unsigned int mn_active_invalidate_count;
    struct rcuwait mn_memslots_update_rcuwait;
    spinlock_t gpc_lock;
    struct list_head gpc_list;
    atomic_t online_vcpus;
    int max_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_invalidate_seq;
    long int mmu_invalidate_in_progress;
    long unsigned int mmu_invalidate_range_start;
    long unsigned int mmu_invalidate_range_end;
    struct list_head devices;
    u64 manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
    bool override_halt_poll_ns;
    unsigned int max_halt_poll_ns;
    u32 dirty_ring_size;
    bool dirty_ring_with_bitmap;
    bool vm_bugged;
    bool vm_dead;
    struct notifier_block pm_notifier;
    char[48] stats_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm {
    rwlock_t mmu_lock;
    struct mutex slots_lock;
    struct mutex slots_arch_lock;
    struct mm_struct * mm;
    long unsigned int nr_memslot_pages;
    struct kvm_memslots[4] __memslots;
    struct kvm_memslots *[2] memslots;
    struct xarray vcpu_array;
    atomic_t nr_memslots_dirty_logging;
    spinlock_t mn_invalidate_lock;
    long unsigned int mn_active_invalidate_count;
    struct rcuwait mn_memslots_update_rcuwait;
    spinlock_t gpc_lock;
    struct list_head gpc_list;
    atomic_t online_vcpus;
    int max_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_invalidate_seq;
    long int mmu_invalidate_in_progress;
    long unsigned int mmu_invalidate_range_start;
    long unsigned int mmu_invalidate_range_end;
    struct list_head devices;
    u64 manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
    bool override_halt_poll_ns;
    unsigned int max_halt_poll_ns;
    u32 dirty_ring_size;
    bool dirty_ring_with_bitmap;
    bool vm_bugged;
    bool vm_dead;
    struct notifier_block pm_notifier;
    char[48] stats_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm {
    rwlock_t mmu_lock;
    struct mutex slots_lock;
    struct mutex slots_arch_lock;
    struct mm_struct * mm;
    long unsigned int nr_memslot_pages;
    struct kvm_memslots[4] __memslots;
    struct kvm_memslots *[2] memslots;
    struct xarray vcpu_array;
    atomic_t nr_memslots_dirty_logging;
    spinlock_t mn_invalidate_lock;
    long unsigned int mn_active_invalidate_count;
    struct rcuwait mn_memslots_update_rcuwait;
    spinlock_t gpc_lock;
    struct list_head gpc_list;
    atomic_t online_vcpus;
    int max_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_invalidate_seq;
    long int mmu_invalidate_in_progress;
    gfn_t mmu_invalidate_range_start;
    gfn_t mmu_invalidate_range_end;
    struct list_head devices;
    u64 manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
    bool override_halt_poll_ns;
    unsigned int max_halt_poll_ns;
    u32 dirty_ring_size;
    bool dirty_ring_with_bitmap;
    bool vm_bugged;
    bool vm_dead;
    struct notifier_block pm_notifier;
    struct xarray mem_attr_array;
    char[48] stats_id;
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
struct kvm {
    spinlock_t mmu_lock;
    struct mutex slots_lock;
    struct mm_struct * mm;
    struct kvm_memslots *[1] memslots;
    struct kvm_vcpu *[512] vcpus;
    atomic_t online_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long int tlbs_dirty;
    struct list_head devices;
    bool manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
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
struct kvm {
    spinlock_t mmu_lock;
    struct mutex slots_lock;
    struct mm_struct * mm;
    struct kvm_memslots *[1] memslots;
    struct kvm_vcpu *[2048] vcpus;
    atomic_t online_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long int tlbs_dirty;
    struct list_head devices;
    bool manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
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
struct kvm {
    spinlock_t mmu_lock;
    struct mutex slots_lock;
    struct mm_struct * mm;
    struct kvm_memslots *[2] memslots;
    struct kvm_vcpu *[288] vcpus;
    atomic_t online_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long int tlbs_dirty;
    struct list_head devices;
    u64 manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
    unsigned int max_halt_poll_ns;
    u32 dirty_ring_size;
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
<code>long unsigned int mmu_notifier_range_start</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int mmu_notifier_range_end</code>
</li>
<li>
<b>Field type changed. </b>
<code>spinlock_t mmu_lock</code> ➡️ <code>rwlock_t mmu_lock</code>
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
<code>struct mutex slots_arch_lock</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t mn_invalidate_lock</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int mn_active_invalidate_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct rcuwait mn_memslots_update_rcuwait</code>
</li>
<li>
<b>Field added. </b>
<code>bool vm_bugged</code>
</li>
<li>
<b>Field added. </b>
<code>struct notifier_block pm_notifier</code>
</li>
<li>
<b>Field added. </b>
<code>char[48] stats_id</code>
</li>
<li>
<b>Field removed. </b>
<code>long int tlbs_dirty</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct kvm_vcpu *[288] vcpus</code> ➡️ <code>struct kvm_vcpu *[1024] vcpus</code>
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
<code>long unsigned int nr_memslot_pages</code>
</li>
<li>
<b>Field added. </b>
<code>struct kvm_memslots[4] __memslots</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray vcpu_array</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t gpc_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head gpc_list</code>
</li>
<li>
<b>Field added. </b>
<code>int max_vcpus</code>
</li>
<li>
<b>Field added. </b>
<code>bool vm_dead</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kvm_vcpu *[1024] vcpus</code>
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
<code>atomic_t nr_memslots_dirty_logging</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int mmu_invalidate_seq</code>
</li>
<li>
<b>Field added. </b>
<code>long int mmu_invalidate_in_progress</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int mmu_invalidate_range_start</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int mmu_invalidate_range_end</code>
</li>
<li>
<b>Field added. </b>
<code>bool override_halt_poll_ns</code>
</li>
<li>
<b>Field added. </b>
<code>bool dirty_ring_with_bitmap</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int mmu_notifier_seq</code>
</li>
<li>
<b>Field removed. </b>
<code>long int mmu_notifier_count</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int mmu_notifier_range_start</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int mmu_notifier_range_end</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct xarray mem_attr_array</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int mmu_invalidate_range_start</code> ➡️ <code>gfn_t mmu_invalidate_range_start</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int mmu_invalidate_range_end</code> ➡️ <code>gfn_t mmu_invalidate_range_end</code>
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
struct kvm {
    spinlock_t mmu_lock;
    struct mutex slots_lock;
    struct mm_struct * mm;
    struct kvm_memslots *[1] memslots;
    struct kvm_vcpu *[512] vcpus;
    atomic_t online_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long int tlbs_dirty;
    struct list_head devices;
    bool manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvm {
    spinlock_t mmu_lock;
    struct mutex slots_lock;
    struct mm_struct * mm;
    struct kvm_memslots *[1] memslots;
    struct kvm_vcpu *[2048] vcpus;
    atomic_t online_vcpus;
    int created_vcpus;
    int last_boosted_vcpu;
    struct list_head vm_list;
    struct mutex lock;
    struct kvm_io_bus *[4] buses;
    struct (anon) irqfds;
    struct list_head ioeventfds;
    struct kvm_vm_stat stat;
    struct kvm_arch arch;
    refcount_t users_count;
    struct kvm_coalesced_mmio_ring * coalesced_mmio_ring;
    spinlock_t ring_lock;
    struct list_head coalesced_zones;
    struct mutex irq_lock;
    struct kvm_irq_routing_table * irq_routing;
    struct hlist_head irq_ack_notifier_list;
    struct mmu_notifier mmu_notifier;
    long unsigned int mmu_notifier_seq;
    long int mmu_notifier_count;
    long int tlbs_dirty;
    struct list_head devices;
    bool manual_dirty_log_protect;
    struct dentry * debugfs_dentry;
    struct kvm_stat_data * * debugfs_stat_data;
    struct srcu_struct srcu;
    struct srcu_struct irq_srcu;
    pid_t userspace_pid;
}
```
</details>
</li>
</ul>
