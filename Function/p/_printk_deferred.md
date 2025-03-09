# Function: <code>_printk_deferred</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int _printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "_printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592134166,
      "name": "_printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:3270",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:replenish_dl_entity",
        "kernel/sched/psi.c:psi_flags_change",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/power/main.c:__pm_pr_dbg",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "drivers/char/random.c:get_random_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592134166,
      "name": "_printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int _printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "_printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593905009,
      "name": "_printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:3526",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:replenish_dl_entity",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_utility.c:psi_flags_change",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "lib/ratelimit.c:___ratelimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593905009,
      "name": "_printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int _printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "_printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:3789",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:replenish_dl_entity",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_utility.c:psi_flags_change",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "kernel/trace/rv/reactor_printk.c:rv_printk_reaction",
        "lib/ratelimit.c:___ratelimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595985898,
      "name": "_printk_deferred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580493472,
      "name": "_printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int _printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "_printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:3830",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/workqueue.c:wq_cpu_intensive_report",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:replenish_dl_entity",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_utility.c:psi_flags_change",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "kernel/trace/rv/reactor_printk.c:rv_printk_reaction",
        "lib/ratelimit.c:___ratelimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596504194,
      "name": "_printk_deferred.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580565312,
      "name": "_printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int _printk_deferred(const char * fmt, void (anon))
```

```json
{
  "name": "_printk_deferred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628416,
      "name": "_printk_deferred",
      "external": true,
      "loc": "kernel/printk/printk.c:3948",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:get_stack_info",
        "arch/x86/kernel/i8259.c:mask_and_ack_8259A",
        "arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm",
        "arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_next_frame",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "arch/x86/kernel/unwind_frame.c:unwind_dump",
        "kernel/workqueue.c:wq_cpu_intensive_report",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:enqueue_task_dl",
        "kernel/sched/build_policy.c:replenish_dl_entity",
        "kernel/sched/build_policy.c:enqueue_task_rt",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_utility.c:psi_flags_change",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/clockevents.c:clockevents_program_min_delta",
        "kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time",
        "kernel/trace/rv/reactor_printk.c:rv_printk_reaction",
        "lib/ratelimit.c:___ratelimit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628416,
      "name": "_printk_deferred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int _printk_deferred(const char * fmt, void (anon))
```
</details>
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
