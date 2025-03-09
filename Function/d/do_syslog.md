# Function: <code>do_syslog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735200,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1297",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:SyS_syslog",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735200,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1324
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
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756096,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1428",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:SyS_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756096,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1355
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
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782160,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1380",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:SyS_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782160,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579778768,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1430",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:SyS_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778768,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579812208,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1429",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:SyS_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812208,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1293
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
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579843920,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1433",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843920,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579889344,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1449",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889344,
      "name": "do_syslog.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2194
    },
    {
      "addr": 18446744071579892160,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579923840,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1493",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923840,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2331
    },
    {
      "addr": 18446744071579926784,
      "name": "do_syslog",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579973952,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973952,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2365
    },
    {
      "addr": 18446744071579976928,
      "name": "do_syslog",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580023212,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1531",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog"
      ],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022080,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
    },
    {
      "addr": 18446744071580024720,
      "name": "do_syslog",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002044,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1561",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog"
      ],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000848,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
    },
    {
      "addr": 18446744071580003488,
      "name": "do_syslog",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580003436,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1633",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog"
      ],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002192,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
    },
    {
      "addr": 18446744071580004928,
      "name": "do_syslog",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580131948,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1632",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog"
      ],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130944,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
    },
    {
      "addr": 18446744071592133079,
      "name": "do_syslog.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580136528,
      "name": "do_syslog",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1659",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593904433,
      "name": "do_syslog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071580279008,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1740",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595985593,
      "name": "do_syslog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071580487632,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1709",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596503903,
      "name": "do_syslog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580559584,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1705",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597401328,
      "name": "do_syslog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071580616608,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491159544,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__arm64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491159544,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225186732,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__se_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225186732,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1572
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284056144,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__se_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284056144,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3048
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
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271713372,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__se_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271713372,
      "name": "do_syslog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2262
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579942688,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942688,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2365
    },
    {
      "addr": 18446744071579945664,
      "name": "do_syslog",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880752,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880752,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2299
    },
    {
      "addr": 18446744071579883664,
      "name": "do_syslog",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579934224,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934224,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2365
    },
    {
      "addr": 18446744071579937200,
      "name": "do_syslog",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_syslog(int type, char * buf, int len, int source)
```

```json
{
  "name": "do_syslog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579979680,
      "name": "do_syslog",
      "external": true,
      "loc": "kernel/printk/printk.c:1503",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:__ia32_sys_syslog",
        "kernel/printk/printk.c:__x64_sys_syslog",
        "fs/proc/kmsg.c:kmsg_poll",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_read",
        "fs/proc/kmsg.c:kmsg_release",
        "fs/proc/kmsg.c:kmsg_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979680,
      "name": "do_syslog.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2307
    },
    {
      "addr": 18446744071579983296,
      "name": "do_syslog",
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
