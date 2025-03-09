# Function: <code>shmctl_do_lock</code>

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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582704432,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:969",
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
      "addr": 18446744071582704432,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902416,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1035",
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
      "addr": 18446744071582902416,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583010704,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446744071583010704,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583192336,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446744071583192336,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298144,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446744071583298144,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583628752,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446744071583628752,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583749344,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1063",
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
      "addr": 18446744071583749344,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583773536,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1063",
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
      "addr": 18446744071583773536,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1159",
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
      "addr": 18446744071584135632,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071592291460,
      "name": "shmctl_do_lock.cold",
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1153",
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
      "addr": 18446744071584731136,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071594073555,
      "name": "shmctl_do_lock.cold",
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1169",
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
      "addr": 18446744071585424624,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071596093259,
      "name": "shmctl_do_lock.cold",
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1169",
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
      "addr": 18446744071585655296,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071596616595,
      "name": "shmctl_do_lock.cold",
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1165",
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
      "addr": 18446744071585902064,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071597522475,
      "name": "shmctl_do_lock.cold",
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495036000,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446603336495036000,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228438168,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288922160,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 13835058055288922160,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274314302,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266880,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446744071583266880,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583204016,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446744071583204016,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583250912,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446744071583250912,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
```

```json
{
  "name": "shmctl_do_lock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583342896,
      "name": "shmctl_do_lock",
      "external": false,
      "loc": "ipc/shm.c:1064",
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
      "addr": 18446744071583342896,
      "name": "shmctl_do_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
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
int shmctl_do_lock(struct ipc_namespace * ns, int shmid, int cmd)
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
