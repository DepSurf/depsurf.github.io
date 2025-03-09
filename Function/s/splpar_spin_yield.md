# Function: <code>splpar_spin_yield</code>

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
void splpar_spin_yield(arch_spinlock_t * lock)
```

```json
{
  "name": "splpar_spin_yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282900880,
      "name": "splpar_spin_yield",
      "external": true,
      "loc": "arch/powerpc/lib/locks.c:21",
      "file": "arch/powerpc/lib/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:oops_begin",
        "arch/powerpc/kernel/rtas.c:rtas_take_timebase",
        "arch/powerpc/kernel/rtas.c:rtas_give_timebase",
        "arch/powerpc/kernel/rtas.c:__se_sys_rtas",
        "arch/powerpc/kernel/rtas.c:rtas_call",
        "arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_deliver_irq",
        "arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_eoi",
        "kernel/locking/spinlock.c:_raw_spin_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_spin_lock_irq",
        "kernel/locking/spinlock.c:_raw_spin_lock_bh",
        "kernel/locking/spinlock.c:_raw_spin_lock",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/ring_buffer.c:ring_buffer_free_read_page",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_write",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:saved_cmdlines_start",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:trace_find_cmdline",
        "kernel/trace/trace.c:tracing_stop",
        "kernel/trace/trace.c:tracing_snapshot_cond_disable",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace.c:tracing_cond_snapshot_data",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:wakeup_reset",
        "kernel/trace/trace_stack.c:t_start",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_stack.c:stack_trace_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282900880,
      "name": "splpar_spin_yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
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
void splpar_spin_yield(arch_spinlock_t * lock)
```
</details>
</li>
</ul>
