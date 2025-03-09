# Function: <code>module_memfree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923808,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:1972",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "kernel/module.c:do_free_init",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923808,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953712,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2072",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953712,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984720,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2084",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984720,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579990032,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2111",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990032,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036592,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2119",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036592,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094096,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2118",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094096,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141376,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2117",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141376,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2114",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580201394,
      "name": "module_memfree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580188160,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 44
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580236864,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236864,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309104,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2163",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:move_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309104,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294624,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2225",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:move_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294624,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580297328,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2135",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:move_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580297328,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450272,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2137",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:move_module",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_optinsn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450272,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475168,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module/main.c:1124",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:move_module",
        "kernel/module/main.c:free_module",
        "kernel/module/main.c:free_module",
        "kernel/kprobes.c:free_optinsn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475168,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 55
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580723952,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module/main.c:1127",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:move_module",
        "kernel/module/main.c:free_module",
        "kernel/module/main.c:free_module",
        "kernel/kprobes.c:free_optinsn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580723952,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 55
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802480,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module/main.c:1182",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:move_module",
        "kernel/module/main.c:free_module",
        "kernel/module/main.c:free_module",
        "kernel/kprobes.c:free_optinsn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec",
        "kernel/bpf/core.c:bpf_prog_pack_free",
        "kernel/bpf/core.c:bpf_prog_pack_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802480,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 55
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891824,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module/main.c:1182",
      "file": "kernel/module/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:do_free_init",
        "kernel/module/main.c:move_module",
        "kernel/module/main.c:free_module",
        "kernel/module/main.c:free_module",
        "kernel/kprobes.c:free_optinsn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891824,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 55
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491479064,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491479064,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 84
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225461252,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225461252,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 100
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284430272,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284430272,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 80
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271925204,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271925204,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 82
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580205664,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205664,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580153104,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153104,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580197136,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580197136,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
void module_memfree(void * module_region)
```

```json
{
  "name": "module_memfree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580249584,
      "name": "module_memfree",
      "external": true,
      "loc": "kernel/module.c:2171",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free",
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:free_insn_page",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:free_module",
        "kernel/module.c:free_module",
        "kernel/kprobes.c:free_insn_page",
        "kernel/bpf/core.c:bpf_jit_free_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249584,
      "name": "module_memfree",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 39
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
