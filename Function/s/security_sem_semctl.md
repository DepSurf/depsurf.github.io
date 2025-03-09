# Function: <code>security_sem_semctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_sem_semctl(struct sem_array * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248720,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1114",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:SyS_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248720,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct sem_array * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467376,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1138",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467376,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct sem_array * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559840,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1159",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559840,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct sem_array * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582647648,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582647648,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct sem_array * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802688,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1881",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:C_SYSC_semctl",
        "ipc/sem.c:SYSC_semctl",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802688,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998272,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1263",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998272,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110832,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1907",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110832,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297328,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1926",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297328,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583402224,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402224,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741984,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:2167",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741984,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583862304,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:2184",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583862304,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583888480,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:2247",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888480,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252192,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:2255",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252192,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584862688,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:2266",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862688,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585568096,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:2342",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568096,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585799008,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:3957",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585799008,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586046944,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:3986",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046944,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495155224,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495155224,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228542716,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228542716,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289083936,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289083936,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274401498,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274401498,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583370960,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370960,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583308064,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308064,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354736,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354736,
      "name": "security_sem_semctl",
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
int security_sem_semctl(struct kern_ipc_perm * sma, int cmd)
```

```json
{
  "name": "security_sem_semctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583449920,
      "name": "security_sem_semctl",
      "external": true,
      "loc": "security/security.c:1965",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:semctl_down",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449920,
      "name": "security_sem_semctl",
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
<code>struct sem_array * sma</code> ➡️ <code>struct kern_ipc_perm * sma</code>
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
