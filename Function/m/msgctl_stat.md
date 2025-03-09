# Function: <code>msgctl_stat</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582679600,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:476",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:C_SYSC_msgctl",
        "ipc/msg.c:SYSC_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582679600,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875088,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:490",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/msg.c:ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875088,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983136,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/msg.c:ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983136,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583165632,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165632,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583271696,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271696,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583598048,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:510",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598048,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718416,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:510",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718416,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583742944,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:512",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742944,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:512",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104608,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071592290706,
      "name": "msgctl_stat.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:512",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700800,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071594072808,
      "name": "msgctl_stat.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:518",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585391072,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071596092662,
      "name": "msgctl_stat.cold",
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:518",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585621712,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071596616013,
      "name": "msgctl_stat.cold",
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:518",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868432,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071597521917,
      "name": "msgctl_stat.cold",
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495003240,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495003240,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228417628,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/msg.c:ksys_msgctl"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288885424,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/msg.c:ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288885424,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274294322,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240432,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240432,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583177584,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177584,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224464,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224464,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```

```json
{
  "name": "msgctl_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583315424,
      "name": "msgctl_stat",
      "external": false,
      "loc": "ipc/msg.c:491",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315424,
      "name": "msgctl_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int msgctl_stat(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * p)
```
</details>
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
