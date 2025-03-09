# Function: <code>trace_seq_putc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580243152,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:235",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/trace_events.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580243152,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580280832,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:235",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_events.c:trace_event_buffer_commit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280832,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580324464,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:235",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324464,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580336704,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:235",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336704,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580390096,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:235",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580390096,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580451936,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:235",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580451936,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580507488,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507488,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580564480,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564480,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580611584,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611584,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580710112,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:233",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:output_printk",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710112,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580699616,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:233",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:output_printk",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699616,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580704224,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:233",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704224,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580881872,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:233",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_osnoise_print",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881872,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581113472,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:233",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_osnoise_print",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_tf_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_tf_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_host_stat",
        "drivers/ata/libata-trace.c:libata_trace_parse_host_stat",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113472,
      "name": "trace_seq_putc",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581422592,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:233",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_osnoise_print",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_tf_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_tf_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_host_stat",
        "drivers/ata/libata-trace.c:libata_trace_parse_host_stat",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422592,
      "name": "trace_seq_putc",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581519296,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:234",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_osnoise_print",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:print_array",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_probe.c:trace_probe_print_args",
        "kernel/trace/trace_probe.c:trace_probe_print_args",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_fprobe.c:print_fexit_event",
        "kernel/trace/trace_fprobe.c:print_fexit_event",
        "kernel/trace/trace_fprobe.c:print_fentry_event",
        "kernel/trace/trace_fprobe.c:print_fentry_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_tf_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_tf_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_host_stat",
        "drivers/ata/libata-trace.c:libata_trace_parse_host_stat",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519296,
      "name": "trace_seq_putc",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581630880,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:231",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_osnoise_print",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:print_array",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_hex_dump_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_comment",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_exit",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_eprobe.c:print_eprobe_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_events_synth.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_probe.c:trace_probe_print_args",
        "kernel/trace/trace_probe.c:trace_probe_print_args",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_fprobe.c:print_fexit_event",
        "kernel/trace/trace_fprobe.c:print_fexit_event",
        "kernel/trace/trace_fprobe.c:print_fentry_event",
        "kernel/trace/trace_fprobe.c:print_fentry_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_tf_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_tf_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_host_stat",
        "drivers/ata/libata-trace.c:libata_trace_parse_host_stat",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630880,
      "name": "trace_seq_putc",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491911696,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491911696,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225854480,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq_u64",
        "kernel/trace/trace_output.c:trace_print_flags_seq_u64",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225854480,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285002688,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285002688,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272197466,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272197466,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580580384,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/nvme/host/trace.c:nvme_trace_disk_name",
        "drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580384,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580527008,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/nvme/host/trace.c:nvme_trace_disk_name",
        "drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_fabrics_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_nvm_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/nvme/host/trace.c:nvme_trace_parse_admin_cmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527008,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580571632,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571632,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void trace_seq_putc(struct trace_seq * s, unsigned char c)
```

```json
{
  "name": "trace_seq_putc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580628368,
      "name": "trace_seq_putc",
      "external": true,
      "loc": "kernel/trace/trace_seq.c:236",
      "file": "kernel/trace/trace_seq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_print_entry_header",
        "kernel/trace/trace.c:trace_event_buffer_commit",
        "kernel/trace/trace_output.c:trace_raw_data",
        "kernel/trace/trace_output.c:trace_hwlat_print",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/trace/trace_output.c:trace_stack_print",
        "kernel/trace/trace_output.c:trace_fn_trace",
        "kernel/trace/trace_output.c:trace_print_lat_fmt",
        "kernel/trace/trace_output.c:seq_print_ip_sym",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_array_seq",
        "kernel/trace/trace_output.c:trace_print_hex_seq",
        "kernel/trace/trace_output.c:trace_print_bitmask_seq",
        "kernel/trace/trace_output.c:trace_print_symbols_seq",
        "kernel/trace/trace_output.c:trace_print_flags_seq",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_function_flags",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_entry",
        "kernel/trace/trace_functions_graph.c:print_graph_prologue",
        "kernel/trace/trace_functions_graph.c:trace_print_graph_duration",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_irq",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/trace_functions_graph.c:print_graph_proc",
        "kernel/trace/blktrace.c:print_one_line",
        "kernel/trace/blktrace.c:blk_log_dump_pdu",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_syscalls.c:print_syscall_enter",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_events_hist.c:print_synth_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kretprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_kprobe.c:print_kprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "kernel/trace/trace_uprobe.c:print_uprobe_event",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/scsi/scsi_trace.c:scsi_trace_parse_cdb",
        "drivers/ata/libata-trace.c:libata_trace_parse_subcmd",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_qc_flags",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_err_mask",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_eh_action",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/ata/libata-trace.c:libata_trace_parse_status",
        "drivers/firmware/efi/cper.c:cper_mem_err_unpack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628368,
      "name": "trace_seq_putc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
