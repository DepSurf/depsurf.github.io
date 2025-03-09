# Function: <code>security_shm_shmctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_shm_shmctl(struct shmid_kernel * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248320,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1089",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248320,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_shm_shmctl(struct shmid_kernel * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466976,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1113",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466976,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_shm_shmctl(struct shmid_kernel * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559440,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1134",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559440,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_shm_shmctl(struct shmid_kernel * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582647200,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1874",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582647200,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_shm_shmctl(struct shmid_kernel * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802144,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1845",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802144,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582997904,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1238",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582997904,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110368,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1873",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110368,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296848,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1892",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296848,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583401760,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583401760,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741488,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:2133",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741488,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861808,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:2150",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861808,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583887984,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:2213",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887984,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584251696,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:2221",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584251696,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584862096,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:2232",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_shm_info",
        "ipc/shm.c:shmctl_ipc_info",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862096,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585567424,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:2308",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_shm_info",
        "ipc/shm.c:shmctl_ipc_info",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585567424,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585798336,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:3874",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_shm_info",
        "ipc/shm.c:shmctl_ipc_info",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798336,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586046272,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:3903",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_shm_info",
        "ipc/shm.c:shmctl_ipc_info",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046272,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495154688,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495154688,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228542196,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228542196,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289082944,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289082944,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274401088,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274401088,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583370496,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370496,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307600,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307600,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354272,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354272,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_shm_shmctl(struct kern_ipc_perm * shp, int cmd)
```

```json
{
  "name": "security_shm_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583449456,
      "name": "security_shm_shmctl",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449456,
      "name": "security_shm_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct shmid_kernel * shp</code> ➡️ <code>struct kern_ipc_perm * shp</code>
</li>
</ul>
</details>
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
