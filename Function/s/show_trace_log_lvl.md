# Function: <code>show_trace_log_lvl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, long unsigned int bp, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049792,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:170",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049792,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, long unsigned int bp, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579046108,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:178",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579045984,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044384,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:51",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_regs",
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044384,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579036912,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:53",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_regs",
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579036912,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579045072,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:105",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_regs",
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579045072,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049914,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:171",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049914,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054719,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:162",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054719,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062520,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:162",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062520,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064616,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:162",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064616,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, const char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072959,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:169",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072959,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, const char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591245182,
      "name": "show_trace_log_lvl",
      "external": false,
      "loc": "arch/x86/kernel/dumpstack.c:186",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591245182,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, const char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591188976,
      "name": "show_trace_log_lvl",
      "external": false,
      "loc": "arch/x86/kernel/dumpstack.c:186",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188976,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, const char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592052538,
      "name": "show_trace_log_lvl",
      "external": false,
      "loc": "arch/x86/kernel/dumpstack.c:186",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592052538,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, const char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593819280,
      "name": "show_trace_log_lvl",
      "external": false,
      "loc": "arch/x86/kernel/dumpstack.c:180",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593819280,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, const char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579178544,
      "name": "show_trace_log_lvl",
      "external": false,
      "loc": "arch/x86/kernel/dumpstack.c:186",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178544,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1025
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, const char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181968,
      "name": "show_trace_log_lvl",
      "external": false,
      "loc": "arch/x86/kernel/dumpstack.c:186",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181968,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, const char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211184,
      "name": "show_trace_log_lvl",
      "external": false,
      "loc": "arch/x86/kernel/dumpstack.c:186",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211184,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064968,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:162",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064968,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578997720,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:162",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578997720,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064552,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:162",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064552,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```

```json
{
  "name": "show_trace_log_lvl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068616,
      "name": "show_trace_log_lvl",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:162",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_stack_regs",
        "arch/x86/kernel/dumpstack.c:show_stack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068616,
      "name": "show_trace_log_lvl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 750
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int bp</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, regs, stack, bp, log_lvl</code> ➡️ <code>task, regs, stack, log_lvl</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * log_lvl</code> ➡️ <code>const char * log_lvl</code>
</li>
</ul>
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void show_trace_log_lvl(struct task_struct * task, struct pt_regs * regs, long unsigned int * stack, char * log_lvl)
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
