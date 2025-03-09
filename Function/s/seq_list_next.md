# Function: <code>seq_list_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140624,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:822",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/ftrace.c:fpid_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_kprobe.c:probes_seq_next",
        "kernel/trace/trace_uprobe.c:probes_seq_next",
        "mm/slab_common.c:slab_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140624,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306144,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:825",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_kprobe.c:probes_seq_next",
        "kernel/trace/trace_uprobe.c:probes_seq_next",
        "mm/slab_common.c:slab_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306144,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581385168,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:863",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_kprobe.c:probes_seq_next",
        "kernel/trace/trace_uprobe.c:probes_seq_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385168,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581440432,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:849",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_kprobe.c:probes_seq_next",
        "kernel/trace/trace_uprobe.c:probes_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/blk-mq-debugfs.c:ctx_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440432,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582304,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:853",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_kprobe.c:probes_seq_next",
        "kernel/trace/trace_uprobe.c:probes_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/blk-mq-debugfs.c:ctx_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582304,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739296,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_events_hist.c:synth_events_seq_next",
        "kernel/trace/trace_kprobe.c:probes_seq_next",
        "kernel/trace/trace_uprobe.c:probes_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/blk-mq-debugfs.c:ctx_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739296,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825984,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:905",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825984,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581950160,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950160,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582022816,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022816,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257504,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:893",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257504,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582306800,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:909",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306800,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582334416,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:931",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334416,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655008,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:940",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch2_next",
        "block/mq-deadline.c:deadline_dispatch1_next",
        "block/mq-deadline.c:deadline_dispatch0_next",
        "block/mq-deadline.c:deadline_write2_fifo_next",
        "block/mq-deadline.c:deadline_read2_fifo_next",
        "block/mq-deadline.c:deadline_write1_fifo_next",
        "block/mq-deadline.c:deadline_read1_fifo_next",
        "block/mq-deadline.c:deadline_write0_fifo_next",
        "block/mq-deadline.c:deadline_read0_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655008,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583194400,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:924",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/procfs.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch2_next",
        "block/mq-deadline.c:deadline_dispatch1_next",
        "block/mq-deadline.c:deadline_dispatch0_next",
        "block/mq-deadline.c:deadline_write2_fifo_next",
        "block/mq-deadline.c:deadline_read2_fifo_next",
        "block/mq-deadline.c:deadline_write1_fifo_next",
        "block/mq-deadline.c:deadline_read1_fifo_next",
        "block/mq-deadline.c:deadline_write0_fifo_next",
        "block/mq-deadline.c:deadline_read0_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194400,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583770000,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:924",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/procfs.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "kernel/trace/rv/rv.c:available_monitors_next",
        "kernel/trace/rv/rv_reactors.c:reactors_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch2_next",
        "block/mq-deadline.c:deadline_dispatch1_next",
        "block/mq-deadline.c:deadline_dispatch0_next",
        "block/mq-deadline.c:deadline_write2_fifo_next",
        "block/mq-deadline.c:deadline_read2_fifo_next",
        "block/mq-deadline.c:deadline_write1_fifo_next",
        "block/mq-deadline.c:deadline_read1_fifo_next",
        "block/mq-deadline.c:deadline_write0_fifo_next",
        "block/mq-deadline.c:deadline_read0_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770000,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583987168,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:924",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/procfs.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "kernel/trace/rv/rv.c:available_monitors_next",
        "kernel/trace/rv/rv_reactors.c:reactors_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch2_next",
        "block/mq-deadline.c:deadline_dispatch1_next",
        "block/mq-deadline.c:deadline_dispatch0_next",
        "block/mq-deadline.c:deadline_write2_fifo_next",
        "block/mq-deadline.c:deadline_read2_fifo_next",
        "block/mq-deadline.c:deadline_write1_fifo_next",
        "block/mq-deadline.c:deadline_read1_fifo_next",
        "block/mq-deadline.c:deadline_write0_fifo_next",
        "block/mq-deadline.c:deadline_read0_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987168,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584199792,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:924",
      "file": "fs/seq_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/procfs.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "kernel/trace/rv/rv.c:available_monitors_next",
        "kernel/trace/rv/rv_reactors.c:reactors_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch2_next",
        "block/mq-deadline.c:deadline_dispatch1_next",
        "block/mq-deadline.c:deadline_dispatch0_next",
        "block/mq-deadline.c:deadline_write2_fifo_next",
        "block/mq-deadline.c:deadline_read2_fifo_next",
        "block/mq-deadline.c:deadline_write1_fifo_next",
        "block/mq-deadline.c:deadline_read1_fifo_next",
        "block/mq-deadline.c:deadline_write0_fifo_next",
        "block/mq-deadline.c:deadline_read0_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "drivers/md/md.c:md_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199792,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493545080,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493545080,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227094756,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227094756,
      "name": "seq_list_next",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287114496,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287114496,
      "name": "seq_list_next",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273207814,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273207814,
      "name": "seq_list_next",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991552,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991552,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929120,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929120,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581982832,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982832,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct list_head * seq_list_next(void * v, struct list_head * head, loff_t * ppos)
```

```json
{
  "name": "seq_list_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053296,
      "name": "seq_list_next",
      "external": true,
      "loc": "fs/seq_file.c:917",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:m_next",
        "kernel/kprobes.c:kprobe_blacklist_seq_next",
        "kernel/trace/trace.c:tracing_err_log_seq_next",
        "kernel/trace/trace_events_trigger.c:trigger_next",
        "kernel/trace/trace_dynevent.c:dyn_event_seq_next",
        "mm/slab_common.c:memcg_slab_next",
        "mm/slab_common.c:slab_next",
        "mm/vmalloc.c:s_next",
        "fs/namespace.c:m_next",
        "fs/namespace.c:m_start",
        "fs/proc/base.c:timers_next",
        "fs/proc/proc_tty.c:t_next",
        "crypto/proc.c:c_next",
        "block/mq-deadline.c:deadline_dispatch_next",
        "block/mq-deadline.c:deadline_write_fifo_next",
        "block/mq-deadline.c:deadline_read_fifo_next",
        "block/blk-mq-debugfs.c:ctx_poll_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_read_rq_list_next",
        "block/blk-mq-debugfs.c:ctx_default_rq_list_next",
        "block/blk-mq-debugfs.c:hctx_dispatch_next",
        "block/blk-mq-debugfs.c:queue_requeue_list_next",
        "lib/error-inject.c:ei_seq_next",
        "drivers/pwm/core.c:pwm_seq_next",
        "drivers/char/misc.c:misc_seq_next",
        "drivers/input/input.c:input_handlers_seq_next",
        "drivers/input/input.c:input_devices_seq_next",
        "net/core/sock.c:proto_seq_next"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053296,
      "name": "seq_list_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
