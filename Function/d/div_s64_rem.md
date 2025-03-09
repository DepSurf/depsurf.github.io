# Function: <code>div_s64_rem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579807940,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582987298,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607717,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585701974,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579835799,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888208,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896662,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281338,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586002965,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586098796,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579864855,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899968,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908342,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400078,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586198773,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586299276,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579873723,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908418,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579916838,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586286821,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586398235,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256772,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:27",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579672126,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917147,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579953618,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962006,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586750149,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586861533,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588808834,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579704954,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962910,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001309,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009637,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016677,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587155083,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589185787,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579744222,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009968,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047645,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056661,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582816091,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587178133,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587335601,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589416442,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579744121,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580053283,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580091209,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100213,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991099,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585727211,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587443557,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587606234,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589873256,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579786803,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580102339,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140169,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580149189,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097291,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585869099,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587646629,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587809770,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590099148,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579815660,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580200682,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:ntp_update_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580211189,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583416213,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585100825,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586599704,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588513125,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588655967,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
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
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579806954,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580185370,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:ntp_update_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195141,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583530645,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585249348,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586710136,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588538530,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588683808,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
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
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579814771,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580188892,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:process_adjtimex_modes",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580200469,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553798,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593688,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588421781,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588566559,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:39",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
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
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579916227,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580336057,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:ntp_update_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580347525,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912326,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587135512,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589089285,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589163982,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589179344,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240911,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
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
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580548977,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:ntp_update_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580561317,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584489923,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588445143,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590532485,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590616918,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590635439,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590706435,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
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
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580806506,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:ntp_update_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580820837,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585155379,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589874440,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592184581,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592278230,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592299157,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592377427,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580889526,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:ntp_update_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896716,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904133,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585384515,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590183358,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592608357,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592704463,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592724213,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592805427,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580335242,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:place_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:avg_vruntime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580979958,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:ntp_update_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987171,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_watchdog",
        "kernel/time/clocksource.c:clocksource_watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994661,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616758,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_time_advisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585619411,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590527006,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592171139,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/gpu/drm/drm_vblank.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593353109,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593450575,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593472053,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/ptp/ptp_vclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_vclock.c:ptp_vclock_adjfine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593554568,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:40",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/gov_power_allocator.c:pid_controller"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490964372,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491311600,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491361680,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491369208,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494804236,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498603184,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500798588,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501016108,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501027172,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/armada_thermal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503887748,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
s64 div_s64_rem(s64 dividend, s32 divisor, s32 * remainder)
```

```json
{
  "name": "div_s64_rem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229485208,
      "name": "div_s64_rem",
      "external": true,
      "loc": "lib/math/div64.c:71",
      "file": "lib/math/div64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/deadline.c:task_non_contending",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/timeconv.c:time64_to_tm",
        "fs/fat/misc.c:fat_truncate_time",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/rtc/lib.c:rtc_time64_to_tm",
        "drivers/thermal/power_allocator.c:allocate_power",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/thermal/armada_thermal.c:armada_thermal_probe",
        "drivers/thermal/armada_thermal.c:armada_read_sensor",
        "drivers/thermal/armada_thermal.c:armada_read_sensor",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229485208,
      "name": "div_s64_rem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283829228,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284239220,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284295900,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284306352,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288643012,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291825472,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294250896,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294497184,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297744516,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271582146,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271821016,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271853248,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271859972,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274132528,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276202126,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277620932,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277763868,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279773330,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579762659,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580071539,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580109369,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580118389,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066027,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585630091,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587330389,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587440746,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589701404,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579693027,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580016355,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580054681,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580063685,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583003179,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585495163,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587098693,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587208954,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589427196,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579747171,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580062611,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100441,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580109461,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583054635,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585819499,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587597877,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587765914,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588944445,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "net/netfilter/nf_conntrack_standalone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590144780,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_s64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579795587,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580113379,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580152185,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:__do_adjtimex",
        "kernel/time/ntp.c:second_overflow",
        "kernel/time/ntp.c:second_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580161205,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "kernel/time/timeconv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timeconv.c:time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143835,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/misc.c:fat_truncate_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585927115,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587708693,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/rtc/lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_time64_to_tm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587879173,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:allocate_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590195180,
      "name": "div_s64_rem",
      "external": false,
      "loc": "include/linux/math64.h:38",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
s64 div_s64_rem(s64 dividend, s32 divisor, s32 * remainder)
```
</details>
</li>
</ul>
