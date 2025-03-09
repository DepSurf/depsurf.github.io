# Function: <code>ssb_prctl_set</code>

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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121248,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:548",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121248,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579128274,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:789",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127440,
      "name": "ssb_prctl_set.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138080,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:987",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138080,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140192,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1117",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140192,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579155504,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1224",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155504,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579152752,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1218",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152752,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579160272,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1218",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160272,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579190592,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1358",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190592,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238816,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1860",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238816,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298048,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1909",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298048,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304176,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2020",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304176,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334928,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2161",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334928,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140560,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1117",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140560,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579071712,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1117",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071712,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140112,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1117",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140112,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ssb_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579145248,
      "name": "ssb_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1117",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145248,
      "name": "ssb_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
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
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ssb_prctl_set(struct task_struct * task, long unsigned int ctrl)
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
