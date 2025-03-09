# Function: <code>shmctl_down</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582165088,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:811",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582165088,
      "name": "shmctl_down.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582381328,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:813",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381328,
      "name": "shmctl_down.constprop.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582473488,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:817",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473488,
      "name": "shmctl_down.constprop.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582554256,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:815",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554256,
      "name": "shmctl_down.constprop.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705840,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:831",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:C_SYSC_shmctl",
        "ipc/shm.c:SYSC_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705840,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582900864,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:871",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl",
        "ipc/shm.c:ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582900864,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009072,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl",
        "ipc/shm.c:ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009072,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583190672,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190672,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296480,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296480,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583628480,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628480,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583749072,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:890",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749072,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583773264,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:890",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773264,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584134240,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:986",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134240,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584734192,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:980",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734192,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585427920,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:996",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427920,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585658640,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:996",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585658640,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585905408,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:992",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905408,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495036776,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495036776,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228438892,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/shm.c:ksys_shmctl"
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288919856,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl",
        "ipc/shm.c:ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288919856,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274314510,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265216,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265216,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202352,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202352,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249248,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249248,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
```

```json
{
  "name": "shmctl_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343840,
      "name": "shmctl_down",
      "external": false,
      "loc": "ipc/shm.c:891",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343840,
      "name": "shmctl_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
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
int shmctl_down(struct ipc_namespace * ns, int shmid, int cmd, struct shmid64_ds * shmid64)
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
