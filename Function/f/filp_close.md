# Function: <code>filp_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981184,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1078",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapon",
        "fs/file.c:do_dup2",
        "fs/file.c:__close_fd",
        "fs/file.c:do_close_on_exec",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981184,
      "name": "filp_close",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136304,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1089",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136304,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211392,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1106",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211392,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257376,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1132",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapoff",
        "mm/swapfile.c:SyS_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257376,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581396496,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1132",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapoff",
        "mm/swapfile.c:SYSC_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396496,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1174",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561105,
      "name": "filp_close.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581551280,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1141",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646273,
      "name": "filp_close.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581635936,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1161",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763025,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581752528,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835233,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581824736,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1273",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd",
        "fs/io_uring.c:io_issue_sqe",
        "fs/coredump.c:do_coredump",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057571,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582046352,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1271",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:blob_to_mnt",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:replace_fd",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_range",
        "fs/io_uring.c:io_close",
        "fs/coredump.c:do_coredump",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591339136,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582096528,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1293",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/file.c:replace_fd",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_range",
        "fs/io_uring.c:io_issue_sqe",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281850,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582120608,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1311",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/file.c:replace_fd",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_range",
        "fs/io_uring.c:io_close",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/proc_sysctl.c:process_sysctl_arg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592228786,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582437440,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1378",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/file.c:replace_fd",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_range",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "io_uring/io_uring.c:io_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008323,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582954400,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583512176,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1410",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/file.c:replace_fd",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_range",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "io_uring/openclose.c:io_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583512176,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727216,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1506",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/usermode_driver.c:umd_load_blob",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/file.c:replace_fd",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_range",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "io_uring/openclose.c:io_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727216,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926960,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1523",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "fs/file.c:replace_fd",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_range",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "fs/proc/proc_sysctl.c:process_sysctl_arg",
        "io_uring/openclose.c:io_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926960,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493288128,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__arm64_sys_acct",
        "kernel/acct.c:__arm64_sys_acct",
        "kernel/acct.c:__arm64_sys_acct",
        "kernel/acct.c:__arm64_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493288128,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226891292,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226891292,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286824368,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286824368,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273035332,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273035332,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803969,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581793472,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741633,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581731136,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795281,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581784784,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int filp_close(struct file * filp, fl_owner_t id)
```

```json
{
  "name": "filp_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filp_close",
      "external": true,
      "loc": "fs/open.c:1166",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "kernel/acct.c:acct_on",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "fs/file.c:do_dup2",
        "fs/file.c:do_close_on_exec",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:__close_fd",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864449,
      "name": "filp_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581853920,
      "name": "filp_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
