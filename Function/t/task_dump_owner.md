# Function: <code>task_dump_owner</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct * task, mode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781856,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1694",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781856,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581931520,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1695",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931520,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115520,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1661",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115520,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209968,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1675",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209968,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582373920,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582373920,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582472832,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472832,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582770480,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1799",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582770480,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843520,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1813",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843520,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871968,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1812",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871968,
      "name": "task_dump_owner",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205600,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1818",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205600,
      "name": "task_dump_owner",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583701984,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1817",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583701984,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312464,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1818",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312464,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584542320,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1818",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542320,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584774192,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1814",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_revalidate",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:proc_fdinfo_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584774192,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494091696,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494091696,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227543464,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227543464,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287757984,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287757984,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273579544,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273579544,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441568,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441568,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378736,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378736,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432048,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432048,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void task_dump_owner(struct task_struct * task, umode_t mode, kuid_t * ruid, kgid_t * rgid)
```

```json
{
  "name": "task_dump_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512080,
      "name": "task_dump_owner",
      "external": true,
      "loc": "fs/proc/base.c:1688",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:pid_update_inode",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_make_inode",
        "fs/proc/fd.c:tid_fd_update_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512080,
      "name": "task_dump_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void task_dump_owner(struct task_struct * task, mode_t mode, kuid_t * ruid, kgid_t * rgid)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>mode_t mode</code> ➡️ <code>umode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
