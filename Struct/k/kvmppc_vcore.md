# Struct: <code>kvmppc_vcore</code>

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
struct kvmppc_vcore {
    int n_runnable;
    int num_threads;
    int entry_exit_map;
    int napping_threads;
    int first_vcpuid;
    u16 pcpu;
    u16 last_cpu;
    u8 vcore_state;
    u8 in_guest;
    struct kvm_vcpu *[8] runnable_threads;
    struct list_head preempt_list;
    spinlock_t lock;
    struct swait_queue_head wq;
    spinlock_t stoltb_lock;
    u64 stolen_tb;
    u64 preempt_tb;
    struct kvm_vcpu * runner;
    struct kvm * kvm;
    u64 tb_offset;
    u64 tb_offset_applied;
    ulong lpcr;
    u32 arch_compat;
    ulong pcr;
    ulong dpdes;
    ulong vtb;
    ulong conferring_threads;
    unsigned int halt_poll_ns;
    atomic_t online_count;
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
struct kvmppc_vcore {
    int n_runnable;
    int num_threads;
    int entry_exit_map;
    int napping_threads;
    int first_vcpuid;
    u16 pcpu;
    u16 last_cpu;
    u8 vcore_state;
    u8 in_guest;
    struct kvm_vcpu *[8] runnable_threads;
    struct list_head preempt_list;
    spinlock_t lock;
    struct swait_queue_head wq;
    spinlock_t stoltb_lock;
    u64 stolen_tb;
    u64 preempt_tb;
    struct kvm_vcpu * runner;
    struct kvm * kvm;
    u64 tb_offset;
    u64 tb_offset_applied;
    ulong lpcr;
    u32 arch_compat;
    ulong pcr;
    ulong dpdes;
    ulong vtb;
    ulong conferring_threads;
    unsigned int halt_poll_ns;
    atomic_t online_count;
}
```
</details>
</li>
</ul>
