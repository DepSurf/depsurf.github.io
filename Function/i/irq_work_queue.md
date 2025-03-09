# Function: <code>irq_work_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580356352,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:87",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "kernel/printk/printk.c:printk_deferred",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "kernel/events/ring_buffer.c:ring_buffer_put_async",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:rb_free_aux",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356352,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580411376,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:87",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log",
        "kernel/printk/printk.c:printk_deferred",
        "kernel/printk/printk.c:console_unlock",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411376,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580459520,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:87",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log",
        "kernel/printk/printk.c:printk_deferred",
        "kernel/printk/printk.c:console_unlock",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459520,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580470544,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:87",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_commit",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:console_unlock",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470544,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580526368,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:90",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_commit",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:console_unlock",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526368,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580615008,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:90",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615008,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580673904,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:90",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580673904,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580738416,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/nmi.c:nmi_handle",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738416,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580789136,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789136,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580906464,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:67",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_end",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906464,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580901200,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:67",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_end",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901200,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580905024,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:67",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_end",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905024,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581107216,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:67",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:printk_trigger_flush",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_end",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107216,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581373488,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:106",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/irq/irq_sim.c:irq_sim_set_irqchip_state",
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/pid_list.c:trace_pid_list_set",
        "kernel/trace/pid_list.c:trace_pid_list_set",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373488,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581721248,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:106",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/irq/irq_sim.c:irq_sim_set_irqchip_state",
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/pid_list.c:trace_pid_list_set",
        "kernel/trace/pid_list.c:trace_pid_list_set",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit",
        "kernel/bpf/memalloc.c:unit_free",
        "kernel/bpf/memalloc.c:unit_alloc",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721248,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581880032,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:116",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/irq/irq_sim.c:irq_sim_set_irqchip_state",
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/pid_list.c:trace_pid_list_set",
        "kernel/trace/pid_list.c:trace_pid_list_set",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit",
        "kernel/bpf/memalloc.c:unit_free",
        "kernel/bpf/memalloc.c:unit_alloc",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581880032,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582003088,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:116",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "kernel/sched/build_utility.c:sugov_update_shared",
        "kernel/sched/build_utility.c:sugov_update_single_freq",
        "kernel/irq/irq_sim.c:irq_sim_set_irqchip_state",
        "kernel/rcu/update.c:call_rcu_tasks_generic",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wake_waiters",
        "kernel/trace/trace.c:__update_max_tr",
        "kernel/trace/pid_list.c:trace_pid_list_set",
        "kernel/trace/pid_list.c:trace_pid_list_set",
        "kernel/trace/bpf_trace.c:bpf_send_signal_common",
        "kernel/bpf/task_iter.c:bpf_iter_task_vma_destroy",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_discard",
        "kernel/bpf/ringbuf.c:bpf_ringbuf_submit",
        "kernel/bpf/memalloc.c:unit_free_rcu",
        "kernel/bpf/memalloc.c:unit_free",
        "kernel/bpf/memalloc.c:unit_alloc",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003088,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492102032,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_event_disable_inatomic",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/acpi/apei/ghes.c:ghes_sdei_critical_callback",
        "drivers/acpi/apei/ghes.c:ghes_sdei_normal_callback",
        "drivers/acpi/apei/ghes.c:ghes_notify_sea",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492102032,
      "name": "irq_work_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226002096,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226002096,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285304848,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/mce.c:machine_check_queue_event",
        "arch/powerpc/kernel/mce.c:save_mce_event",
        "arch/powerpc/platforms/pseries/ras.c:pseries_machine_check_realmode",
        "arch/powerpc/platforms/pseries/ras.c:pseries_machine_check_realmode",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285304848,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272277940,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272277940,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580757936,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757936,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580704112,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704112,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580749184,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:vprintk_deferred",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749184,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool irq_work_queue(struct irq_work * work)
```

```json
{
  "name": "irq_work_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580807232,
      "name": "irq_work_queue",
      "external": true,
      "loc": "kernel/irq_work.c:75",
      "file": "kernel/irq_work.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_log",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single",
        "kernel/printk/printk.c:defer_console_output",
        "kernel/printk/printk.c:wake_up_klogd",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/relay.c:relay_switch_subbuf",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/bpf_trace.c:bpf_send_signal",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_sample_event_took",
        "kernel/events/ring_buffer.c:perf_aux_output_skip",
        "kernel/events/ring_buffer.c:perf_aux_output_end",
        "kernel/events/ring_buffer.c:perf_aux_output_begin",
        "kernel/events/ring_buffer.c:perf_output_put_handle",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb",
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807232,
      "name": "irq_work_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
