# Function: <code>module_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240848,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:78",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240848,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240352,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:79",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240352,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579252800,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:79",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252800,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248560,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:79",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248560,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579265248,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:80",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265248,
      "name": "module_alloc",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276432,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:80",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276432,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300320,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:80",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300320,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579316928,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316928,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320960,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320960,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350432,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:move_module",
        "kernel/module.c:move_module",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350432,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350272,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:move_module",
        "kernel/module.c:move_module",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350272,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579354912,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:move_module",
        "kernel/module.c:move_module",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579354912,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412544,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:move_module",
        "kernel/module.c:move_module",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412544,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579479504,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module/main.c:move_module",
        "kernel/module/main.c:move_module",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579479504,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572336,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module/main.c:move_module",
        "kernel/module/main.c:move_module",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572336,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584688,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module/main.c:move_module",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec",
        "kernel/bpf/core.c:bpf_prog_pack_alloc",
        "kernel/bpf/core.c:alloc_new_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584688,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614480,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module/main.c:move_module",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614480,
      "name": "module_alloc",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490295000,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/arm64/kernel/module.c:22",
      "file": "arch/arm64/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490295000,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224438732,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/arm/kernel/module.c:38",
      "file": "arch/arm/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224438732,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284432848,
      "name": "module_alloc",
      "external": true,
      "loc": "kernel/module.c:2809",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284432848,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 52
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271354258,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/riscv/kernel/module.c:397",
      "file": "arch/riscv/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271354258,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579316864,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316864,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579251456,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251456,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579316784,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316784,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void * module_alloc(long unsigned int size)
```

```json
{
  "name": "module_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579325072,
      "name": "module_alloc",
      "external": true,
      "loc": "arch/x86/kernel/module.c:68",
      "file": "arch/x86/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline",
        "arch/x86/kernel/kprobes/core.c:alloc_insn_page",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/kprobes.c:alloc_insn_page",
        "kernel/bpf/core.c:bpf_jit_alloc_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325072,
      "name": "module_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
