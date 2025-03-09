# Function: <code>proc_pid_make_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455936,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1643",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455936,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640224,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1659",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640224,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581728624,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1677",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581728624,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581782720,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581782720,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932384,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1747",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932384,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116256,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1719",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116256,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210704,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1733",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210704,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582374688,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582374688,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582473600,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473600,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582771600,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1870",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582771600,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844768,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1884",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844768,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582873184,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1883",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582873184,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583206816,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1889",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583206816,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583703200,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1888",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703200,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313760,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1889",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313760,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584543632,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1889",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584543632,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584775488,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1883",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584775488,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494092600,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494092600,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227544212,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227544212,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287759200,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287759200,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273580262,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273580262,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442336,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442336,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582379504,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379504,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432816,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432816,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * proc_pid_make_inode(struct super_block * sb, struct task_struct * task, umode_t mode)
```

```json
{
  "name": "proc_pid_make_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512880,
      "name": "proc_pid_make_inode",
      "external": true,
      "loc": "fs/proc/base.c:1746",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_task_instantiate",
        "fs/proc/base.c:proc_pid_instantiate",
        "fs/proc/base.c:proc_pident_instantiate",
        "fs/proc/base.c:proc_map_files_instantiate",
        "fs/proc/fd.c:proc_fdinfo_instantiate",
        "fs/proc/fd.c:proc_fd_instantiate",
        "fs/proc/namespaces.c:proc_ns_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512880,
      "name": "proc_pid_make_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>umode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
