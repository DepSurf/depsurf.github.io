# Function: <code>set_memory_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300720,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1708",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300720,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300358,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1716",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "kernel/power/snapshot.c:swsusp_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300048,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579315830,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1716",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "arch/x86/net/bpf_jit_comp.c:bpf_jit_free",
        "kernel/power/snapshot.c:swsusp_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315520,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579313126,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1762",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312864,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579335766,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1762",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335504,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346789,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1792",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346320,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579373333,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1985",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372864,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579388405,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1996",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387936,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579391733,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1902",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391264,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431957,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1938",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431488,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431429,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1938",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430960,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579434389,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1946",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433920,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579498613,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1946",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498144,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579580019,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:1983",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579440,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579689507,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2089",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_init_pages",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688816,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579703269,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2090",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_initrd_mem",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702576,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579737877,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pat/set_memory.c:2089",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/mm/init.c:free_initrd_mem",
        "kernel/power/snapshot.c:swsusp_free",
        "kernel/bpf/trampoline.c:arch_unprotect_bpf_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737104,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490353592,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/arm64/mm/pageattr.c:118",
      "file": "arch/arm64/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490353592,
      "name": "set_memory_rw",
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224501688,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/arm/mm/pageattr.c:71",
      "file": "arch/arm/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/plat-omap/sram.c:omap_sram_push",
        "kernel/power/snapshot.c:swsusp_free",
        "drivers/misc/sram-exec.c:sram_exec_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224501688,
      "name": "set_memory_rw",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387637,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1902",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387168,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579316997,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1902",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316528,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387557,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1902",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387088,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int set_memory_rw(long unsigned int addr, int numpages)
```

```json
{
  "name": "set_memory_rw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579396069,
      "name": "set_memory_rw",
      "external": true,
      "loc": "arch/x86/mm/pageattr.c:1902",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:set_pages_rw"
      ],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/mm/init.c:free_init_pages",
        "arch/x86/mm/init_64.c:set_kernel_text_rw",
        "kernel/power/snapshot.c:swsusp_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395600,
      "name": "set_memory_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages)
```
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
