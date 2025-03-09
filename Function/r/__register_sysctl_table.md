# Function: <code>__register_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581489568,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1213",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:register_sysctl",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581489568,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581674208,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1219",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674208,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1498
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581762352,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1225",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762352,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1498
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581816512,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1289",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816512,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1472
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966080,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1290",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966080,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1472
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1292",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153733,
      "name": "__register_sysctl_table.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071582150944,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1320
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1291",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248341,
      "name": "__register_sysctl_table.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071582245616,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1249
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413043,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071582410272,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1251
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512003,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071582509232,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1251
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582813296,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1299",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582813296,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582887008,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1299",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582887008,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1303",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289022,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582914688,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1257
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1303",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592248533,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583249296,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1257
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1329",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:__register_sysctl_init",
        "fs/proc/proc_sysctl.c:register_sysctl_mount_point",
        "ipc/ipc_sysctl.c:setup_ipc_sysctls",
        "ipc/mq_sysctl.c:setup_mq_sysctls",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594029271,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071583748784,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1236
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584364336,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1328",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:__register_sysctl_init",
        "fs/proc/proc_sysctl.c:register_sysctl_mount_point",
        "ipc/ipc_sysctl.c:setup_ipc_sysctls",
        "ipc/mq_sysctl.c:setup_mq_sysctls",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584364336,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1300
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584594832,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1353",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_init",
        "fs/proc/proc_sysctl.c:register_sysctl_mount_point",
        "ipc/ipc_sysctl.c:setup_ipc_sysctls",
        "ipc/mq_sysctl.c:setup_mq_sysctls",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594832,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table, size_t table_size)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584826432,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1351",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_init",
        "fs/proc/proc_sysctl.c:register_sysctl_mount_point",
        "ipc/ipc_sysctl.c:setup_ipc_sysctls",
        "ipc/mq_sysctl.c:setup_mq_sysctls",
        "net/sysctl_net.c:register_net_sysctl_sz"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826432,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494136080,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494136080,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2096
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227584248,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227584248,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1708
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287812720,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287812720,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2148
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273616442,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273616442,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1668
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480739,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071582477968,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1251
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417971,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071582415200,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1251
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471219,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071582468448,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1251
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
struct ctl_table_header * __register_sysctl_table(struct ctl_table_set * set, const char * path, struct ctl_table * table)
```

```json
{
  "name": "__register_sysctl_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_sysctl_table",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1316",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:setup_userns_sysctls",
        "fs/proc/proc_sysctl.c:__register_sysctl_paths",
        "fs/proc/proc_sysctl.c:register_leaf_sysctl_tables",
        "fs/proc/proc_sysctl.c:register_sysctl",
        "net/sysctl_net.c:register_net_sysctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551555,
      "name": "__register_sysctl_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071582548848,
      "name": "__register_sysctl_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1193
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t table_size</code>
</li>
</ul>
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
