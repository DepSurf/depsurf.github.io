# Function: <code>copy_compat_msqid_to_user</code>

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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582680864,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:609",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:C_SYSC_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582680864,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582873200,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:647",
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
      "addr": 18446744071582873200,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981248,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:657",
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
      "addr": 18446744071582981248,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583162224,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:669",
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
      "addr": 18446744071583162224,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268288,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:670",
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
      "addr": 18446744071583268288,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583595920,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:689",
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
      "addr": 18446744071583595920,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583716272,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:689",
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
      "addr": 18446744071583716272,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740752,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:691",
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
      "addr": 18446744071583740752,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102416,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:691",
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
      "addr": 18446744071584102416,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698640,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:691",
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
      "addr": 18446744071584698640,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585390144,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:697",
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
      "addr": 18446744071585390144,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585620784,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:697",
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
      "addr": 18446744071585620784,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585867504,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:697",
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
      "addr": 18446744071585867504,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495006472,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:670",
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
      "addr": 18446603336495006472,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288880704,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:670",
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
      "addr": 13835058055288880704,
      "name": "copy_compat_msqid_to_user",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237024,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:670",
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
      "addr": 18446744071583237024,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583174176,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:670",
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
      "addr": 18446744071583174176,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583221056,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:670",
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
      "addr": 18446744071583221056,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_msqid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583316112,
      "name": "copy_compat_msqid_to_user",
      "external": false,
      "loc": "ipc/msg.c:670",
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
      "addr": 18446744071583316112,
      "name": "copy_compat_msqid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
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
int copy_compat_msqid_to_user(void * buf, struct msqid64_ds * in, int version)
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
