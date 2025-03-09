# Function: <code>ksys_msgctl</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds * buf)
```

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879152,
      "name": "ksys_msgctl",
      "external": true,
      "loc": "ipc/msg.c:560",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879152,
      "name": "ksys_msgctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds * buf)
```

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987216,
      "name": "ksys_msgctl",
      "external": true,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987216,
      "name": "ksys_msgctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583167200,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167200,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583273216,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583273216,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583601088,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:589",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601088,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721440,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:589",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721440,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745872,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:591",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745872,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584107568,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:591",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107568,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584701872,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:591",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701872,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585393664,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:597",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585393664,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585624352,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:597",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585624352,
      "name": "ksys_msgctl.constprop.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585871072,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:597",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871072,
      "name": "ksys_msgctl.constprop.0",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495008832,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__arm64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495008832,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds * buf, int version)
```

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228417428,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:ksys_old_msgctl",
        "ipc/msg.c:__se_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228417428,
      "name": "ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds * buf, int version)
```

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288886720,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:ksys_old_msgctl",
        "ipc/msg.c:__se_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288886720,
      "name": "ksys_msgctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274294222,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274294222,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 818
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241952,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583241952,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583179104,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179104,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583225984,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583225984,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ksys_msgctl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583318704,
      "name": "ksys_msgctl",
      "external": false,
      "loc": "ipc/msg.c:570",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgctl",
        "ipc/msg.c:__x64_sys_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583318704,
      "name": "ksys_msgctl.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds * buf)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds * buf)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds * buf, int version)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long int ksys_msgctl(int msqid, int cmd, struct msqid_ds * buf, int version)
```
</details>
</li>
</ul>
