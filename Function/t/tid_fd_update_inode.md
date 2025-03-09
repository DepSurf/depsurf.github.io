# Function: <code>tid_fd_update_inode</code>

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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133664,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133664,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228208,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228208,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392464,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392464,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582491376,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491376,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582791321,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790736,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582865065,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:97",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864592,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582893321,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:97",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582892832,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583226697,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:111",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226240,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583724805,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:121",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724304,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584336853,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:122",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336304,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584566933,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:123",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566384,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584798821,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:125",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ],
      "caller_func": [
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584798272,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494114208,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494114208,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227563784,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227563784,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287784128,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287784128,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273597670,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273597670,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460112,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460112,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582397344,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397344,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450592,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450592,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
```

```json
{
  "name": "tid_fd_update_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530912,
      "name": "tid_fd_update_inode",
      "external": false,
      "loc": "fs/proc/fd.c:101",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530912,
      "name": "tid_fd_update_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void tid_fd_update_inode(struct task_struct * task, struct inode * inode, fmode_t f_mode)
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
