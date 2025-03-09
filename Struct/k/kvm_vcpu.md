# Struct: <code>kvm_vcpu</code>

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
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int vcpu_idx;
    int srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    int pre_pcpu;
    struct list_head blocked_vcpu_list;
    struct mutex mutex;
    struct kvm_run * run;
    struct rcuwait wait;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    struct kvm_vcpu_stat stat;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) async_pf;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct kvm_dirty_ring dirty_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int vcpu_idx;
    int srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    int pre_pcpu;
    struct list_head blocked_vcpu_list;
    struct mutex mutex;
    struct kvm_run * run;
    struct rcuwait wait;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    struct kvm_vcpu_stat stat;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) async_pf;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct kvm_dirty_ring dirty_ring;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int vcpu_idx;
    int srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    int pre_pcpu;
    struct list_head blocked_vcpu_list;
    struct mutex mutex;
    struct kvm_run * run;
    struct rcuwait wait;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) async_pf;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct kvm_vcpu_stat stat;
    char[48] stats_id;
    struct kvm_dirty_ring dirty_ring;
    int last_used_slot;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int vcpu_idx;
    int ____srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    struct mutex mutex;
    struct kvm_run * run;
    struct rcuwait wait;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) async_pf;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct kvm_vcpu_stat stat;
    char[48] stats_id;
    struct kvm_dirty_ring dirty_ring;
    struct kvm_memory_slot * last_used_slot;
    u64 last_used_slot_gen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int vcpu_idx;
    int ____srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    struct mutex mutex;
    struct kvm_run * run;
    struct rcuwait wait;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) async_pf;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct kvm_vcpu_stat stat;
    char[48] stats_id;
    struct kvm_dirty_ring dirty_ring;
    struct kvm_memory_slot * last_used_slot;
    u64 last_used_slot_gen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int vcpu_idx;
    int ____srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    struct mutex mutex;
    struct kvm_run * run;
    struct rcuwait wait;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) async_pf;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct kvm_vcpu_stat stat;
    char[48] stats_id;
    struct kvm_dirty_ring dirty_ring;
    struct kvm_memory_slot * last_used_slot;
    u64 last_used_slot_gen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int vcpu_idx;
    int ____srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    struct mutex mutex;
    struct kvm_run * run;
    struct rcuwait wait;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) async_pf;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct kvm_vcpu_stat stat;
    char[48] stats_id;
    struct kvm_dirty_ring dirty_ring;
    struct kvm_memory_slot * last_used_slot;
    u64 last_used_slot_gen;
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
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    int pre_pcpu;
    struct list_head blocked_vcpu_list;
    struct mutex mutex;
    struct kvm_run * run;
    int guest_xcr0_loaded;
    struct swait_queue_head wq;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    struct kvm_vcpu_stat stat;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct dentry * debugfs_dentry;
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
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    int pre_pcpu;
    struct list_head blocked_vcpu_list;
    struct mutex mutex;
    struct kvm_run * run;
    int guest_xcr0_loaded;
    struct swait_queue_head wq;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    struct kvm_vcpu_stat stat;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct dentry * debugfs_dentry;
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
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int vcpu_idx;
    int srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    int pre_pcpu;
    struct list_head blocked_vcpu_list;
    struct mutex mutex;
    struct kvm_run * run;
    struct rcuwait wait;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    struct kvm_vcpu_stat stat;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) async_pf;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct kvm_dirty_ring dirty_ring;
}
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>char[48] stats_id</code>
</li>
<li>
<b>Field added. </b>
<code>int last_used_slot</code>
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
<code>int ____srcu_idx</code>
</li>
<li>
<b>Field added. </b>
<code>u64 last_used_slot_gen</code>
</li>
<li>
<b>Field removed. </b>
<code>int srcu_idx</code>
</li>
<li>
<b>Field removed. </b>
<code>int pre_pcpu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head blocked_vcpu_list</code>
</li>
<li>
<b>Field type changed. </b>
<code>int last_used_slot</code> ➡️ <code>struct kvm_memory_slot * last_used_slot</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    int pre_pcpu;
    struct list_head blocked_vcpu_list;
    struct mutex mutex;
    struct kvm_run * run;
    int guest_xcr0_loaded;
    struct swait_queue_head wq;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    struct kvm_vcpu_stat stat;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    struct (anon) spin_loop;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct dentry * debugfs_dentry;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct kvm_vcpu {
    struct kvm * kvm;
    struct preempt_notifier preempt_notifier;
    int cpu;
    int vcpu_id;
    int srcu_idx;
    int mode;
    u64 requests;
    long unsigned int guest_debug;
    int pre_pcpu;
    struct list_head blocked_vcpu_list;
    struct mutex mutex;
    struct kvm_run * run;
    int guest_xcr0_loaded;
    struct swait_queue_head wq;
    struct pid * pid;
    int sigset_active;
    sigset_t sigset;
    struct kvm_vcpu_stat stat;
    unsigned int halt_poll_ns;
    bool valid_wakeup;
    int mmio_needed;
    int mmio_read_completed;
    int mmio_is_write;
    int mmio_cur_fragment;
    int mmio_nr_fragments;
    struct kvm_mmio_fragment[2] mmio_fragments;
    bool preempted;
    bool ready;
    struct kvm_vcpu_arch arch;
    struct dentry * debugfs_dentry;
}
```
</details>
</li>
</ul>
