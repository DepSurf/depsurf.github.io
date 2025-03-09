# Function: <code>seq_list_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581140576,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:801",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/ftrace.c:fpid_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_kprobe.c:probes_seq_start",
        "kernel/trace/trace_uprobe.c:probes_seq_start",
        "mm/slab_common.c:slab_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140576,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581306096,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:804",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_kprobe.c:probes_seq_start",
        "kernel/trace/trace_uprobe.c:probes_seq_start",
        "mm/slab_common.c:slab_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306096,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581385120,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:842",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_kprobe.c:probes_seq_start",
        "kernel/trace/trace_uprobe.c:probes_seq_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385120,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581440384,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:828",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_kprobe.c:probes_seq_start",
        "kernel/trace/trace_uprobe.c:probes_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/blk-mq-debugfs.c:ctx_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440384,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581582256,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:832",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_kprobe.c:probes_seq_start",
        "kernel/trace/trace_uprobe.c:probes_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/blk-mq-debugfs.c:ctx_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582256,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581739248,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_events_hist.c:synth_events_seq_start",
        "kernel/trace/trace_kprobe.c:probes_seq_start",
        "kernel/trace/trace_uprobe.c:probes_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/blk-mq-debugfs.c:ctx_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739248,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581825936,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:884",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825936,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581950112,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950112,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582022768,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022768,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582257456,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:872",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257456,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582306752,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:888",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306752,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582334368,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:910",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334368,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582654960,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:919",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch2_start",
        "block/mq-deadline.c:deadline_dispatch1_start",
        "block/mq-deadline.c:deadline_dispatch0_start",
        "block/mq-deadline.c:deadline_write2_fifo_start",
        "block/mq-deadline.c:deadline_read2_fifo_start",
        "block/mq-deadline.c:deadline_write1_fifo_start",
        "block/mq-deadline.c:deadline_read1_fifo_start",
        "block/mq-deadline.c:deadline_write0_fifo_start",
        "block/mq-deadline.c:deadline_read0_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654960,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583194336,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:903",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/procfs.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch2_start",
        "block/mq-deadline.c:deadline_dispatch1_start",
        "block/mq-deadline.c:deadline_dispatch0_start",
        "block/mq-deadline.c:deadline_write2_fifo_start",
        "block/mq-deadline.c:deadline_read2_fifo_start",
        "block/mq-deadline.c:deadline_write1_fifo_start",
        "block/mq-deadline.c:deadline_read1_fifo_start",
        "block/mq-deadline.c:deadline_write0_fifo_start",
        "block/mq-deadline.c:deadline_read0_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194336,
      "name": "seq_list_start",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583769920,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:903",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/procfs.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "kernel/trace/rv/rv.c:available_monitors_start",
        "kernel/trace/rv/rv_reactors.c:reactors_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch2_start",
        "block/mq-deadline.c:deadline_dispatch1_start",
        "block/mq-deadline.c:deadline_dispatch0_start",
        "block/mq-deadline.c:deadline_write2_fifo_start",
        "block/mq-deadline.c:deadline_read2_fifo_start",
        "block/mq-deadline.c:deadline_write1_fifo_start",
        "block/mq-deadline.c:deadline_read1_fifo_start",
        "block/mq-deadline.c:deadline_write0_fifo_start",
        "block/mq-deadline.c:deadline_read0_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769920,
      "name": "seq_list_start",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583987088,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:903",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/procfs.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "kernel/trace/rv/rv.c:available_monitors_start",
        "kernel/trace/rv/rv_reactors.c:reactors_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch2_start",
        "block/mq-deadline.c:deadline_dispatch1_start",
        "block/mq-deadline.c:deadline_dispatch0_start",
        "block/mq-deadline.c:deadline_write2_fifo_start",
        "block/mq-deadline.c:deadline_read2_fifo_start",
        "block/mq-deadline.c:deadline_write1_fifo_start",
        "block/mq-deadline.c:deadline_read1_fifo_start",
        "block/mq-deadline.c:deadline_write0_fifo_start",
        "block/mq-deadline.c:deadline_read0_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987088,
      "name": "seq_list_start",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584199712,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:903",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/procfs.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "kernel/trace/rv/rv.c:available_monitors_start",
        "kernel/trace/rv/rv_reactors.c:reactors_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch2_start",
        "block/mq-deadline.c:deadline_dispatch1_start",
        "block/mq-deadline.c:deadline_dispatch0_start",
        "block/mq-deadline.c:deadline_write2_fifo_start",
        "block/mq-deadline.c:deadline_read2_fifo_start",
        "block/mq-deadline.c:deadline_write1_fifo_start",
        "block/mq-deadline.c:deadline_read1_fifo_start",
        "block/mq-deadline.c:deadline_write0_fifo_start",
        "block/mq-deadline.c:deadline_read0_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199712,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493544992,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493544992,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227094672,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227094672,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287114416,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287114416,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273207750,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273207750,
      "name": "seq_list_start",
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581991504,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991504,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581929072,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929072,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581982784,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982784,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
struct list_head * seq_list_start(struct list_head * head, loff_t pos)
```

```json
{
  "name": "seq_list_start",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582053248,
      "name": "seq_list_start",
      "external": true,
      "loc": "fs/seq_file.c:896",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_start",
        "kernel/kprobes.c:kprobe_blacklist_seq_start",
        "kernel/trace/trace.c:tracing_err_log_seq_start",
        "kernel/trace/trace_events_trigger.c:trigger_start",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_start",
        "mm/slab_common.c:memcg_slab_start",
        "mm/slab_common.c:slab_start",
        "mm/vmalloc.c:s_start",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_start",
        "fs/proc/proc_tty.c:t_start",
        "crypto/proc.c:c_start",
        "block/mq-deadline.c:deadline_dispatch_start",
        "block/mq-deadline.c:deadline_write_fifo_start",
        "block/mq-deadline.c:deadline_read_fifo_start",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_start",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_start",
        "block/blk-mq-debugfs.c:hctx_dispatch_start",
        "block/blk-mq-debugfs.c:queue_requeue_list_start",
        "lib/error-inject.c:ei_seq_start",
        "drivers/pwm/core.c:pwm_seq_start",
        "drivers/char/misc.c:misc_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053248,
      "name": "seq_list_start",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
