# Function: <code>msgctl_down</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582145488,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:339",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145488,
      "name": "msgctl_down.constprop.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582361584,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:339",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361584,
      "name": "msgctl_down.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582453200,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:363",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453200,
      "name": "msgctl_down.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582531936,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:363",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531936,
      "name": "msgctl_down.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * msqid64)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582680416,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:364",
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
      "addr": 18446744071582680416,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * msqid64)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582876912,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:378",
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
      "addr": 18446744071582876912,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * msqid64)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986592,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
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
      "addr": 18446744071582986592,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * msqid64)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166064,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
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
      "addr": 18446744071583166064,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272128,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
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
      "addr": 18446744071583272128,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583600048,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:398",
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
      "addr": 18446744071583600048,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720416,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:398",
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
      "addr": 18446744071583720416,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744880,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:400",
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
      "addr": 18446744071583744880,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106576,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:400",
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
      "addr": 18446744071584106576,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700384,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:400",
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
      "addr": 18446744071584700384,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392560,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:401",
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
      "addr": 18446744071585392560,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623200,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:401",
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
      "addr": 18446744071585623200,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869920,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:401",
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
      "addr": 18446744071585869920,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495005912,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/msg.c:compat_ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495005912,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228413720,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:ksys_msgctl",
        "ipc/msg.c:ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228413720,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288886048,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/msg.c:ksys_msgctl",
        "ipc/msg.c:ksys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288886048,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274293772,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274293772,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240864,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
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
      "addr": 18446744071583240864,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583178016,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
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
      "addr": 18446744071583178016,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224896,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
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
      "addr": 18446744071583224896,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct ipc64_perm * perm, int msg_qbytes)
```

```json
{
  "name": "msgctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583317616,
      "name": "msgctl_down",
      "external": false,
      "loc": "ipc/msg.c:379",
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
      "addr": 18446744071583317616,
      "name": "msgctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int msgctl_down(struct ipc_namespace * ns, int msqid, int cmd, struct msqid64_ds * msqid64)
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ipc64_perm * perm</code>
</li>
<li>
<b>Param added. </b>
<code>int msg_qbytes</code>
</li>
<li>
<b>Param removed. </b>
<code>struct msqid64_ds * msqid64</code>
</li>
</ul>
</details>
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
