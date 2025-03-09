# Function: <code>force_sig_mceerr</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int force_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579500512,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1532",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500512,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int force_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534128,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1618",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534128,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1706",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570130,
      "name": "force_sig_mceerr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579559216,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585344,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585344,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621376,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1707",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621376,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601680,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1708",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601680,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607184,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1710",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607184,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682448,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1747",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682448,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777360,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1748",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777360,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909904,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1749",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909904,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959696,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1755",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959696,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998944,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1746",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "mm/memory-failure.c:kill_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998944,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490749072,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:arm64_force_sig_mceerr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490749072,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224798244,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224798244,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283574064,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283574064,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271452108,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271452108,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561648,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561648,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490304,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490304,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558928,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558928,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int force_sig_mceerr(int code, void * addr, short int lsb)
```

```json
{
  "name": "force_sig_mceerr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592320,
      "name": "force_sig_mceerr",
      "external": true,
      "loc": "kernel/signal.c:1711",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592320,
      "name": "force_sig_mceerr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int force_sig_mceerr(int code, void * addr, short int lsb, struct task_struct * t)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * t</code>
</li>
</ul>
</details>
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
