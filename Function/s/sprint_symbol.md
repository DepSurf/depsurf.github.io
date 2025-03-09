# Function: <code>sprint_symbol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579940032,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:394",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:__print_symbol"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940032,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579970870,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:418",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:__print_symbol"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_trigger_entry_print",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970832,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580001350,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:418",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:__print_symbol"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_trigger_entry_print",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001312,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580008342,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:420",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:__print_symbol"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_trigger_entry_print",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008304,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055014,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:425",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:__print_symbol"
      ],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_trigger_entry_print",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054976,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112000,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:390",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:hist_trigger_entry_print",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112000,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158352,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:390",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_events_hist.c:hist_trigger_entry_print",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158352,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204416,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204416,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252752,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252752,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580321280,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:392",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_events_hist.c:hist_trigger_print_key",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321280,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306416,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_events_hist.c:hist_trigger_print_key",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306416,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309952,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:444",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_events_hist.c:hist_trigger_print_key",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309952,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580462864,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:471",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_events_hist.c:hist_trigger_print_key",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462864,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580655856,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:495",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580655856,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580924224,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:568",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924224,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012608,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:535",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012608,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581108480,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:533",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108480,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491495024,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491495024,
      "name": "sprint_symbol",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225476632,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225476632,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284453456,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284453456,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271938096,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271938096,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580221552,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221552,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580168992,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168992,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213024,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213024,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int sprint_symbol(char * buffer, long unsigned int address)
```

```json
{
  "name": "sprint_symbol",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265728,
      "name": "sprint_symbol",
      "external": true,
      "loc": "kernel/kallsyms.c:393",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:seq_print_sym",
        "lib/vsprintf.c:symbol_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265728,
      "name": "sprint_symbol",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
