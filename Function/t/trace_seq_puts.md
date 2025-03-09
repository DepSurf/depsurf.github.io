# Function: <code>trace_seq_puts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580243904,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:207",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243904,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580281584,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:207",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281584,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325216,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:207",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325216,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336448,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:207",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336448,
      "name": "trace_seq_puts",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389840,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:207",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389840,
      "name": "trace_seq_puts",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580451776,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:207",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451776,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507248,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507248,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580564240,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564240,
      "name": "trace_seq_puts",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580611344,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611344,
      "name": "trace_seq_puts",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709872,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:205",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_map",
        "kernel/trace/trace_mmiotrace.c:mmio_print_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_mmiotrace.c:mmio_print_pcidev",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709872,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699376,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:205",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_map",
        "kernel/trace/trace_mmiotrace.c:mmio_print_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_mmiotrace.c:mmio_print_pcidev",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699376,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580703984,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:205",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_context",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580703984,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881632,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:205",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_context",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881632,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113152,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:205",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_context",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113152,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422240,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:205",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_context",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422240,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518944,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:206",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:print_event_fields",
        "kernel/trace/trace_output.c:print_array",
        "kernel/trace/trace_output.c:trace_print_context",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "kernel/trace/trace_fprobe.c:print_fexit_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518944,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630512,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:203",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:tracing_read_pipe",
        "kernel/trace/trace.c:s_show",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_func_repeats_print",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:print_event_fields",
        "kernel/trace/trace_output.c:print_array",
        "kernel/trace/trace_output.c:trace_print_context",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_rw",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "kernel/trace/trace_fprobe.c:print_fexit_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630512,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491911472,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491911472,
      "name": "trace_seq_puts",
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225854248,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq_u64",
        "kernel/trace/trace_output.c:trace_print_flags_seq_u64",
        "kernel/trace/trace_output.c:trace_print_flags_seq_u64",
        "kernel/trace/trace_output.c:trace_print_flags_seq_u64",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225854248,
      "name": "trace_seq_puts",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285002336,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285002336,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272197962,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272197962,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580144,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580144,
      "name": "trace_seq_puts",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580526768,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526768,
      "name": "trace_seq_puts",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571392,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571392,
      "name": "trace_seq_puts",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void trace_seq_puts(struct trace_seq * s, const char * str)
```

```json
{
  "name": "trace_seq_puts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628128,
      "name": "trace_seq_puts",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:208",
      "file": "kernel/trace/trace_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_bprint_print",
        "kernel/trace/trace_output.c:trace_bputs_raw",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_bputs_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_printk_msg_only",
        "kernel/trace/trace_output.c:trace_print_bputs_msg_only",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_print_line",
        "kernel/trace/trace_mmiotrace.c:mmio_read",
        "kernel/trace/trace_mmiotrace.c:mmio_pipe_open",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events_filter.c:print_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:print_event_filter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_probe.c:print_type_string",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628128,
      "name": "trace_seq_puts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
