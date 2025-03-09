# Function: <code>__arch_xprod_64</code>

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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
uint64_t __arch_xprod_64(uint64_t m, uint64_t n, bool bias)
```

```json
{
  "name": "__arch_xprod_64",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224401216,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "arch/arm/vfp/vfpsingle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/vfp/vfpsingle.c:vfp_estimate_sqrt_significand"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "arch/arm/vfp/vfpdouble.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "arch/arm/mach-omap2/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243341428,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "arch/arm/mach-omap2/vc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/vc.c:omap_vc_init_channel",
        "arch/arm/mach-omap2/vc.c:omap_vc_init_channel"
      ],
      "caller_func": []
    },
    {
      "addr": 3224925980,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_max_write",
        "kernel/sched/core.c:cpu_max_show",
        "kernel/sched/core.c:cpu_weight_write_u64",
        "kernel/sched/core.c:cpu_extra_stat_show",
        "kernel/sched/core.c:tg_cfs_schedulable_down",
        "kernel/sched/core.c:cpu_cfs_period_read_u64",
        "kernel/sched/core.c:tg_get_cfs_quota",
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/sched/core.c:tg_set_cfs_bandwidth",
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225021896,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:sched_group_rt_period",
        "kernel/sched/rt.c:sched_group_rt_runtime"
      ],
      "caller_func": []
    },
    {
      "addr": 3225029188,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:start_dl_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225077528,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:nsec_low"
      ],
      "caller_func": []
    },
    {
      "addr": 3225106516,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 3225133292,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:ksys_sync_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 3225134376,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225142780,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:swsusp_show_speed"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225174832,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/power/wakelock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/wakelock.c:pm_wake_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225181168,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:msg_print_text"
      ],
      "caller_func": []
    },
    {
      "addr": 3225309972,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 3225328620,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:get_next_timer_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/hrtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/timekeeping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225357224,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency",
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 3225362140,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/clocksource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:clocksource_max_adjustment"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/jiffies.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/alarmtimer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/clockevents.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225415948,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:get_cpu_iowait_time_us",
        "kernel/time/tick-sched.c:get_cpu_idle_time_us"
      ],
      "caller_func": []
    },
    {
      "addr": 3225478744,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:fill_ac",
        "kernel/acct.c:fill_ac",
        "kernel/acct.c:fill_ac",
        "kernel/acct.c:fill_ac",
        "kernel/acct.c:check_free_space",
        "kernel/acct.c:check_free_space"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225536428,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/cgroup/rstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show",
        "kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3225678648,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225731392,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3225734020,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/tsacct.c:xacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225812700,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_stats_read",
        "kernel/trace/trace.c:tracing_stats_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3225853472,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_output.c:trace_print_lat_context",
        "kernel/trace/trace_output.c:trace_print_lat_context",
        "kernel/trace/trace_output.c:trace_print_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3225869468,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3225875200,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_rel_time",
        "kernel/trace/trace_functions_graph.c:print_graph_abs_time"
      ],
      "caller_func": []
    },
    {
      "addr": 3225885656,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:blk_log_action_classic"
      ],
      "caller_func": []
    },
    {
      "addr": 3226052352,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226225120,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:update_perf_cpu_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226445748,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227572868,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227709556,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227951212,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3228055592,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 3228136900,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229169456,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/blk-settings.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229242708,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229340640,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch"
      ],
      "caller_func": []
    },
    {
      "addr": 3229356712,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_now"
      ],
      "caller_func": []
    },
    {
      "addr": 3229391564,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "lib/string_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "lib/math/div64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "lib/math/reciprocal_div.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229673508,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "lib/dim/dim.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dim/dim.c:dim_calc_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/phy/phy-core-mipi-dphy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230053840,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/gpio/gpio-mvebu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply",
        "drivers/gpio/gpio-mvebu.c:mvebu_pwm_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/pwm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/pci/setup-bus.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/clk-fixed-factor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/clk-fractional-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/clk-hsdk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/clk-npcm7xx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243598596,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/clk-qoriq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-qoriq.c:clockgen_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/actions/owl-factor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/berlin/berlin2-avpll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/berlin/berlin2-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-frac-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-pfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-pfdv2.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-pllv1.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-pllv2.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-pllv3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-pllv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-sccg-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/imx/clk-pll14xx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/mediatek/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/meson/clk-mpll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/meson/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/mvebu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/renesas/clk-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/renesas/rcar-gen2-cpg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/rockchip/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/rockchip/clk-half-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230705892,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/samsung/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/samsung/clk-pll.c:samsung_pll46xx_set_rate",
        "drivers/clk/samsung/clk-pll.c:samsung_pll45xx_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/tegra/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/tegra/clk-periph-fixed.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/tegra/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/tegra/clk-sdmmc-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/tegra/clk-utils.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/ti/divider.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/ti/clkt_dpll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230762500,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/ti/clkctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/ti/dpll3xxx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230769476,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/ti/fapll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/ti/fapll.c:ti_fapll_synth_round_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/ti/adpll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clk/versatile/icst.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/soc/amlogic/meson-clk-measure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230916520,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/soc/tegra/pmc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode",
        "drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231548380,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231596388,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/base/power/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/sysfs.c:runtime_suspended_time_show",
        "drivers/base/power/sysfs.c:runtime_active_time_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3231624180,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_show_time"
      ],
      "caller_func": []
    },
    {
      "addr": 3231639252,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231643064,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/base/power/wakeup_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup_stats.c:prevent_suspend_time_ms_show",
        "drivers/base/power/wakeup_stats.c:last_change_ms_show",
        "drivers/base/power/wakeup_stats.c:max_time_ms_show",
        "drivers/base/power/wakeup_stats.c:total_time_ms_show",
        "drivers/base/power/wakeup_stats.c:active_time_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3231661628,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:active_time_show",
        "drivers/base/power/domain.c:idle_states_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_std_bios_param"
      ],
      "caller_func": []
    },
    {
      "addr": 3232224680,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/mtd/mtdcore.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232306612,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/mtd/mtdconcat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232320552,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/mtd/mtdpart.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/mtd/nand/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232362372,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/mtd/nand/raw/nand_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/nand/raw/nand_base.c:nand_erase_op",
        "drivers/mtd/nand/raw/nand_base.c:nand_prog_page_end_op",
        "drivers/mtd/nand/raw/nand_base.c:nand_exec_prog_page_op",
        "drivers/mtd/nand/raw/nand_base.c:nand_read_param_page_op",
        "drivers/mtd/nand/raw/nand_base.c:nand_read_page_op",
        "drivers/mtd/nand/raw/nand_base.c:nand_lp_exec_read_page_op"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232569396,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/net/ethernet/ti/cpts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpts.c:cpts_ptp_adjfreq"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232814360,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233038668,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_calculate_u2_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_u1_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_u1_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 3233389504,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233409240,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/i2c/busses/i2c-s3c2410.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 3233443568,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233478852,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233513144,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/thermal/thermal_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_sysfs.c:time_in_state_ms_show"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233532796,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3233535464,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/thermal/devfreq_cooling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/devfreq_cooling.c:get_dynamic_power"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/md/dm-stripe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/md/dm-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233786628,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233806348,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233814364,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233824348,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233826684,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233942072,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_start_data"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/mmc/host/omap_hsmmc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234078552,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/firmware/tegra/bpmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3234090216,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/clocksource/sh_cmt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234283504,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "drivers/memory/tegra/mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/memory/tegra/mc.c:tegra_mc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "sound/core/pcm_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "sound/soc/codecs/sgtl5000.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "sound/soc/fsl/fsl_ssi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/bpf/test_run.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235377312,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_time_stamp_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 3235434156,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235462560,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_mstamp_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 3235478344,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235496352,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 3235505552,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235523572,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 3235524712,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_skb_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 3235609624,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/nexthop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235757136,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 3235761628,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv4/tcp_cubic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid"
      ],
      "caller_func": []
    },
    {
      "addr": 3235963328,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_rs_timer",
        "net/ipv6/addrconf.c:addrconf_rs_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236142864,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 3236222668,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__arch_xprod_64",
      "external": false,
      "loc": "arch/arm/include/asm/div64.h:75",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227957104,
      "name": "__arch_xprod_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 3232306612,
      "name": "__arch_xprod_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 3232320552,
      "name": "__arch_xprod_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 3232564512,
      "name": "__arch_xprod_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 3235760032,
      "name": "__arch_xprod_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
uint64_t __arch_xprod_64(uint64_t m, uint64_t n, bool bias)
```
</details>
</li>
</ul>
