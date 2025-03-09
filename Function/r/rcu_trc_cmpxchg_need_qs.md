# Function: <code>rcu_trc_cmpxchg_need_qs</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 rcu_trc_cmpxchg_need_qs(struct task_struct * t, u8 old, u8 new)
```

```json
{
  "name": "rcu_trc_cmpxchg_need_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580597674,
      "name": "rcu_trc_cmpxchg_need_qs",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1255",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:rcu_read_unlock_trace_special"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:trc_read_check_handler",
        "kernel/rcu/update.c:trc_read_check_handler",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:kfree_rcu_work",
        "kernel/rcu/tree.c:kfree_rcu_work",
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585008,
      "name": "rcu_trc_cmpxchg_need_qs",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 rcu_trc_cmpxchg_need_qs(struct task_struct * t, u8 old, u8 new)
```

```json
{
  "name": "rcu_trc_cmpxchg_need_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580671178,
      "name": "rcu_trc_cmpxchg_need_qs",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1292",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:rcu_read_unlock_trace_special"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:trc_read_check_handler",
        "kernel/rcu/update.c:trc_read_check_handler",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:kvfree_rcu_list",
        "kernel/rcu/tree.c:kvfree_rcu_bulk",
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/trace/trace_osnoise.c:osnoise_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580658048,
      "name": "rcu_trc_cmpxchg_need_qs",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
u8 rcu_trc_cmpxchg_need_qs(struct task_struct * t, u8 old, u8 new)
```

```json
{
  "name": "rcu_trc_cmpxchg_need_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580738026,
      "name": "rcu_trc_cmpxchg_need_qs",
      "external": true,
      "loc": "kernel/rcu/tasks.h:1408",
      "file": "kernel/rcu/update.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:rcu_read_unlock_trace_special"
      ],
      "caller_func": [
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:check_all_holdout_tasks_trace",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:rcu_tasks_trace_pregp_step",
        "kernel/rcu/update.c:trc_inspect_reader",
        "kernel/rcu/update.c:trc_read_check_handler",
        "kernel/rcu/update.c:trc_read_check_handler",
        "kernel/rcu/update.c:exit_tasks_rcu_finish",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:rcu_nocb_gp_kthread",
        "kernel/rcu/tree.c:kvfree_rcu_list",
        "kernel/rcu/tree.c:kvfree_rcu_bulk",
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_softirq_qs",
        "kernel/trace/trace_osnoise.c:osnoise_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580723472,
      "name": "rcu_trc_cmpxchg_need_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
u8 rcu_trc_cmpxchg_need_qs(struct task_struct * t, u8 old, u8 new)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
