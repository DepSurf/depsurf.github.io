# Function: <code>retire_sysctl_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492160,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1606",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492160,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676896,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1612",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676896,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765040,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1618",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765040,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819168,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1682",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819168,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581968736,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1683",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968736,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582153488,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1685",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582153488,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248096,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1685",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248096,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413309,
      "name": "retire_sysctl_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582412752,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511712,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511712,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582814928,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1695",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814928,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888640,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1695",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888640,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582917104,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1699",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917104,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251712,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1699",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251712,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583751408,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1768",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "ipc/ipc_sysctl.c:retire_ipc_sysctls",
        "ipc/ipc_sysctl.c:setup_ipc_sysctls",
        "ipc/mq_sysctl.c:retire_mq_sysctls",
        "ipc/mq_sysctl.c:setup_mq_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751408,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584367168,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1767",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "ipc/ipc_sysctl.c:retire_ipc_sysctls",
        "ipc/ipc_sysctl.c:setup_ipc_sysctls",
        "ipc/mq_sysctl.c:retire_mq_sysctls",
        "ipc/mq_sysctl.c:setup_mq_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367168,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584595520,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1541",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "ipc/ipc_sysctl.c:retire_ipc_sysctls",
        "ipc/ipc_sysctl.c:setup_ipc_sysctls",
        "ipc/mq_sysctl.c:retire_mq_sysctls",
        "ipc/mq_sysctl.c:setup_mq_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595520,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584827104,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1537",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "ipc/ipc_sysctl.c:retire_ipc_sysctls",
        "ipc/ipc_sysctl.c:setup_ipc_sysctls",
        "ipc/mq_sysctl.c:retire_mq_sysctls",
        "ipc/mq_sysctl.c:setup_mq_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827104,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494139416,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494139416,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227587168,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227587168,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287816448,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287816448,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273619082,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273619082,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480448,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480448,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417680,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417680,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470928,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470928,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void retire_sysctl_set(struct ctl_table_set * set)
```

```json
{
  "name": "retire_sysctl_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551264,
      "name": "retire_sysctl_set",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1712",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:retire_userns_sysctls",
        "kernel/ucount.c:setup_userns_sysctls",
        "net/sysctl_net.c:sysctl_net_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551264,
      "name": "retire_sysctl_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
