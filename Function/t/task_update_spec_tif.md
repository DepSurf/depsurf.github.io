# Function: <code>task_update_spec_tif</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void task_update_spec_tif(struct task_struct * tsk)
```

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127392,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:772",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127392,
      "name": "task_update_spec_tif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void task_update_spec_tif(struct task_struct * tsk)
```

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138032,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:970",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138032,
      "name": "task_update_spec_tif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void task_update_spec_tif(struct task_struct * tsk)
```

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140144,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1100",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140144,
      "name": "task_update_spec_tif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579156742,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1207",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
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
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153982,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1201",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579161326,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1201",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579191838,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1323",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579238623,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1825",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579297747,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1874",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579303859,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1985",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579334611,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2126",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void task_update_spec_tif(struct task_struct * tsk)
```

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140512,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1100",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140512,
      "name": "task_update_spec_tif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void task_update_spec_tif(struct task_struct * tsk)
```

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579071664,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1100",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071664,
      "name": "task_update_spec_tif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void task_update_spec_tif(struct task_struct * tsk)
```

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140064,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1100",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140064,
      "name": "task_update_spec_tif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void task_update_spec_tif(struct task_struct * tsk)
```

```json
{
  "name": "task_update_spec_tif",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579145200,
      "name": "task_update_spec_tif",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1100",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145200,
      "name": "task_update_spec_tif",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void task_update_spec_tif(struct task_struct * tsk)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void task_update_spec_tif(struct task_struct * tsk)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void task_update_spec_tif(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void task_update_spec_tif(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void task_update_spec_tif(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void task_update_spec_tif(struct task_struct * tsk)
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
