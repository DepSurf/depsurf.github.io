# Function: <code>div_u64_rem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579571776,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579583329,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:enqueue_entity",
        "kernel/sched/fair.c:update_group_capacity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579629956,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579807457,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:clock_t_to_jiffies"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579856160,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580516752,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582987295,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046825,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584728354,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586110869,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595187266,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579606831,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_task_cfs_rq",
        "kernel/sched/fair.c:attach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:detach_task_cfs_rq",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:put_prev_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:set_next_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:dequeue_entity",
        "kernel/sched/fair.c:enqueue_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579644597,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579835413,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885200,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580487981,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580602602,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580703952,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:fragmentation_index",
        "mm/vmstat.c:fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992446,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664378,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848598,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582039114,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110443,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583146372,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583183565,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_target_latency_us_show",
        "block/cfq-iosched.c:cfq_slice_async_us_show",
        "block/cfq-iosched.c:cfq_slice_sync_us_show",
        "block/cfq-iosched.c:cfq_group_idle_us_show",
        "block/cfq-iosched.c:cfq_slice_idle_us_show",
        "block/cfq-iosched.c:cfq_target_latency_show",
        "block/cfq-iosched.c:cfq_slice_async_show",
        "block/cfq-iosched.c:cfq_slice_sync_show",
        "block/cfq-iosched.c:cfq_group_idle_show",
        "block/cfq-iosched.c:cfq_slice_idle_show",
        "block/cfq-iosched.c:cfq_fifo_expire_async_show",
        "block/cfq-iosched.c:cfq_fifo_expire_sync_show",
        "block/cfq-iosched.c:__cfq_update_io_thinktime",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_set_prio_slice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281335,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340377,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585053974,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:__add_badblock_range",
        "drivers/nvdimm/core.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585080471,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585097610,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585351078,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586310631,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586524345,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587094990,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587239365,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595430127,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579647146,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669274,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579864469,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896960,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580341654,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551181,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580669514,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580769728,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:fragmentation_index",
        "mm/vmstat.c:fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066205,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752943,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937508,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129223,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582200952,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144719,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224234,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258292,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583294413,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_target_latency_us_show",
        "block/cfq-iosched.c:cfq_slice_async_us_show",
        "block/cfq-iosched.c:cfq_slice_sync_us_show",
        "block/cfq-iosched.c:cfq_group_idle_us_show",
        "block/cfq-iosched.c:cfq_slice_idle_us_show",
        "block/cfq-iosched.c:cfq_target_latency_show",
        "block/cfq-iosched.c:cfq_slice_async_show",
        "block/cfq-iosched.c:cfq_slice_sync_show",
        "block/cfq-iosched.c:cfq_group_idle_show",
        "block/cfq-iosched.c:cfq_slice_idle_show",
        "block/cfq-iosched.c:cfq_fifo_expire_async_show",
        "block/cfq-iosched.c:cfq_fifo_expire_sync_show",
        "block/cfq-iosched.c:__cfq_update_io_thinktime",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_set_prio_slice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583341801,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400075,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465791,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585237254,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:__add_badblock_range",
        "drivers/nvdimm/core.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585266913,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585552118,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586518343,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586704041,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587292438,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587439573,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596350534,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579586469,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641584,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:task_tick_fair",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579644947,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579872725,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905472,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937628,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234815,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580236991,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580354340,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582381,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702923,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580805888,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:fragmentation_index",
        "mm/vmstat.c:fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114095,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806712,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581928344,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582153394,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286360,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201855,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278356,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310341,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356845,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_target_latency_us_show",
        "block/cfq-iosched.c:cfq_slice_async_us_show",
        "block/cfq-iosched.c:cfq_slice_sync_us_show",
        "block/cfq-iosched.c:cfq_group_idle_us_show",
        "block/cfq-iosched.c:cfq_slice_idle_us_show",
        "block/cfq-iosched.c:cfq_target_latency_show",
        "block/cfq-iosched.c:cfq_slice_async_show",
        "block/cfq-iosched.c:cfq_slice_sync_show",
        "block/cfq-iosched.c:cfq_group_idle_show",
        "block/cfq-iosched.c:cfq_slice_idle_show",
        "block/cfq-iosched.c:cfq_fifo_expire_async_show",
        "block/cfq-iosched.c:cfq_fifo_expire_sync_show",
        "block/cfq-iosched.c:__cfq_update_io_thinktime",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_set_prio_slice"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400301,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583488136,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584970856,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_part_to_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585318833,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/core.c:__add_badblock_range",
        "drivers/nvdimm/core.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585351517,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585636006,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586347463,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580600,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586607357,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586644015,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586829751,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587378557,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587414789,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587460018,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587464739,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587482977,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587575509,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587684441,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587990666,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256769,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:18",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602668718,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617333,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671306,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:sched_group_set_shares",
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:dequeue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:enqueue_task_fair",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674318,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579916133,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950752,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983163,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580286015,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580288191,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408052,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580662109,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580793962,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895176,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581225119,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956206,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582078664,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302056,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582435416,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582756239,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583378175,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432491,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583458615,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492981,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538861,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_target_latency_us_show",
        "block/cfq-iosched.c:cfq_slice_async_us_show",
        "block/cfq-iosched.c:cfq_slice_sync_us_show",
        "block/cfq-iosched.c:cfq_group_idle_us_show",
        "block/cfq-iosched.c:cfq_slice_idle_us_show",
        "block/cfq-iosched.c:cfq_target_latency_show",
        "block/cfq-iosched.c:cfq_slice_async_show",
        "block/cfq-iosched.c:cfq_slice_sync_show",
        "block/cfq-iosched.c:cfq_group_idle_show",
        "block/cfq-iosched.c:cfq_slice_idle_show",
        "block/cfq-iosched.c:cfq_fifo_expire_async_show",
        "block/cfq-iosched.c:cfq_fifo_expire_sync_show",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:__cfq_update_io_thinktime",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583579853,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669176,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585392216,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_part_to_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585779933,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585801073,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586067718,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586811783,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587063880,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587090463,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125584,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587317501,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587899823,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587934614,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587981922,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587982770,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588004995,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588099397,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588211177,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588526924,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588808831,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602839992,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647641,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693427,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:update_group_capacity",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710478,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579960773,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579998387,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580034293,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580299720,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580347338,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580349447,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469957,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580793583,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580931480,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030948,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581372939,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141440,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266585,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582489971,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582625588,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582956431,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583588192,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643655,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669814,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705925,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583754325,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/cfq-iosched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_target_latency_us_show",
        "block/cfq-iosched.c:cfq_slice_async_us_show",
        "block/cfq-iosched.c:cfq_slice_sync_us_show",
        "block/cfq-iosched.c:cfq_group_idle_us_show",
        "block/cfq-iosched.c:cfq_slice_idle_us_show",
        "block/cfq-iosched.c:cfq_target_latency_show",
        "block/cfq-iosched.c:cfq_slice_async_show",
        "block/cfq-iosched.c:cfq_slice_sync_show",
        "block/cfq-iosched.c:cfq_group_idle_show",
        "block/cfq-iosched.c:cfq_slice_idle_show",
        "block/cfq-iosched.c:cfq_fifo_expire_async_show",
        "block/cfq-iosched.c:cfq_fifo_expire_sync_show",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:__cfq_update_io_thinktime",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:cfq_dispatch_requests",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:__cfq_slice_expired",
        "block/cfq-iosched.c:cfq_service_tree_add",
        "block/cfq-iosched.c:cfq_service_tree_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583796393,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583886949,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586028829,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586047221,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586315725,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587085548,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587098596,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587362097,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587388584,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587425312,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587620284,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588249691,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588283857,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_rcv_space_adjust",
        "net/ipv4/tcp_input.c:tcp_init_buffer_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588332193,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588333106,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355705,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452885,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588565753,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892086,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589122098,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589185821,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604636422,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685209,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697886,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579748270,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579793536,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824676,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:update_stats",
        "kernel/sched/psi.c:update_stats",
        "kernel/sched/psi.c:update_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580007349,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044739,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580081158,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352808,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580403402,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580405511,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580526037,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580860079,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581008053,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108500,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581436963,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582236064,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363897,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582590691,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582727332,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066010,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583697108,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750247,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583767640,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583777094,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583812903,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583879260,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583971189,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586167997,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586187445,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586457277,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587246082,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587275812,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587541969,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587568520,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587606112,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587749820,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588432033,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588472617,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588521338,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588527007,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588546115,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588566006,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588566683,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588646645,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588763282,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589115547,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589356162,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589416476,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604733705,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604751290,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718985,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579773841,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776845,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579821983,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853116,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580050933,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580088355,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580124478,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:run_posix_cpu_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406599,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456302,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580458430,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582448,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829318,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956759,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071194,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173285,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551918,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400480,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582531865,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582762406,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900908,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250663,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583886670,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939315,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583957109,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583966791,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002995,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584069836,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584152405,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586405280,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586424629,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586702221,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513367,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545348,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587816533,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587844294,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587883017,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054554,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588838763,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588900973,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588931813,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934878,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588957068,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588960761,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977142,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977824,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589059013,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589196210,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589568802,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589813157,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589873290,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604747089,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604764691,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708417,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761417,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579816498,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579823645,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579870079,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579901660,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580099989,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137315,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580455367,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580505262,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580507342,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580629552,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880614,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581008967,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127170,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231381,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616905,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582499440,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582633108,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865526,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007484,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356503,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583989950,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584042787,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060581,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070151,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106361,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192540,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275029,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586552085,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586571269,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586848845,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587716149,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587748100,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588021733,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588049126,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588088851,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588260458,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589061379,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589125101,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589155829,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589159054,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589181580,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589185465,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201590,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589202272,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283285,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589421634,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589792963,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590038075,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590099182,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609093070,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280192,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609111048,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579748433,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795093,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803475,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579862441,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:do_balance_runtime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911781,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579945212,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580167381,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timespec64",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580198835,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580537431,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580591081,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580593561,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580729641,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581021786,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189703,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314414,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420839,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831857,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582800716,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582942164,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178605,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323724,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583691482,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584378830,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584438627,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584456567,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584502216,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584587215,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584684024,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584796034,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "lib/zstd/fse_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_compress.c:FSE_normalizeCount",
        "lib/zstd/fse_compress.c:FSE_normalizeCount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585100859,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609314202,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:irtl_2_usec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587314300,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587338318,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356421,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587651302,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588586839,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588592846,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588881775,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588909860,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588951318,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:get_typical_interval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589139835,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590029256,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590092211,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590124853,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_syn_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590129564,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590152544,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590156425,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590173830,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590174430,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590257381,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590408789,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590814903,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591068673,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612157932,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284746,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:amd_set_max_freq_ratio",
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612175772,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734207,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794611,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854777,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:do_balance_runtime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905259,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579933468,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580151525,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timespec64",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580183667,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525207,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580580233,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582729,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718969,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581027954,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231335,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355778,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463927,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:extfrag_for_order",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878440,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582874348,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583016580,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270413,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397192,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583440412,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583812874,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584492734,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584555443,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573238,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584613058,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584667780,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705764,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584801592,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584909511,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "lib/zstd/fse_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_compress.c:FSE_normalizeCount",
        "lib/zstd/fse_compress.c:FSE_normalizeCount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585249382,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612384676,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:irtl_2_usec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376236,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587400046,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587417733,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587712230,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588610279,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588615902,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894591,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588922372,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588925894,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:get_max_boost_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588963574,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:get_typical_interval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589138907,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589833514,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590082474,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590138355,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590172581,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_syn_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177308,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590201600,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590205385,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590223078,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590223680,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590310245,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590467112,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590875054,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591133576,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591142988,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_subflow_get_send"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614298348,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579290160,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614316023,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579740735,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579811314,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579863950,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579914288,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579940924,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580156181,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timespec64",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580188125,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580528839,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580582761,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580585673,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724132,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038079,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581247084,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581372728,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484775,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:extfrag_for_order",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909280,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582902690,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583042105,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583295421,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420120,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583462601,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837098,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527470,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584588247,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584605343,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584644666,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584694324,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584733989,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584845433,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_kstrtoull"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614526378,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:irtl_2_usec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587257372,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587281806,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587299797,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587591190,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588495257,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588500834,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588783599,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588810963,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588817764,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588851592,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589028944,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589726388,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589996968,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590052906,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590087013,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_syn_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590091708,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590115766,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590119476,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590137145,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590137766,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590226117,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590392885,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590804216,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591064395,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591074012,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:25",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615225180,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335216,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615244675,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826031,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908744,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975756,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580035668,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064963,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580300709,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timespec64",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334365,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580700712,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580752965,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756505,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903593,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581261333,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482908,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621051,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737797,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:extfrag_for_order",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582200848,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583236856,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583379529,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583638589,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583764302,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583814761,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584200090,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584937710,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585002770,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585018463,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585061588,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585117428,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585161733,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585265353,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_kstrtoull"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615476201,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:irtl_2_usec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587826910,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587848638,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587866613,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588175130,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589169058,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475828,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589503735,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589511225,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589551212,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589744640,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590484787,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590767443,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590826586,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590861701,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_syn_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590866928,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590892829,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590896102,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590917353,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590918070,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591009029,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591188165,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591622436,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591906987,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591920428,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616977327,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616999467,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387325,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/acpi/cppc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617021040,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944565,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580023411,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580125183,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580207343,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "kernel/sched/build_utility.c:__sched_core_account_forceidle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580509701,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timespec64",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580547123,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912490,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968022,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971936,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139684,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581551807,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581827777,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984774,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582120988,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:extfrag_for_order",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582665676,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583735729,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583892841,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584182818,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584324086,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584385296,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584802754,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585639725,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585717238,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585735830,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585783931,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585856568,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585898179,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586110347,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586245374,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/zstd/compress/fse_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/fse_compress.c:FSE_normalizeCount",
        "lib/zstd/compress/fse_compress.c:FSE_normalizeM2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586676116,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/flex_proportions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/flex_proportions.c:__fprop_add_percpu_max"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617278464,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:irtl_2_usec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589176615,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197211,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589216037,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589556640,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590624427,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590955151,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590987152,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590995586,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590998724,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq",
        "drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591044727,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591255314,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592400755,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592462784,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592498305,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_syn_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592503580,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592531064,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592534284,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592557328,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592558204,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592655525,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592847525,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593315103,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593627869,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593645036,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627597801,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627627258,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465005,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/acpi/cppc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627655561,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096981,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580179515,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298895,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580400315,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "kernel/sched/build_utility.c:__sched_core_account_forceidle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580763685,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timespec64",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580804435,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204490,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263702,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267760,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451636,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581923544,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582254964,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582420767,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582595068,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:extfrag_for_order",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190627,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349015,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584517849,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584820527,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584972550,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585038016,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585500978,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586412853,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586497703,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586518934,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586564795,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586635563,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586685891,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587096011,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587224414,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/zstd/compress/fse_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/fse_compress.c:FSE_normalizeCount",
        "lib/zstd/compress/fse_compress.c:FSE_normalizeM2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627990041,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590729879,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590750939,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590771717,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591149520,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592287195,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592657615,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592694828,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592702659,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592706340,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq",
        "drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592756679,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593010066,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594262429,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594317168,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594354033,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_syn_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594359676,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594389165,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594392541,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594416912,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594417820,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594522277,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594724597,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595220018,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595557501,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595575708,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595756164,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/flex_proportions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/flex_proportions.c:__fprop_add_percpu_max"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619351822,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619383386,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477509,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/acpi/cppc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619412505,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580160501,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580248580,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_cpu",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580366121,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469280,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "kernel/sched/build_utility.c:__sched_core_account_forceidle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699301,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580846357,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timespec64",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580887587,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580961952,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_init_jiffy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298842,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358854,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362912,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548740,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581565948,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/trace/trace_osnoise.c:timerlat_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106737,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582132742,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/bpf/log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/log.c:bpf_vlog_finalize",
        "kernel/bpf/log.c:bpf_vlog_reset",
        "kernel/bpf/log.c:bpf_verifier_vlog",
        "kernel/bpf/log.c:bpf_verifier_vlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582455572,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582625983,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582802791,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:extfrag_for_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583408659,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584579287,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584746386,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585045135,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585200790,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585265616,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585732562,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586659797,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586745299,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586766102,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586820950,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586896568,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586947507,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587356075,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587488702,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/zstd/compress/fse_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/fse_compress.c:FSE_normalizeCount",
        "lib/zstd/compress/fse_compress.c:FSE_normalizeM2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619755849,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591071207,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591093040,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591113125,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591508032,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592711555,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593088351,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593125788,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593133657,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593140038,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq",
        "drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593183679,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593191941,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593461587,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594649875,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594703568,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594741937,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_syn_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594747974,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594777511,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594781626,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594806256,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594807164,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594914101,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595116677,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595616104,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596065821,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596085852,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596280492,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/flex_proportions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/flex_proportions.c:__fprop_add_percpu_max"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621645758,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621678753,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579508277,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/acpi/cppc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580199813,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580353335,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580421721,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_dl_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:update_rt_rq_load_avg",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_cfs_rq",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se",
        "kernel/sched/build_policy.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580529097,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:update_averages",
        "kernel/sched/build_utility.c:collect_percpu_times",
        "kernel/sched/build_utility.c:__sched_core_account_forceidle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580762995,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stat_info",
        "kernel/rcu/tree.c:print_cpu_stat_info",
        "kernel/rcu/tree.c:print_cpu_stat_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580935749,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timespec64",
        "kernel/time/time.c:ns_to_kernel_old_timeval",
        "kernel/time/time.c:ns_to_kernel_old_timeval"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978019,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053536,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/time/tick-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_init_jiffy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405018,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465013,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:fill_stats_for_tgid",
        "kernel/taskstats.c:fill_stats_for_tgid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581469187,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660964,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581678190,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/trace/trace_osnoise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_fd_read",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/trace/trace_osnoise.c:timerlat_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246373,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275446,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/bpf/log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/log.c:bpf_vlog_finalize",
        "kernel/bpf/log.c:bpf_vlog_reset",
        "kernel/bpf/log.c:bpf_verifier_vlog",
        "kernel/bpf/log.c:bpf_verifier_vlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582624276,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_event_max_sample_rate_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582790959,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582977383,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:extfrag_show_print",
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:extfrag_for_order"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388387,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_debugfs_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349851,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:folio_init_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584810547,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584979106,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585277055,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585433686,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585498848,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585979820,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586931064,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587017459,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587038582,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show",
        "block/genhd.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587098038,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:is_gpt_valid",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587174600,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587227939,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587642395,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer_limit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587823486,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/zstd/compress/fse_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/fse_compress.c:FSE_normalizeCount",
        "lib/zstd/compress/fse_compress.c:FSE_normalizeM2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622063449,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update",
        "drivers/idle/intel_idle.c:bxt_idle_state_table_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591416103,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591437984,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591458453,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591856640,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592045855,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/gpu/drm/drm_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_file.c:print_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592166286,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/gpu/drm/drm_vblank.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants",
        "drivers/gpu/drm/drm_vblank.c:drm_calc_timestamping_constants"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593457931,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593840767,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593879006,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593886936,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593892823,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpufreq/amd-pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_set_policy",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init",
        "drivers/cpufreq/amd-pstate.c:show_amd_pstate_lowest_nonlinear_freq",
        "drivers/cpufreq/amd-pstate.c:show_amd_pstate_max_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_adjust_perf",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_update_freq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593937503,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593946559,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select",
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594208579,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595454020,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:tcp_get_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595498085,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595547633,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_synack_options",
        "net/ipv4/tcp_output.c:tcp_syn_options",
        "net/ipv4/tcp_output.c:tcp_syn_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595553781,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595573289,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595592833,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595617488,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595618396,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595725925,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595929813,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596452939,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596933629,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596951653,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_rcv_space_adjust",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:mptcp_subflow_get_send",
        "net/mptcp/protocol.c:perf_trace_mptcp_subflow_get_send",
        "net/mptcp/protocol.c:trace_event_raw_event_mptcp_subflow_get_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597165196,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:26",
      "file": "lib/flex_proportions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/flex_proportions.c:__fprop_add_percpu_max"
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490888836,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490939832,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490983112,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491005368,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491068648,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491100784,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491311376,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491359064,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491727868,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491783984,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491786128,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491932960,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492205564,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492355764,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492497796,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492620816,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493061240,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494123528,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494284016,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494566028,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494692744,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495101372,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495816360,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495877832,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495902348,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495913424,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495949856,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496057724,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496160324,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497920952,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/clk/meson/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/meson/clk-pll.c:meson_clk_pll_set_rate",
        "drivers/clk/meson/clk-pll.c:meson_clk_pll_round_rate",
        "drivers/clk/meson/clk-pll.c:meson_clk_get_pll_settings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497933836,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/clk/renesas/rcar-gen3-cpg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-gen3-cpg.c:cpg_z_clk_round_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499441976,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499460872,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499781184,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500038372,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500882432,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500933988,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501284952,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501318672,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501335784,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501719996,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502682916,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502740840,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502771808,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502775968,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502799380,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502803488,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502821928,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502822712,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502912396,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503074568,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503497064,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503792380,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503887780,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u64 div_u64_rem(u64 dividend, u32 divisor, u32 * remainder)
```

```json
{
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224909872,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3224955928,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/sched/cputime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cputime.c:cputime_adjust"
      ]
    },
    {
      "addr": 3224985288,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_h_load"
      ],
      "caller_func": [
        "kernel/sched/fair.c:task_h_load",
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ]
    },
    {
      "addr": 3225007004,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/sched/rt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225067624,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/sched/pelt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ]
    },
    {
      "addr": 3225076984,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/debug.c:proc_sched_show_task"
      ]
    },
    {
      "addr": 3225106484,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages"
      ],
      "caller_func": [
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ]
    },
    {
      "addr": 3225309972,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
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
      "addr": 3225357224,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency",
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 3225678636,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ]
    },
    {
      "addr": 3225730636,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd"
      ]
    },
    {
      "addr": 3225733180,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ]
    },
    {
      "addr": 3225740368,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show"
      ]
    },
    {
      "addr": 3225868764,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    },
    {
      "addr": 3226052340,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    },
    {
      "addr": 3226225120,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:update_perf_cpu_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 3226367092,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:__wb_calc_thresh",
        "mm/page-writeback.c:__wb_calc_thresh"
      ]
    },
    {
      "addr": 3226475144,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index"
      ]
    },
    {
      "addr": 3226765632,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:list_locations"
      ]
    },
    {
      "addr": 3227572856,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/uptime.c:uptime_proc_show"
      ]
    },
    {
      "addr": 3227709544,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ]
    },
    {
      "addr": 3228024232,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 3228136888,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ]
    },
    {
      "addr": 3228492936,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "security/keys/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ]
    },
    {
      "addr": 3229169456,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3229223336,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229242696,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ]
    },
    {
      "addr": 3229252276,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ]
    },
    {
      "addr": 3229289704,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:last_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 3229391564,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": [
        "block/blk-wbt.c:rwb_arm_timer"
      ]
    },
    {
      "addr": 3229479944,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kstrtox.c:_parse_integer"
      ]
    },
    {
      "addr": 3229485256,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "lib/math/div64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/math/div64.c:div_s64_rem"
      ],
      "caller_func": [
        "lib/math/div64.c:div_s64_rem"
      ]
    },
    {
      "addr": 3230190196,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources",
        "drivers/pci/setup-bus.c:pci_bus_distribute_available_resources"
      ]
    },
    {
      "addr": 3230672964,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/clk/meson/clk-pll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/meson/clk-pll.c:meson_clk_get_pll_range_m"
      ],
      "caller_func": [
        "drivers/clk/meson/clk-pll.c:__pll_params_with_frac"
      ]
    },
    {
      "addr": 3230680988,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/clk/renesas/clk-rcar-gen2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/clk-rcar-gen2.c:cpg_z_clk_round_rate",
        "drivers/clk/renesas/clk-rcar-gen2.c:cpg_z_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230681548,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/clk/renesas/rcar-gen2-cpg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/rcar-gen2-cpg.c:cpg_z_clk_round_rate",
        "drivers/clk/renesas/rcar-gen2-cpg.c:cpg_z_clk_recalc_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 3230764344,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/clk/ti/dpll3xxx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/ti/dpll3xxx.c:omap3_dpll5_set_rate"
      ]
    },
    {
      "addr": 3232224668,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ]
    },
    {
      "addr": 3232557192,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/net/ethernet/freescale/fec_ptp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_adjfreq"
      ]
    },
    {
      "addr": 3232569396,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/net/ethernet/ti/cpts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpts.c:cpts_ptp_adjfreq"
      ],
      "caller_func": []
    },
    {
      "addr": 3233389492,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    },
    {
      "addr": 3233443556,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233786616,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233806336,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ]
    },
    {
      "addr": 3233824456,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/menu.c:get_typical_interval"
      ]
    },
    {
      "addr": 3234243208,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ]
    },
    {
      "addr": 3234430244,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "sound/core/pcm_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "sound/core/pcm_lib.c:snd_interval_mulkdiv",
        "sound/core/pcm_lib.c:snd_interval_mulkdiv",
        "sound/core/pcm_lib.c:snd_interval_muldivk",
        "sound/core/pcm_lib.c:snd_interval_muldivk",
        "sound/core/pcm_lib.c:update_audio_tstamp"
      ]
    },
    {
      "addr": 3235377312,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_time_stamp_raw"
      ],
      "caller_func": []
    },
    {
      "addr": 3235434156,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_ack_update_rtt",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    },
    {
      "addr": 3235462560,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options",
        "net/ipv4/tcp_output.c:tcp_mstamp_refresh"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_update_skb_after_send"
      ]
    },
    {
      "addr": 3235478332,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    },
    {
      "addr": 3235496352,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    },
    {
      "addr": 3235505540,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    },
    {
      "addr": 3235523572,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
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
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
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
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 3235757484,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 3236142864,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 3236409732,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    },
    {
      "addr": 3236500692,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:88",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224955928,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3224962548,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3225007004,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3225067624,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3225076984,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3225102968,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3225678636,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 3225730636,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3225733180,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3225740368,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3225868028,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3226052340,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3226367092,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3226470524,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3226765632,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3227572856,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 3227709544,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 3228136888,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 3228492936,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3229242696,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 3229252276,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3229386384,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3229479944,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3229485124,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3230190196,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3230672016,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3230680488,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3230681048,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3230764344,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3232224668,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3232557192,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3233389492,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3233443556,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 3233786616,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 3233806336,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 3233824456,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3234243208,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3234430244,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3235418096,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3235449088,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3235478332,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3235483884,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3235505540,
      "name": "div_u64_rem.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3236409732,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3236500692,
      "name": "div_u64_rem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283730856,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283795616,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283851016,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283873840,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283949536,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283992288,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284237096,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284291908,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284755724,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284832112,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284834696,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285032220,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285425072,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285605076,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285785788,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285940872,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286502168,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287796064,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287997000,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288316920,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288516208,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289005860,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290003840,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290079700,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290109752,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290123252,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290171216,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:find_valid_gpt",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290294808,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290423920,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292696996,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292724780,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293128304,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294388788,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294810940,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294853764,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294882176,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295165124,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296292224,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296365536,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296405196,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296410304,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296440168,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296444140,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296469816,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296470824,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296583268,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296778940,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297287980,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297634840,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297744556,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271571750,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271577920,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_task_rq_fair",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271612722,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:do_balance_runtime"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271659162,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271683396,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271820092,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271850896,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272099202,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:taskstats_user_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272100906,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272209086,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272355238,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272476970,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272559704,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272646502,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272928164,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273605986,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273729126,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273925860,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274051056,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274360872,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274952478,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275000496,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275017750,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275027146,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275060556,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275134434,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275212006,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275928480,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/clk/analogbits/wrpll-cln28hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_calc_output_rate",
        "drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate",
        "drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate",
        "drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate",
        "drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/clk/sifive/fu540-prci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276666320,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276682520,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276934108,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277673030,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277699580,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278135360,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278811346,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278865634,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278893302,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278896700,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278916862,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278919814,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278935714,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278936400,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279008152,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279130892,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279471350,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279697364,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279773322,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604673392,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604690970,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579684737,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579737337,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579792274,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579797469,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579842431,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579873772,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580069189,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106515,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580424167,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474062,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580476142,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580598352,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849414,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977815,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096018,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200229,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585641,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468176,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582601844,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834262,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582976220,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583325239,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958686,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584011523,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584029317,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584038887,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584075097,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161276,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584243765,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242565,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586261749,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586503699,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586607373,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587389044,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587646725,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587674118,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587710451,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587872154,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588667763,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588731485,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588762213,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588765438,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588787964,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588791849,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588807974,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588808656,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588889461,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589026002,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589397331,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589641675,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589701438,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604640863,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604658520,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579613057,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666297,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579723058,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730397,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579777167,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579808780,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014005,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580051827,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580371239,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580421096,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580423195,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580544826,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795590,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923943,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043186,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146981,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527161,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405408,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539012,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582771414,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582913372,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583262343,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583895614,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583947347,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583965109,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583974647,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584010857,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584096540,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584178965,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585090044,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/acpi/nfit/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io",
        "drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586060933,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586080117,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586107200,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/btt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt.c:btt_write_pg",
        "drivers/nvdimm/btt.c:btt_read_pg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586115271,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/blk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/blk.c:nd_blk_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586372275,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586475885,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587157252,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587420597,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587447990,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587488931,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587598954,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588379747,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588443469,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588474149,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588477374,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588499900,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588503785,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588519910,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588520592,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588601397,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588751042,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589122323,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589366203,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589427230,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604751155,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604768554,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579721785,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776866,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784013,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579830447,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579861932,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580060261,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:nsecs_to_jiffies",
        "kernel/time/time.c:nsec_to_clock_t",
        "kernel/time/time.c:jiffies_64_to_clock_t",
        "kernel/time/time.c:clock_t_to_jiffies",
        "kernel/time/time.c:jiffies_to_clock_t",
        "kernel/time/time.c:jiffies_to_timeval",
        "kernel/time/time.c:jiffies_to_timespec64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580097587,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580415415,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580465310,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580467390,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580589600,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580840662,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969015,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087218,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191429,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576953,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458656,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582591956,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823142,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964828,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583309015,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583942446,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583995283,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584013077,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584022647,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584058857,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145036,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584227525,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586500053,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586519237,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586803405,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587672293,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587704244,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587977877,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588005270,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588044995,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588197514,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589103939,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589167661,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589198389,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201614,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224140,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589228025,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589244150,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589244832,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589325845,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589462386,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589834195,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590083707,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590144814,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
  "name": "div_u64_rem",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604751188,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604768811,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:calibrate_APIC_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716949,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:cpu_uclamp_max_show",
        "kernel/sched/core.c:cpu_uclamp_min_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769161,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:cputime_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579824975,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:sched_cfs_period_timer",
        "kernel/sched/fair.c:attach_entity_load_avg",
        "kernel/sched/fair.c:reweight_entity",
        "kernel/sched/fair.c:reweight_entity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579826225,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579875663,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/pelt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_dl_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:update_rt_rq_load_avg",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_cfs_rq",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se",
        "kernel/sched/pelt.c:__update_load_avg_blocked_se"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579907308,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:update_averages",
        "kernel/sched/psi.c:collect_percpu_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580111029,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
      "addr": 18446744071580149331,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/time/ntp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/ntp.c:ntp_update_frequency"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470999,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520979,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/taskstats.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580523090,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/tsacct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk",
        "kernel/tsacct.c:bacct_add_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580646496,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898950,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/bpf/verifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:bpf_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029799,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_cpu_time_max_percent_handler",
        "kernel/events/core.c:perf_proc_update_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149164,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:balance_dirty_pages",
        "mm/page-writeback.c:wb_update_dirty_ratelimit",
        "mm/page-writeback.c:wb_position_ratio",
        "mm/page-writeback.c:wb_position_ratio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254709,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:unusable_show_print",
        "mm/vmstat.c:__fragmentation_index",
        "mm/vmstat.c:__fragmentation_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642201,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:list_locations"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539008,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/proc/uptime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/uptime.c:uptime_proc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673839,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show",
        "fs/ext4/extents_status.c:ext4_seq_es_shrinker_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909750,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:perf_trace_ext4_es_shrink",
        "fs/ext4/super.c:trace_event_raw_event_ext4_es_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053692,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_seq_info_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583404047,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "security/keys/proc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show",
        "security/keys/proc.c:proc_keys_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044446,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-sysfs.c:queue_wb_lat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584097683,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584115618,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125191,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:rescan_partitions",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161353,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584249004,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:rwb_arm_timer",
        "block/blk-wbt.c:perf_trace_wbt_step",
        "block/blk-wbt.c:perf_trace_wbt_lat",
        "block/blk-wbt.c:trace_event_raw_event_wbt_step",
        "block/blk-wbt.c:trace_event_raw_event_wbt_lat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584332357,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "lib/kstrtox.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:_parse_integer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586611797,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586631205,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:__add_badblock_range",
        "drivers/nvdimm/badrange.c:__add_badblock_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586909501,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ata/libata-transport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-transport.c:ata_show_ering"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587778677,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587817316,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588093253,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time",
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588120710,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588160803,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/cpuidle/governors/menu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/menu.c:menu_select"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588332810,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "drivers/devfreq/governor_simpleondemand.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func",
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589143699,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589207661,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_synack_rtt_meas",
        "net/ipv4/tcp_input.c:tcp_cwnd_reduction",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589238501,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_window_probe",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_make_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb",
        "net/ipv4/tcp_output.c:tcp_established_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589241742,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589264268,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589268169,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589284726,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_rate.c:tcp_rate_skb_delivered",
        "net/ipv4/tcp_rate.c:tcp_rate_skb_sent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589285408,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589366949,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:inet_current_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589508722,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_init_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589885459,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590133915,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590195214,
      "name": "div_u64_rem",
      "external": false,
      "loc": "include/linux/math64.h:24",
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
u64 div_u64_rem(u64 dividend, u32 divisor, u32 * remainder)
```
</details>
</li>
</ul>
