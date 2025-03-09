# Function: <code>pid_update_inode</code>

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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116880,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1789",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116880,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211328,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1803",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211328,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375328,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375328,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582474240,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582474240,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582773052,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1949",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate"
      ],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582773680,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582846284,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1963",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate"
      ],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846912,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582874700,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1962",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate"
      ],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875328,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583208332,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1968",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate"
      ],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208960,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583705106,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1995",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate"
      ],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583705632,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584315842,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1996",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate"
      ],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316400,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584545730,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1996",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate"
      ],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546288,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584777554,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1990",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate"
      ],
      "caller_func": [
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778112,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494093344,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494093344,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227544968,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227544968,
      "name": "pid_update_inode",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287760288,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287760288,
      "name": "pid_update_inode",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273580856,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273580856,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442976,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442976,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380144,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380144,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433456,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433456,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
```

```json
{
  "name": "pid_update_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513520,
      "name": "pid_update_inode",
      "external": true,
      "loc": "fs/proc/base.c:1816",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513520,
      "name": "pid_update_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void pid_update_inode(struct task_struct * task, struct inode * inode)
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
