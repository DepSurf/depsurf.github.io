# Function: <code>access_process_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688080,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:3740",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "kernel/ptrace.c:ptrace_readdata",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688080,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801536,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:3935",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801536,
      "name": "access_process_vm",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866592,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4014",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866592,
      "name": "access_process_vm",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580911584,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4304",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911584,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010400,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4482",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010400,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144048,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4530",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144048,
      "name": "access_process_vm",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223872,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4320",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223872,
      "name": "access_process_vm",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581297552,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4375",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297552,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356320,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356320,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553904,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4765",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:is_setting_trap_flag",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553904,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598640,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4992",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:is_setting_trap_flag",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598640,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621488,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:5059",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621488,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888896,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:5205",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888896,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582286832,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:5512",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_copy_from_user_task",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582286832,
      "name": "access_process_vm",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582779520,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:5592",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_single_step",
        "kernel/bpf/helpers.c:bpf_copy_from_user_task",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779520,
      "name": "access_process_vm",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995968,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:5798",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_single_step",
        "kernel/bpf/helpers.c:bpf_copy_from_user_task",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995968,
      "name": "access_process_vm",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583128592,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:6022",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_single_step",
        "kernel/bpf/helpers.c:bpf_copy_from_user_task",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583128592,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492759752,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492759752,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226583492,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226583492,
      "name": "access_process_vm",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286124464,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286124464,
      "name": "access_process_vm",
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272740624,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272740624,
      "name": "access_process_vm",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581325168,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581325168,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268928,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268928,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316368,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316368,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int access_process_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "access_process_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581380336,
      "name": "access_process_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/step.c:enable_step",
        "mm/util.c:get_cmdline",
        "mm/util.c:get_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380336,
      "name": "access_process_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
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
