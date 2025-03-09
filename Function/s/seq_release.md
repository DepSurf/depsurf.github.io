# Function: <code>seq_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581142512,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:365",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:single_release",
        "fs/seq_file.c:seq_release_private"
      ],
      "caller_func": [
        "kernel/sched/debug.c:sched_debug_release",
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/array.c:children_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581142512,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581307295,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:368",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/sched/debug.c:sched_debug_release",
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/array.c:children_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307136,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581386313,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:375",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/sched/debug.c:sched_debug_release",
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/array.c:children_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386160,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581442569,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:361",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/sched/debug.c:sched_debug_release",
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/array.c:children_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442416,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581584521,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:365",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/sched/debug.c:sched_debug_release",
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/array.c:children_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584368,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581740985,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:368",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740448,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581826857,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:356",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826320,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581951033,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950496,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582023689,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023152,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582260633,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:333",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257856,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582311513,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:349",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307120,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582336921,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:352",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334768,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582657401,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:352",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655328,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583197417,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:352",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194880,
      "name": "seq_release",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583773033,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:352",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770592,
      "name": "seq_release",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583990201,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:352",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987760,
      "name": "seq_release",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584202825,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:352",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200384,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493546352,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493545648,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227095792,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227095252,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287115856,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287114992,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273208816,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273208290,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581992425,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991888,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581929993,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929456,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581983705,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983168,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int seq_release(struct inode * inode, struct file * file)
```

```json
{
  "name": "seq_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582054169,
      "name": "seq_release",
      "external": true,
      "loc": "fs/seq_file.c:357",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/seq_file.c:seq_release_private",
        "fs/seq_file.c:single_release"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_release",
        "kernel/trace/ftrace.c:ftrace_graph_release",
        "kernel/trace/ftrace.c:ftrace_regex_release",
        "kernel/trace/trace.c:tracing_err_log_release",
        "kernel/trace/trace.c:show_traces_release",
        "kernel/trace/trace_stat.c:tracing_stat_release",
        "kernel/trace/trace_events.c:ftrace_event_release",
        "kernel/trace/trace_events_trigger.c:event_trigger_release",
        "kernel/bpf/inode.c:bpffs_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/generic.c:proc_seq_release",
        "fs/kernfs/file.c:kernfs_fop_release",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/jbd2/journal.c:jbd2_seq_info_release",
        "security/apparmor/apparmorfs.c:profiles_release",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "block/blk-mq-debugfs.c:blk_mq_debugfs_release",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053632,
      "name": "seq_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
