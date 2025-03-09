# Function: <code>ptrace_access_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448144,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:35",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448144,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436112,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:38",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436112,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464384,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:38",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464384,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477888,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:38",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477888,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511216,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:38",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511216,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530816,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530816,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556960,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556960,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579588416,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588416,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568448,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568448,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579573984,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:43",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573984,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579650208,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:43",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650208,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579745168,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:43",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745168,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579876480,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:43",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876480,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579925792,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:44",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925792,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579965120,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:44",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965120,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490712288,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:generic_ptrace_peekdata",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490712288,
      "name": "ptrace_access_vm",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224771932,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:generic_ptrace_peekdata",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224771932,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283535920,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace",
        "arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:generic_ptrace_peekdata",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283535920,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271433088,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:generic_ptrace_peekdata",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271433088,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533264,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533264,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462032,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462032,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530544,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530544,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "ptrace_access_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563616,
      "name": "ptrace_access_vm",
      "external": true,
      "loc": "kernel/ptrace.c:42",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:compat_ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_writedata",
        "kernel/ptrace.c:ptrace_readdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563616,
      "name": "ptrace_access_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int ptrace_access_vm(struct task_struct * tsk, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```
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
