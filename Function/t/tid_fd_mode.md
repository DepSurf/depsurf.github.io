# Function: <code>tid_fd_mode</code>

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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133552,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133552,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228096,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228096,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392352,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392352,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582491264,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582491264,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582791120,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791120,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582865451,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:85",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
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
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582893941,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:85",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:tid_fd_revalidate"
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
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583227237,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:99",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:tid_fd_revalidate"
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
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583725510,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:109",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:tid_fd_revalidate"
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
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584337894,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:110",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:tid_fd_revalidate"
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
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584567990,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:111",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfdinfo",
        "fs/proc/fd.c:proc_lookupfd",
        "fs/proc/fd.c:tid_fd_revalidate"
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
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584799612,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:111",
      "file": "fs/proc/fd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494114040,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494114040,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227563668,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227563668,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287783888,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287783888,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273597530,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273597530,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460000,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460000,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582397232,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397232,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450480,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450480,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```

```json
{
  "name": "tid_fd_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530784,
      "name": "tid_fd_mode",
      "external": false,
      "loc": "fs/proc/fd.c:84",
      "file": "fs/proc/fd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/fd.c:proc_lookupfd_common",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530784,
      "name": "tid_fd_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
bool tid_fd_mode(struct task_struct * task, unsigned int fd, fmode_t * mode)
```
</details>
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
