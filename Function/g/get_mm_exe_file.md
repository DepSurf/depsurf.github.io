# Function: <code>get_mm_exe_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359728,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:758",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "fs/coredump.c:do_coredump",
        "fs/proc/base.c:proc_exe_link",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359728,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579366800,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:793",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "fs/coredump.c:do_coredump",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366800,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384896,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:947",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "fs/coredump.c:do_coredump",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384896,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372304,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:994",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "fs/coredump.c:do_coredump",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372304,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399088,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1006",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "fs/coredump.c:do_coredump",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399088,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579416599,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1075",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_mm",
        "kernel/fork.c:get_task_exe_file"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "fs/coredump.c:do_coredump",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413856,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443952,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1131",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "fs/coredump.c:do_coredump",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443952,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461184,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1148",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461184,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487232,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487232,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514944,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1177",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_multicast",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514944,
      "name": "get_mm_exe_file",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496944,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1174",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_multicast",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496944,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579500736,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1180",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_multicast",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500736,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578912,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1261",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/audit.c:audit_log_multicast",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578912,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579669536,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1333",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579669536,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789632,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1357",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789632,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837152,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1498",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837152,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877861,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1494",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "kernel/audit_watch.c:audit_exe_compare",
        "fs/coredump.c:cn_print_exe_file",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877728,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490621000,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490621000,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224701964,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "fs/coredump.c:format_corename",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224701964,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283435024,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283435024,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271380202,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271377186,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460896,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460896,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389856,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389856,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460816,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460816,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct file * get_mm_exe_file(struct mm_struct * mm)
```

```json
{
  "name": "get_mm_exe_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493520,
      "name": "get_mm_exe_file",
      "external": true,
      "loc": "kernel/fork.c:1163",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:get_task_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/audit.c:audit_log_d_path_exe",
        "security/tomoyo/util.c:tomoyo_get_exe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493520,
      "name": "get_mm_exe_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
