# Function: <code>umwait_update_control_msr</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140896,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:32",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140896,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143152,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:38",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143152,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160389,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:33",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160304,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579157413,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:33",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157328,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579164389,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:33",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164304,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579195109,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:33",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195024,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579244229,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:33",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244096,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579304181,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:33",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304016,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579311365,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:33",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311200,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579342117,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:33",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341952,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143520,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:38",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143520,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579075445,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:38",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075328,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143072,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:38",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143072,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void umwait_update_control_msr(void * unused)
```

```json
{
  "name": "umwait_update_control_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148208,
      "name": "umwait_update_control_msr",
      "external": false,
      "loc": "arch/x86/kernel/cpu/umwait.c:38",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148208,
      "name": "umwait_update_control_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void umwait_update_control_msr(void * unused)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void umwait_update_control_msr(void * unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void umwait_update_control_msr(void * unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void umwait_update_control_msr(void * unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void umwait_update_control_msr(void * unused)
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
