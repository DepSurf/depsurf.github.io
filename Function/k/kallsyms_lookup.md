# Function: <code>kallsyms_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939552,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:292",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/stop_machine.c:cpu_stopper_thread",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939552,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579970352,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:316",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970352,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580000832,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:316",
      "file": "kernel/kallsyms.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:__unregister_ftrace_function_probe",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000832,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007792,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:312",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007792,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054416,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:313",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054416,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111472,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:278",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111472,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157840,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:278",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157840,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580203904,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203904,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252240,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252240,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320736,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:280",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/bpf/btf.c:__btf_resolve_helper_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320736,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305872,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305872,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309408,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:311",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309408,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463488,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:356",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463488,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580656624,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:380",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_match_record",
        "kernel/trace/ftrace.c:print_rec",
        "kernel/trace/ftrace.c:test_for_valid_rec",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656624,
      "name": "kallsyms_lookup",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926128,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:453",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_match_record",
        "kernel/trace/ftrace.c:print_rec",
        "kernel/trace/ftrace.c:test_for_valid_rec",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926128,
      "name": "kallsyms_lookup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014208,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:448",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_match_record",
        "kernel/trace/ftrace.c:print_rec",
        "kernel/trace/ftrace.c:test_for_valid_rec",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014208,
      "name": "kallsyms_lookup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110080,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:446",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_match_record",
        "kernel/trace/ftrace.c:print_rec",
        "kernel/trace/ftrace.c:test_for_valid_rec",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:trace_seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110080,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491494408,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491494408,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225476040,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:save_ftrace_mod_rec",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:ftrace_match_record",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225476040,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284452640,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/xmon/xmon.c:xmon_print_symbol",
        "arch/powerpc/xmon/xmon.c:get_function_bounds",
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284452640,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271937636,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271937636,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580221040,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221040,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580168480,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168480,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212512,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212512,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
const char * kallsyms_lookup(long unsigned int addr, long unsigned int * symbolsize, long unsigned int * offset, char * * modname, char * namebuf)
```

```json
{
  "name": "kallsyms_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580265216,
      "name": "kallsyms_lookup",
      "external": true,
      "loc": "kernel/kallsyms.c:281",
      "file": "kernel/kallsyms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kallsyms.c:__sprint_symbol",
        "kernel/kprobes.c:show_kprobe_addr",
        "kernel/debug/kdb/kdb_support.c:kdbnearsym",
        "kernel/trace/ftrace.c:unregister_ftrace_function_probe_func",
        "kernel/trace/ftrace.c:function_stat_show",
        "kernel/trace/trace_output.c:seq_print_sym",
        "kernel/trace/trace_syscalls.c:find_syscall_meta"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580265216,
      "name": "kallsyms_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
