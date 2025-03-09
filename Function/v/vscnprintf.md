# Function: <code>vscnprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582996288,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2006",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:early_printk",
        "kernel/kexec_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:verbose",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/clk/clkdev.c:vclkdev_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996288,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583286213,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2143",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/kexec_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:verbose",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/clk/clkdev.c:vclkdev_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286000,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583404965,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2171",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/kexec_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:verbose",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583404752,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588261222,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2311",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:verbose",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588261008,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588813238,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2409",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:verbose",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588813024,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589190072,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2395",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189824,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589420984,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2523",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420736,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589878568,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2630",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589878320,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590104488,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104240,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585107640,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2747",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/leds/led-triggers.c:led_trigger_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585106992,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585256824,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2746",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "fs/sysfs/file.c:sysfs_emit_at",
        "fs/sysfs/file.c:sysfs_emit",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/leds/led-triggers.c:led_trigger_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585256176,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585140344,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2877",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "fs/sysfs/file.c:sysfs_emit_at",
        "fs/sysfs/file.c:sysfs_emit",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/leds/led-triggers.c:led_trigger_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585139712,
      "name": "vscnprintf",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585590744,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2896",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "fs/sysfs/file.c:sysfs_emit_at",
        "fs/sysfs/file.c:sysfs_emit",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/leds/led-triggers.c:led_trigger_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585590112,
      "name": "vscnprintf",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586746586,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2881",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/blktrace.c:__blk_trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "fs/sysfs/file.c:sysfs_emit_at",
        "fs/sysfs/file.c:sysfs_emit",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/leds/led-triggers.c:led_trigger_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586745808,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595910234,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2895",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/blktrace.c:__blk_trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "fs/sysfs/file.c:sysfs_emit_at",
        "fs/sysfs/file.c:sysfs_emit",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/leds/led-triggers.c:led_trigger_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595909376,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596427962,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2916",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/blktrace.c:__blk_trace_note_message",
        "kernel/bpf/log.c:bpf_verifier_vlog",
        "fs/sysfs/file.c:sysfs_emit_at",
        "fs/sysfs/file.c:sysfs_emit",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/leds/led-triggers.c:led_trigger_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596427104,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597323322,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2923",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:printk_sprint",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/blktrace.c:__blk_trace_note_message",
        "kernel/bpf/log.c:bpf_verifier_vlog",
        "fs/sysfs/file.c:sysfs_emit_at",
        "fs/sysfs/file.c:sysfs_emit",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc",
        "drivers/leds/led-triggers.c:led_trigger_snprintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597322464,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int vscnprintf(char * buf, size_t size, const char * fmt, va_list args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503882536,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503882176,
      "name": "vscnprintf",
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
int vscnprintf(char * buf, size_t size, const char * fmt, va_list args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236513672,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236513448,
      "name": "vscnprintf",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int vscnprintf(char * buf, size_t size, const char * fmt, va_list args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297750120,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297749904,
      "name": "vscnprintf",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int vscnprintf(char * buf, size_t size, const char * fmt, va_list args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279777158,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279777014,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589706744,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589706496,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589432536,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432288,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590150120,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149872,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int vscnprintf(char * buf, size_t size, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vscnprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590200520,
      "name": "vscnprintf",
      "external": true,
      "loc": "lib/vsprintf.c:2637",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:scnprintf"
      ],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/printk/printk.c:early_printk",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/crash_core.c:vmcoreinfo_append_str",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/verifier.c:bpf_verifier_vlog",
        "drivers/clk/clkdev.c:vclkdev_alloc",
        "drivers/scsi/scsi_logging.c:scmd_printk",
        "drivers/scsi/scsi_logging.c:sdev_prefix_printk",
        "drivers/ata/libata-eh.c:ata_port_desc",
        "drivers/ata/libata-eh.c:ata_ehi_push_desc",
        "drivers/ata/libata-eh.c:__ata_ehi_push_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590200272,
      "name": "vscnprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
