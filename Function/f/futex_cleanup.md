# Function: <code>futex_cleanup</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204448,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204448,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580280490,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3672",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
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
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580263706,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3596",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
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
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580268698,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3593",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
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
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580420330,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3824",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626560,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex/core.c:1007",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:futex_exit_release",
        "kernel/futex/core.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626560,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580892528,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex/core.c:1015",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:futex_exit_release",
        "kernel/futex/core.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892528,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976384,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex/core.c:1015",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:futex_exit_release",
        "kernel/futex/core.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976384,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070224,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex/core.c:1040",
      "file": "kernel/futex/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/core.c:futex_exit_release",
        "kernel/futex/core.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070224,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491434496,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491434496,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1588
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225431340,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225431340,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1192
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284387872,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284387872,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2844
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271897602,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271897602,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173248,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173248,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118000,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118000,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1113
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164720,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164720,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
void futex_cleanup(struct task_struct * tsk)
```

```json
{
  "name": "futex_cleanup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213984,
      "name": "futex_cleanup",
      "external": false,
      "loc": "kernel/futex.c:3759",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_exit_release",
        "kernel/futex.c:futex_exec_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213984,
      "name": "futex_cleanup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void futex_cleanup(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void futex_cleanup(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void futex_cleanup(struct task_struct * tsk)
```
</details>
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
