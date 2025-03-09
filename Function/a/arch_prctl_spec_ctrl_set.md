# Function: <code>arch_prctl_spec_ctrl_set</code>

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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121952,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:587",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121952,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579128000,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:856",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579128000,
      "name": "arch_prctl_spec_ctrl_set",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139056,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1064",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139056,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141184,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1194",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141184,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156432,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1308",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156432,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579153680,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1319",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153680,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579161216,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1319",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161216,
      "name": "arch_prctl_spec_ctrl_set",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191664,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1459",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191664,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240080,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1961",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240080,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299552,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2012",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299552,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305920,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2123",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305920,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579336864,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2264",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336864,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490336032,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/arm64/kernel/ssbd.c:90",
      "file": "arch/arm64/kernel/ssbd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490336032,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int arch_prctl_spec_ctrl_set(struct task_struct * t, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224822564,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "kernel/sys.c:2271",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224822564,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
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
int arch_prctl_spec_ctrl_set(struct task_struct * t, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283611376,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "kernel/sys.c:2271",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283611376,
      "name": "arch_prctl_spec_ctrl_set",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct * t, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271468992,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "kernel/sys.c:2271",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271468992,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141552,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1194",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141552,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072784,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1194",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072784,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141104,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1194",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141104,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```

```json
{
  "name": "arch_prctl_spec_ctrl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146240,
      "name": "arch_prctl_spec_ctrl_set",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1194",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146240,
      "name": "arch_prctl_spec_ctrl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int arch_prctl_spec_ctrl_set(struct task_struct * task, long unsigned int which, long unsigned int ctrl)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
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
