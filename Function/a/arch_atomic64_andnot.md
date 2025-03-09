# Function: <code>arch_atomic64_andnot</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591205741,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic-arch-fallback.h:1759",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579953508,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic-arch-fallback.h:1759",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591700941,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic-arch-fallback.h:1829",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579942180,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic-arch-fallback.h:1829",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585179357,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic-arch-fallback.h:1829",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_resize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591642618,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic-arch-fallback.h:1829",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579949316,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic-arch-fallback.h:1829",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585059633,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic-arch-fallback.h:1829",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_resize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592816498,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1829",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580078588,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1829",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585506462,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1829",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:__sbitmap_get",
        "lib/sbitmap.c:sbitmap_resize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594720182,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1927",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580214579,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1927",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586658918,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1927",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_clear_batch",
        "lib/sbitmap.c:sbitmap_queue_clear_batch",
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:__sbitmap_get",
        "lib/sbitmap.c:sbitmap_resize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic64_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596470403,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1927",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580407083,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1927",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587906550,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "include/linux/atomic/atomic-arch-fallback.h:1927",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_clear_batch",
        "lib/sbitmap.c:sbitmap_queue_clear_batch",
        "lib/sbitmap.c:__sbitmap_queue_get_batch",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:__sbitmap_get",
        "lib/sbitmap.c:sbitmap_resize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void arch_atomic64_andnot(long int i, atomic64_t * v)
```

```json
{
  "name": "arch_atomic64_andnot",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490180536,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/debug-monitors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/debug-monitors.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490189192,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread",
        "arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch",
        "arch/arm64/kernel/fpsimd.c:sve_set_vector_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490195068,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:set_tagged_addr_ctrl",
        "arch/arm64/kernel/process.c:arch_dup_task_struct",
        "arch/arm64/kernel/process.c:flush_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490210608,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:sve_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490234520,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:restore_fpsimd_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490275188,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:smp_send_stop"
      ],
      "caller_func": [
        "arch/arm64/kernel/smp.c:crash_smp_send_stop",
        "arch/arm64/kernel/smp.c:cpu_die_early"
      ]
    },
    {
      "addr": 18446603336490277676,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/syscall.c:el0_svc_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490305412,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/perf_event.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/perf_event.c:armv8pmu_clear_event_idx",
        "arch/arm64/kernel/perf_event.c:armv8pmu_clear_event_idx",
        "arch/arm64/kernel/perf_event.c:armv8pmu_get_event_idx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490336212,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kernel/ssbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set",
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490343384,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/mm/flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/flush.c:flush_dcache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490361188,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:numa_update_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490388208,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:hardware_disable_nolock",
        "virt/kvm/kvm_main.c:hardware_enable_nolock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490446684,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run",
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490476128,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "virt/kvm/arm/psci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/psci.c:kvm_psci_0_2_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490489096,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kvm/handle_exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/handle_exit.c:kvm_handle_wfx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490528240,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "arch/arm64/kvm/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp",
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp",
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490611268,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "virt/kvm/arm/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/pmu.c:kvm_pmu_set_counter_event_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490633788,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446603336490653856,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490658908,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490674640,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/softirq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490718596,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490748952,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490788008,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_prctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490801408,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_calc_node_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490845348,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490931148,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490974608,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491008704,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:rq_offline_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491019236,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491048812,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491051064,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/sched/cpudeadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpudeadline.c:cpudl_clear_freecpu",
        "kernel/sched/cpudeadline.c:cpudl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491061344,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:sched_domains_numa_masks_clear",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503931896,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491112528,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491193676,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/irq/resend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/resend.c:resend_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491202604,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_percpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491209712,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_unmap_generic_chip"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491237004,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/irq/affinity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/affinity.c:__irq_build_affinity_masks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491305220,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:profile_dead_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410912,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot",
        "kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control",
        "kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_offline",
        "kernel/time/tick-broadcast.c:tick_broadcast_control",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast",
        "kernel/time/tick-broadcast.c:tick_device_uses_broadcast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491506412,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "kernel/kexec_core.c:kimage_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491577168,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491586456,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_do_freeze",
        "kernel/cgroup/freezer.c:cgroup_update_frozen",
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491611424,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:update_flag",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag",
        "kernel/cgroup/cpuset.c:cpuset_update_task_spread_flag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491629296,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491669652,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491758812,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491789720,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491876416,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_filter_add_remove_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491971088,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:event_enable_count_probe",
        "kernel/trace/trace_events.c:event_enable_probe",
        "kernel/trace/trace_events.c:__ftrace_clear_event_pids",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:trace_event_enable_tgid_record",
        "kernel/trace/trace_events.c:trace_event_enable_cmd_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491979932,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/trace/trace_syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491999732,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger",
        "kernel/trace/trace_events_trigger.c:update_cond_flag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492340140,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_cpu_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492392388,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492416908,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:xol_free_insn_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492426560,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_remove_cpu",
        "kernel/padata.c:padata_remove_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492459228,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:wake_up_page_bit",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:file_check_and_advance_wb_err",
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492484580,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492508856,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492513676,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492519584,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/swap.c:lru_cache_add_anon",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:mark_page_accessed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492530300,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_cleanup_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492574624,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:node_reclaim",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:reclaim_clean_pages_from_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492593852,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_lock",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492629792,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492715568,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:undo_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492767092,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492814552,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492882900,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:drain_all_pages",
        "mm/page_alloc.c:__free_pages_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492903424,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492910220,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:__swap_writepage"
      ],
      "caller_func": [
        "mm/page_io.c:end_swap_bio_read",
        "mm/page_io.c:end_swap_bio_write"
      ]
    },
    {
      "addr": 18446603336492913616,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492950716,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_page",
        "mm/frontswap.c:__frontswap_load",
        "mm/frontswap.c:__frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492998668,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:__free_huge_page",
        "mm/hugetlb.c:__free_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493004520,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493026200,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_remove_section"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493038488,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:run_store",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:ksm_scan_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493096464,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__online_page_free",
        "mm/memory_hotplug.c:put_page_bootmem",
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493111100,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493124012,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:defrag_store",
        "mm/huge_memory.c:single_hugepage_flag_store",
        "mm/huge_memory.c:enabled_store",
        "mm/huge_memory.c:enabled_store",
        "mm/huge_memory.c:enabled_store",
        "mm/huge_memory.c:enabled_store"
      ],
      "caller_func": [
        "mm/huge_memory.c:setup_transparent_hugepage",
        "mm/huge_memory.c:setup_transparent_hugepage",
        "mm/huge_memory.c:setup_transparent_hugepage",
        "mm/huge_memory.c:setup_transparent_hugepage"
      ]
    },
    {
      "addr": 18446603336493159592,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__khugepaged_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493217712,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493229976,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493253792,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:reset_page",
        "mm/zsmalloc.c:reset_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493271256,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493274836,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493609668,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493674320,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bforget",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:__end_buffer_read_notouch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493722344,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493869780,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493953316,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493993192,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494002416,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494024432,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:dquot_set_dqblk",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:dquot_decr_space",
        "fs/quota/dquot.c:dquot_decr_inodes",
        "fs/quota/dquot.c:dquot_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494066260,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494083184,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_coredump_filter_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494219084,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494231684,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494238608,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494284884,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_clear_inode_es"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494289384,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494295732,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/fsync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsync.c:ext4_sync_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494336984,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data",
        "fs/ext4/inline.c:ext4_delete_inline_entry",
        "fs/ext4/inline.c:ext4_try_add_inline_entry",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_prepare_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494388000,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_expand_extra_isize",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:__ext4_journalled_invalidatepage",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_update_inode",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    },
    {
      "addr": 18446603336494394328,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494442360,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494451648,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/migrate.c:ext4_ind_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494452760,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:read_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494488224,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_rename",
        "fs/ext4/namei.c:ext4_symlink",
        "fs/ext4/namei.c:ext4_mkdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494497344,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494499524,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494583752,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_set_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494636800,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494647320,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494662672,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:__jbd2_journal_temp_unlink_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494671568,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    },
    {
      "addr": 18446603336494688088,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_clear_buffer_revoked_flags",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke",
        "fs/jbd2/revoke.c:jbd2_journal_cancel_revoke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494714440,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    },
    {
      "addr": 18446603336494750512,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_huge_page",
        "fs/hugetlbfs/inode.c:remove_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494832208,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_readpage",
        "fs/ecryptfs/mmap.c:ecryptfs_writepage"
      ],
      "caller_func": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin"
      ]
    },
    {
      "addr": 18446603336494885692,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:end_requests",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_request_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494912812,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_do_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494934296,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_perform_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495060980,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/gc.c:key_garbage_collector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495383464,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495585780,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "security/integrity/ima/ima_fs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_fs.c:ima_release_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495614880,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "security/integrity/ima/ima_appraise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_appraise.c:ima_inode_post_setattr",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495620488,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "security/integrity/evm/evm_crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495795392,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_queue_flag_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495854784,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:dispatch_rq_from_ctx",
        "block/blk-mq.c:flush_busy_ctx"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495885140,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496348184,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:irq_poll_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496397868,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496411164,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/irqchip/irq-bcm7038-l1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511086140,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/irqchip/irq-imx-gpcv2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496425648,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/irqchip/irq-mvebu-sei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_release_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496430748,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/irqchip/qcom-irq-combiner.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/qcom-irq-combiner.c:combiner_irq_chip_mask_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496433176,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/irqchip/irq-meson-gpio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_free",
        "drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496441728,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/irqchip/irq-ti-sci-inta.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_release_resources",
        "drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_request_resources"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496595544,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pinctrl/bcm/pinctrl-bcm2835.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496640044,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pinctrl/qcom/pinctrl-msm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_mask",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496710408,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_disable_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiochip_unlock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiod_get_direction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496748416,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-sysfs.c:active_low_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496794480,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/gpio/gpio-stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-stmpe.c:stmpe_init_irq_valid_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496815456,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pwm/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pwm/sysfs.c:export_store",
        "drivers/pwm/sysfs.c:export_store"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496846400,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pci/remove.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_bus_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497081300,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pci/endpoint/pci-ep-cfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_unlink",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497094708,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pci/controller/pcie-cadence-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_unmap_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497108620,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pci/controller/pcie-rcar.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rcar.c:rcar_msi_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497116432,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pci/controller/pcie-xilinx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497140232,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pci/controller/pcie-rockchip-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497166024,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/pci/controller/dwc/pcie-designware-ep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_unmap_addr",
        "drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_clear_bar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497435844,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/acpi/ec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:advance_transaction"
      ],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_stop"
      ]
    },
    {
      "addr": 18446603336497652260,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497658892,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/acpi/battery.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497778352,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clk/clk-fixed-factor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511149320,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clk/hisilicon/clk-hi3660.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/hisilicon/clk-hi3660.c:hi3660_clk_crgctrl_of_clk_init_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497828452,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clk/hisilicon/clk-hi6220.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_media_of_clk_init_driver",
        "drivers/clk/hisilicon/clk-hi6220.c:hi6220_clk_sys_of_clk_init_driver"
      ]
    },
    {
      "addr": 18446603336511151548,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clk/mediatek/clk-mt6797.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-mt6797.c:mtk_infra_of_clk_init_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511151972,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clk/mediatek/clk-mt2712.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-mt2712.c:mt2712_topckgen_of_clk_init_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511154432,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clk/mediatek/clk-mt8183.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/mediatek/clk-mt8183.c:mt8183_topckgen_of_clk_init_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511180068,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clk/sunxi/clk-mod0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-mod0.c:sun4i_a10_mod0_of_clk_init_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511186140,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clk/sunxi/clk-sun8i-apb0.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_of_clk_init_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498010108,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_release_channel",
        "drivers/dma/dmaengine.c:dma_get_slave_channel",
        "drivers/dma/dmaengine.c:find_candidate"
      ],
      "caller_func": [
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init",
        "drivers/dma/dmaengine.c:dma_channel_table_init"
      ]
    },
    {
      "addr": 18446603336498112956,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498135236,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/soc/qcom/rpmh-rsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/qcom/rpmh-rsc.c:tcs_tx_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498198040,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/xen/cpu_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/cpu_hotplug.c:setup_cpu_watcher",
        "drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498203336,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_pages_clear_private"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498212356,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:balloon_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498228576,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_unmask",
        "drivers/xen/events/events_2l.c:evtchn_2l_clear_pending",
        "drivers/xen/events/events_2l.c:evtchn_2l_bind_to_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498233216,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/events/events_fifo.c:evtchn_fifo_clear_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498358788,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kclose"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498375548,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_read",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/tty/n_tty.c:n_tty_set_termios",
        "drivers/tty/n_tty.c:n_tty_write_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498396100,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/tty_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ioctl.c:tty_unthrottle_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498399220,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_unlock",
        "drivers/tty/tty_ldisc.c:tty_ldisc_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498409216,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/tty_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_port.c:tty_port_open",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498420368,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/pty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/pty.c:pty_open",
        "drivers/tty/pty.c:pty_open",
        "drivers/tty/pty.c:pty_set_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498432092,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:sysrq_filter",
        "drivers/tty/sysrq.c:sysrq_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498462320,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498548664,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_resume_port",
        "drivers/tty/serial/serial_core.c:uart_suspend_port",
        "drivers/tty/serial/serial_core.c:uart_hangup",
        "drivers/tty/serial/serial_core.c:uart_tty_port_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498648188,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/serial/max310x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/max310x.c:max310x_spi_remove",
        "drivers/tty/serial/max310x.c:max310x_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498718528,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/tty/serdev/serdev-ttyport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498750984,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/char/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/misc.c:misc_deregister",
        "drivers/char/misc.c:misc_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498778176,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/char/tpm/tpm-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev.c:tpm_release",
        "drivers/char/tpm/tpm-dev.c:tpm_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498810908,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498877808,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/iommu/arm-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu.c:arm_smmu_attach_dev",
        "drivers/iommu/arm-smmu.c:arm_smmu_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498889780,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/iommu/arm-smmu-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_finalise_s1",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_free",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498940944,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499020548,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/base/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499108392,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499202056,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/base/arch_topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/arch_topology.c:remove_cpu_topology",
        "drivers/base/arch_topology.c:remove_cpu_topology",
        "drivers/base/arch_topology.c:remove_cpu_topology"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499414520,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/dimm_devs.c:nvdimm_clear_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499451764,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_write_index",
        "drivers/nvdimm/label.c:nd_label_alloc_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499469528,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/nvdimm/security.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499476368,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:dax_write_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499564732,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499589304,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/scsi/scsi_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_lun_change_reported",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_mode_parameter_change_reported",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_soft_threshold_reached",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_capacity_change_reported",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_inquiry_change_reported",
        "drivers/scsi/scsi_sysfs.c:sdev_store_evt_media_change"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499646040,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_kref_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499752100,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_sas_free_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499871768,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_unregister_device"
      ],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    },
    {
      "addr": 18446603336499967404,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500004684,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500029436,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_resume",
        "drivers/net/ethernet/freescale/fec_main.c:fec_suspend",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500096324,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/net/ethernet/smsc/smc91x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500149304,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_create_queues",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:xennet_open",
        "drivers/net/xen-netfront.c:xennet_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500220572,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:port_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_reset",
        "drivers/usb/core/hub.c:hub_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500244612,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:hcd_bus_resume",
        "drivers/usb/core/hcd.c:hcd_bus_suspend",
        "drivers/usb/core/hcd.c:usb_hcd_poll_rh_status"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ]
    },
    {
      "addr": 18446603336500295072,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/core/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/sysfs.c:interface_authorized_default_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500301088,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:driver_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500387344,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500500200,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:companion_store"
      ],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_hcd_cleanup",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_hub_control",
        "drivers/usb/host/ehci-hcd.c:ehci_bus_resume"
      ]
    },
    {
      "addr": 18446603336500533908,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_hub_status_data"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_hcd_mod_exit"
      ]
    },
    {
      "addr": 18446603336500554548,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:suspend_rh",
        "drivers/usb/host/uhci-hcd.c:finish_reset",
        "drivers/usb/host/uhci-hcd.c:uhci_hub_control",
        "drivers/usb/host/uhci-hcd.c:uhci_finish_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init"
      ]
    },
    {
      "addr": 18446603336500578124,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500669952,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status"
      ]
    },
    {
      "addr": 18446603336500759984,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/input/mousedev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/mousedev.c:mousedev_event",
        "drivers/input/mousedev.c:mousedev_event",
        "drivers/input/mousedev.c:mousedev_event",
        "drivers/input/mousedev.c:mousedev_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500829720,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/rtc/rtc-sun6i.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-sun6i.c:sun8i_v3_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun8i_r40_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun50i_h6_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun8i_h3_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun8i_a23_rtc_clk_of_clk_init_driver",
        "drivers/rtc/rtc-sun6i.c:sun6i_a31_rtc_clk_of_clk_init_driver"
      ]
    },
    {
      "addr": 18446603336500839076,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500866704,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/i2c/i2c-core-of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-of.c:of_i2c_register_devices"
      ]
    },
    {
      "addr": 18446603336500890044,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/i2c/busses/i2c-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_resume_noirq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500896032,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/media/cec/cec-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-core.c:cec_devnode_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501033832,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/watchdog/watchdog_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_open",
        "drivers/watchdog/watchdog_dev.c:watchdog_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501074568,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_reap_sync_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:recovery_start_store",
        "drivers/md/md.c:super_written"
      ],
      "caller_func": [
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:remove_and_add_spares",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:add_new_disk",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_1_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_90_validate",
        "drivers/md/md.c:super_90_validate"
      ]
    },
    {
      "addr": 18446603336501140388,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501153708,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_queue_flush",
        "drivers/md/dm.c:dm_cancel_deferred_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501214788,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501296856,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_remove_dev",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501464416,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "drivers/leds/led-core.c:led_timer_function",
        "drivers/leds/led-core.c:led_timer_function"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501500276,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/firmware/ti_sci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/ti_sci.c:ti_sci_release_resource"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501520332,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511280816,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efisubsys_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511285484,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501590168,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/clocksource/arm_arch_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501615448,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/of/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_bus_create",
        "drivers/of/platform.c:of_platform_device_create_pdata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501626924,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/of/dynamic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/dynamic.c:__of_attach_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511308196,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/of/irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/irq.c:of_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501761284,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501769788,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501782752,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/perf/hisilicon/hisi_uncore_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501795736,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_del",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_event_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501805668,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/xgene_pmu.c:xgene_perf_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501871560,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501941744,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_write_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501998396,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:napi_disable",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:__dev_close_many",
        "net/core/dev.c:__dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502164172,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/core/link_watch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/link_watch.c:__linkwatch_run_queue",
        "net/core/link_watch.c:linkwatch_do_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502280272,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502284420,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502414712,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502452484,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/sched/sch_generic.c:dev_watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502531812,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502551920,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_unregister_family"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502692156,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502768972,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_tasklet_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503084156,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503206972,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503749864,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/ncsi/ncsi-rsp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503765356,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_configure_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503888000,
      "name": "arch_atomic64_andnot",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:64",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490270232,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336490620680,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336492908192,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336493122088,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494341488,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494668192,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494695120,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336494831840,
      "name": "arch_atomic64_andnot.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336497432640,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336497828452,
      "name": "arch_atomic64_andnot.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336498008352,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336499871440,
      "name": "arch_atomic64_andnot.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336500232472,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336500464976,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336500512400,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336500548896,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336500655704,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336500829720,
      "name": "arch_atomic64_andnot.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336500866704,
      "name": "arch_atomic64_andnot.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336501061792,
      "name": "arch_atomic64_andnot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void arch_atomic64_andnot(long int i, atomic64_t * v)
```
</details>
</li>
</ul>
