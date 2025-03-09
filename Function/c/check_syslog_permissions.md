# Function: <code>check_syslog_permissions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724496,
      "name": "check_syslog_permissions",
      "external": true,
      "loc": "kernel/printk/printk.c:495",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:do_syslog",
        "fs/pstore/inode.c:pstore_unlink",
        "fs/pstore/inode.c:pstore_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724496,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579745552,
      "name": "check_syslog_permissions",
      "external": true,
      "loc": "kernel/printk/printk.c:605",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:do_syslog",
        "fs/pstore/inode.c:pstore_unlink",
        "fs/pstore/inode.c:pstore_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745552,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774256,
      "name": "check_syslog_permissions",
      "external": true,
      "loc": "kernel/printk/printk.c:603",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:do_syslog",
        "fs/pstore/inode.c:pstore_unlink",
        "fs/pstore/inode.c:pstore_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774256,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770368,
      "name": "check_syslog_permissions",
      "external": true,
      "loc": "kernel/printk/printk.c:652",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pstore/inode.c:pstore_unlink",
        "fs/pstore/inode.c:pstore_file_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770368,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803392,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:652",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803392,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:656",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836896,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071579848242,
      "name": "check_syslog_permissions.cold.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:652",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883824,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071579895282,
      "name": "check_syslog_permissions.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:669",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917424,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071579930066,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967472,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071579980210,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:691",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014496,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071580027788,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:508",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992592,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071591301530,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:521",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994192,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071591244315,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:516",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127376,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071592132851,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:521",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268976,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071593903544,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:602",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580476288,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071595985070,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:589",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548320,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071596503404,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:589",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609856,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071597401013,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491148120,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491148120,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225177952,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225177952,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284045856,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284045856,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271705816,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271705816,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936208,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071579948946,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874480,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071579886834,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927744,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071579940482,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int check_syslog_permissions(int type, int source)
```

```json
{
  "name": "check_syslog_permissions",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_syslog_permissions",
      "external": false,
      "loc": "kernel/printk/printk.c:679",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973728,
      "name": "check_syslog_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071579986754,
      "name": "check_syslog_permissions.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
