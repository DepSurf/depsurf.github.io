# Function: <code>arch_seccomp_spec_mitigate</code>

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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121984,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:599",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121984,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579128240,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:870",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579128240,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139200,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1078",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139200,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141328,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1208",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141328,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156672,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1322",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_strict",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156672,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579153920,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1333",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_strict",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153920,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579161264,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1333",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161264,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191776,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1475",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191776,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240240,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1977",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240240,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299728,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2028",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299728,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306080,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2139",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306080,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337024,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2280",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:do_seccomp",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337024,
      "name": "arch_seccomp_spec_mitigate",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491767648,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "kernel/seccomp.c:295",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491767648,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225716036,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "kernel/seccomp.c:295",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225716036,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284812048,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "kernel/seccomp.c:295",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284812048,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 12
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272086960,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "kernel/seccomp.c:295",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272086960,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 26
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141696,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1208",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141696,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072928,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1208",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072928,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141248,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1208",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141248,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
```

```json
{
  "name": "arch_seccomp_spec_mitigate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146384,
      "name": "arch_seccomp_spec_mitigate",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1208",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146384,
      "name": "arch_seccomp_spec_mitigate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void arch_seccomp_spec_mitigate(struct task_struct * task)
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
