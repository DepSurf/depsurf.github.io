# Function: <code>seq_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145008,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:61",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/resource.c:iomem_open",
        "kernel/resource.c:ioports_open",
        "kernel/sched/stats.c:schedstat_open",
        "kernel/sched/debug.c:sched_debug_open",
        "kernel/module.c:modules_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_saved_cmdlines_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_printk.c:ftrace_formats_open",
        "kernel/trace/trace_stack.c:stack_trace_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_kprobe.c:profile_open",
        "kernel/trace/trace_kprobe.c:probes_open",
        "kernel/trace/trace_uprobe.c:profile_open",
        "kernel/trace/trace_uprobe.c:probes_open",
        "mm/vmstat.c:zoneinfo_open",
        "mm/vmstat.c:vmstat_open",
        "mm/vmstat.c:pagetypeinfo_open",
        "mm/vmstat.c:fragmentation_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:single_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/proc_tty.c:tty_drivers_open",
        "fs/proc/consoles.c:consoles_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/proc/devices.c:devinfo_open",
        "fs/proc/interrupts.c:interrupts_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/keys/proc.c:proc_key_users_open",
        "security/keys/proc.c:proc_keys_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "crypto/proc.c:crypto_info_open",
        "block/genhd.c:partitions_open",
        "block/genhd.c:diskstats_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/pci/proc.c:proc_bus_pci_dev_open",
        "drivers/video/fbdev/core/fbmem.c:proc_fb_open",
        "drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open",
        "drivers/char/misc.c:misc_seq_open",
        "drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_open",
        "drivers/char/tpm/tpm_eventlog.c:tpm_ascii_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/scsi/sg.c:sg_proc_open_devstrs",
        "drivers/scsi/sg.c:sg_proc_open_dev",
        "drivers/scsi/sg.c:sg_proc_open_debug",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/core/net-procfs.c:softnet_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145008,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310112,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:61",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/resource.c:iomem_open",
        "kernel/resource.c:ioports_open",
        "kernel/sched/stats.c:schedstat_open",
        "kernel/sched/debug.c:sched_debug_open",
        "kernel/module.c:modules_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_saved_cmdlines_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_printk.c:ftrace_formats_open",
        "kernel/trace/trace_stack.c:stack_trace_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_kprobe.c:profile_open",
        "kernel/trace/trace_kprobe.c:probes_open",
        "kernel/trace/trace_uprobe.c:profile_open",
        "kernel/trace/trace_uprobe.c:probes_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/vmstat.c:vmstat_open",
        "mm/vmstat.c:zoneinfo_open",
        "mm/vmstat.c:pagetypeinfo_open",
        "mm/vmstat.c:fragmentation_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/proc_tty.c:tty_drivers_open",
        "fs/proc/consoles.c:consoles_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/proc/devices.c:devinfo_open",
        "fs/proc/interrupts.c:interrupts_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/keys/proc.c:proc_key_users_open",
        "security/keys/proc.c:proc_keys_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "crypto/proc.c:crypto_info_open",
        "block/genhd.c:diskstats_open",
        "block/genhd.c:partitions_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/pci/proc.c:proc_bus_pci_dev_open",
        "drivers/video/fbdev/core/fbmem.c:proc_fb_open",
        "drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open",
        "drivers/char/misc.c:misc_seq_open",
        "drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_open",
        "drivers/char/tpm/tpm_eventlog.c:tpm_ascii_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/scsi/sg.c:sg_proc_open_debug",
        "drivers/scsi/sg.c:sg_proc_open_devstrs",
        "drivers/scsi/sg.c:sg_proc_open_dev",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/core/net-procfs.c:softnet_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310112,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581387936,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:61",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/resource.c:iomem_open",
        "kernel/resource.c:ioports_open",
        "kernel/sched/stats.c:schedstat_open",
        "kernel/sched/debug.c:sched_debug_open",
        "kernel/module.c:modules_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_saved_cmdlines_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_printk.c:ftrace_formats_open",
        "kernel/trace/trace_stack.c:stack_trace_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_kprobe.c:profile_open",
        "kernel/trace/trace_kprobe.c:probes_open",
        "kernel/trace/trace_uprobe.c:profile_open",
        "kernel/trace/trace_uprobe.c:probes_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/vmstat.c:vmstat_open",
        "mm/vmstat.c:zoneinfo_open",
        "mm/vmstat.c:pagetypeinfo_open",
        "mm/vmstat.c:fragmentation_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/proc_tty.c:tty_drivers_open",
        "fs/proc/consoles.c:consoles_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/proc/devices.c:devinfo_open",
        "fs/proc/interrupts.c:interrupts_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/keys/proc.c:proc_key_users_open",
        "security/keys/proc.c:proc_keys_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "crypto/proc.c:crypto_info_open",
        "block/genhd.c:diskstats_open",
        "block/genhd.c:partitions_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/pci/proc.c:proc_bus_pci_dev_open",
        "drivers/video/fbdev/core/fbmem.c:proc_fb_open",
        "drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open",
        "drivers/char/misc.c:misc_seq_open",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/scsi/sg.c:sg_proc_open_debug",
        "drivers/scsi/sg.c:sg_proc_open_devstrs",
        "drivers/scsi/sg.c:sg_proc_open_dev",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/core/net-procfs.c:softnet_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387936,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444192,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:47",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/resource.c:iomem_open",
        "kernel/resource.c:ioports_open",
        "kernel/sched/stats.c:schedstat_open",
        "kernel/sched/debug.c:sched_debug_open",
        "kernel/module.c:modules_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_saved_cmdlines_open",
        "kernel/trace/trace.c:tracing_saved_tgids_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_printk.c:ftrace_formats_open",
        "kernel/trace/trace_stack.c:stack_trace_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_kprobe.c:profile_open",
        "kernel/trace/trace_kprobe.c:probes_open",
        "kernel/trace/trace_uprobe.c:profile_open",
        "kernel/trace/trace_uprobe.c:probes_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/vmstat.c:vmstat_open",
        "mm/vmstat.c:zoneinfo_open",
        "mm/vmstat.c:pagetypeinfo_open",
        "mm/vmstat.c:fragmentation_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/proc_tty.c:tty_drivers_open",
        "fs/proc/consoles.c:consoles_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/proc/devices.c:devinfo_open",
        "fs/proc/interrupts.c:interrupts_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/keys/proc.c:proc_key_users_open",
        "security/keys/proc.c:proc_keys_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "crypto/proc.c:crypto_info_open",
        "block/genhd.c:diskstats_open",
        "block/genhd.c:partitions_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/pci/proc.c:proc_bus_pci_dev_open",
        "drivers/video/fbdev/core/fbmem.c:proc_fb_open",
        "drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open",
        "drivers/char/misc.c:misc_seq_open",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/scsi/sg.c:sg_proc_open_debug",
        "drivers/scsi/sg.c:sg_proc_open_devstrs",
        "drivers/scsi/sg.c:sg_proc_open_dev",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/core/net-procfs.c:softnet_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444192,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586128,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:48",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/resource.c:iomem_open",
        "kernel/resource.c:ioports_open",
        "kernel/sched/stats.c:schedstat_open",
        "kernel/sched/debug.c:sched_debug_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_saved_cmdlines_open",
        "kernel/trace/trace.c:tracing_saved_tgids_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_printk.c:ftrace_formats_open",
        "kernel/trace/trace_stack.c:stack_trace_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_kprobe.c:profile_open",
        "kernel/trace/trace_kprobe.c:probes_open",
        "kernel/trace/trace_uprobe.c:profile_open",
        "kernel/trace/trace_uprobe.c:probes_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/vmstat.c:vmstat_open",
        "mm/vmstat.c:zoneinfo_open",
        "mm/vmstat.c:pagetypeinfo_open",
        "mm/vmstat.c:fragmentation_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/proc_tty.c:tty_drivers_open",
        "fs/proc/consoles.c:consoles_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/proc/devices.c:devinfo_open",
        "fs/proc/interrupts.c:interrupts_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/ext4/mballoc.c:ext4_mb_seq_groups_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/keys/proc.c:proc_key_users_open",
        "security/keys/proc.c:proc_keys_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "crypto/proc.c:crypto_info_open",
        "block/genhd.c:diskstats_open",
        "block/genhd.c:partitions_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/pci/proc.c:proc_bus_pci_dev_open",
        "drivers/video/fbdev/core/fbmem.c:proc_fb_open",
        "drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open",
        "drivers/char/misc.c:misc_seq_open",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/scsi/sg.c:sg_proc_open_debug",
        "drivers/scsi/sg.c:sg_proc_open_devstrs",
        "drivers/scsi/sg.c:sg_proc_open_dev",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/core/net-procfs.c:softnet_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586128,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739488,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_saved_cmdlines_open",
        "kernel/trace/trace.c:tracing_saved_tgids_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_printk.c:ftrace_formats_open",
        "kernel/trace/trace_stack.c:stack_trace_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_events_hist.c:synth_events_open",
        "kernel/trace/trace_kprobe.c:profile_open",
        "kernel/trace/trace_kprobe.c:probes_open",
        "kernel/trace/trace_uprobe.c:profile_open",
        "kernel/trace/trace_uprobe.c:probes_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739488,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826176,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_saved_cmdlines_open",
        "kernel/trace/trace.c:tracing_saved_tgids_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_printk.c:ftrace_formats_open",
        "kernel/trace/trace_stack.c:stack_trace_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_events_hist.c:synth_events_open",
        "kernel/trace/trace_kprobe.c:profile_open",
        "kernel/trace/trace_kprobe.c:probes_open",
        "kernel/trace/trace_dynevent.c:dyn_event_open",
        "kernel/trace/trace_uprobe.c:profile_open",
        "kernel/trace/trace_uprobe.c:probes_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826176,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:tracing_saved_cmdlines_open",
        "kernel/trace/trace.c:tracing_saved_tgids_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_printk.c:ftrace_formats_open",
        "kernel/trace/trace_stack.c:stack_trace_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_events_hist.c:synth_events_open",
        "kernel/trace/trace_kprobe.c:profile_open",
        "kernel/trace/trace_kprobe.c:probes_open",
        "kernel/trace/trace_dynevent.c:dyn_event_open",
        "kernel/trace/trace_uprobe.c:profile_open",
        "kernel/trace/trace_uprobe.c:probes_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956098,
      "name": "seq_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581950352,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023008,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "arch/x86/platform/uv/tlb_uv.c:ptc_proc_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023008,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257664,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:53",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat/memtype.c:memtype_seq_open",
        "arch/x86/platform/uv/tlb_uv.c:ptc_proc_open",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257664,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582306960,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:54",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat/memtype.c:memtype_seq_open",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306960,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582334608,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:57",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat/memtype.c:memtype_seq_open",
        "kernel/sched/debug.c:sched_debug_open",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334608,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655200,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:57",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat/memtype.c:memtype_seq_open",
        "kernel/sched/debug.c:sched_debug_open",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_hwlat.c:hwlat_mode_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "mm/kfence/core.c:open_objects",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655200,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194736,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:57",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat/memtype.c:memtype_seq_open",
        "kernel/sched/build_utility.c:sched_debug_open",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_hwlat.c:hwlat_mode_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "mm/kfence/core.c:open_objects",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194736,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583770432,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:57",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat/memtype.c:memtype_seq_open",
        "kernel/sched/build_utility.c:sched_debug_open",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_hwlat.c:hwlat_mode_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv.c:available_monitors_open",
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_open",
        "kernel/trace/rv/rv_reactors.c:available_reactors_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmscan.c:lru_gen_seq_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770432,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583987600,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:57",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat/memtype.c:memtype_seq_open",
        "kernel/sched/build_utility.c:sched_debug_open",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_hwlat.c:hwlat_mode_open",
        "kernel/trace/trace_osnoise.c:osnoise_options_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_events_user.c:user_status_open",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv.c:available_monitors_open",
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_open",
        "kernel/trace/rv/rv_reactors.c:available_reactors_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmscan.c:lru_gen_seq_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987600,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584200224,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:57",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat/memtype.c:memtype_seq_open",
        "kernel/sched/build_utility.c:sched_debug_open",
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_hwlat.c:hwlat_mode_open",
        "kernel/trace/trace_osnoise.c:osnoise_options_open",
        "kernel/trace/trace_events.c:ftrace_event_set_npid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_pid_open",
        "kernel/trace/trace_events.c:ftrace_event_set_open",
        "kernel/trace/trace_events.c:ftrace_event_avail_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/trace/trace_events_user.c:user_status_open",
        "kernel/trace/rv/rv.c:enabled_monitors_open",
        "kernel/trace/rv/rv.c:available_monitors_open",
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_open",
        "kernel/trace/rv/rv_reactors.c:available_reactors_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmscan.c:lru_gen_seq_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200224,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493545496,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic-debug.c:debug_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493545496,
      "name": "seq_open",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227095084,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227095084,
      "name": "seq_open",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287114800,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287114800,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273208160,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273208160,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991744,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991744,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929312,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929312,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581983024,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983024,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int seq_open(struct file * file, const struct seq_operations * op)
```

```json
{
  "name": "seq_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053488,
      "name": "seq_open",
      "external": true,
      "loc": "fs/seq_file.c:51",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open",
        "arch/x86/mm/pat.c:memtype_seq_open",
        "arch/x86/platform/uv/tlb_uv.c:ptc_proc_open",
        "kernel/kprobes.c:kprobe_blacklist_open",
        "kernel/kprobes.c:kprobes_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_regex_open",
        "kernel/trace/trace.c:tracing_err_log_open",
        "kernel/trace/trace.c:show_traces_open",
        "kernel/trace/trace_stat.c:tracing_stat_open",
        "kernel/trace/trace_events.c:trace_format_open",
        "kernel/trace/trace_events_trigger.c:event_trigger_open",
        "kernel/bpf/inode.c:bpffs_map_open",
        "mm/vmstat.c:extfrag_open",
        "mm/vmstat.c:unusable_open",
        "mm/slab_common.c:slabinfo_open",
        "mm/swapfile.c:swaps_open",
        "fs/seq_file.c:__seq_open_private",
        "fs/seq_file.c:single_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/generic.c:proc_seq_open",
        "fs/proc/array.c:children_seq_open",
        "fs/proc/cpuinfo.c:cpuinfo_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_open",
        "fs/pstore/inode.c:pstore_file_open",
        "security/selinux/selinuxfs.c:sel_open_avc_cache_stats",
        "security/smack/smackfs.c:smk_open_relabel_self",
        "security/smack/smackfs.c:smk_open_load_self2",
        "security/smack/smackfs.c:smk_open_load2",
        "security/smack/smackfs.c:smk_open_load_self",
        "security/smack/smackfs.c:smk_open_onlycap",
        "security/smack/smackfs.c:smk_open_net6addr",
        "security/smack/smackfs.c:smk_open_net4addr",
        "security/smack/smackfs.c:smk_open_cipso2",
        "security/smack/smackfs.c:smk_open_cipso",
        "security/smack/smackfs.c:smk_open_load",
        "security/apparmor/apparmorfs.c:profiles_open",
        "security/integrity/ima/ima_fs.c:ima_ascii_measurements_open",
        "security/integrity/ima/ima_fs.c:ima_measurements_open",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_open",
        "lib/error-inject.c:ei_open",
        "drivers/gpio/gpiolib.c:gpiolib_open",
        "drivers/pwm/core.c:pwm_seq_open",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open",
        "drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open",
        "drivers/scsi/scsi_proc.c:proc_scsi_open",
        "drivers/input/input.c:input_proc_handlers_open",
        "drivers/input/input.c:input_proc_devices_open",
        "drivers/md/md.c:md_seq_open",
        "net/ipv4/route.c:rt_cpu_seq_open",
        "net/ipv4/route.c:rt_cache_seq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053488,
      "name": "seq_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
