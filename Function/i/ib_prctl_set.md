# Function: <code>ib_prctl_set</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579128288,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:818",
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
      "addr": 18446744071579127488,
      "name": "ib_prctl_set.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579139260,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1026",
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
      "addr": 18446744071579138288,
      "name": "ib_prctl_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579141388,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1156",
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
      "addr": 18446744071579140400,
      "name": "ib_prctl_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579156722,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1263",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153705,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1265",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ib_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579161310,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1265",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160048,
      "name": "ib_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int ib_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579191822,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1405",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579190368,
      "name": "ib_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int ib_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238528,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1907",
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
      "addr": 18446744071579238528,
      "name": "ib_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int ib_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297648,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1956",
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
      "addr": 18446744071579297648,
      "name": "ib_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int ib_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579303760,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2067",
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
      "addr": 18446744071579303760,
      "name": "ib_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int ib_prctl_set(struct task_struct * task, long unsigned int ctrl)
```

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334512,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2208",
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
      "addr": 18446744071579334512,
      "name": "ib_prctl_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579141756,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1156",
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
      "addr": 18446744071579140768,
      "name": "ib_prctl_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579072988,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1156",
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
      "addr": 18446744071579071920,
      "name": "ib_prctl_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579141308,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1156",
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
      "addr": 18446744071579140320,
      "name": "ib_prctl_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ib_prctl_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579146444,
      "name": "ib_prctl_set",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1156",
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
      "addr": 18446744071579145456,
      "name": "ib_prctl_set.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int ib_prctl_set(struct task_struct * task, long unsigned int ctrl)
```
</details>
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
