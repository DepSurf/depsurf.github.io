# Function: <code>__audit_ipc_obj</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062096,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2121",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcperms",
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062096,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095312,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2125",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/util.c:ipcperms",
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095312,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135632,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2133",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/util.c:ipcperms",
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135632,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141296,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2142",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/util.c:ipcperms",
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141296,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580193904,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2165",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/util.c:ipcperms",
        "ipc/shm.c:shmctl_do_lock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193904,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253664,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2172",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253664,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580306912,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2157",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306912,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580358896,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580358896,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407664,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407664,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580486192,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2325",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580486192,
      "name": "__audit_ipc_obj",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474448,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2342",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474448,
      "name": "__audit_ipc_obj",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478400,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2339",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478400,
      "name": "__audit_ipc_obj",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580645840,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2353",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645840,
      "name": "__audit_ipc_obj",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580854192,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2619",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580854192,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141568,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2597",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141568,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234608,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2596",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234608,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581340704,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2591",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340704,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491673144,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491673144,
      "name": "__audit_ipc_obj",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225627440,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:ksys_msgctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225627440,
      "name": "__audit_ipc_obj",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284682304,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284682304,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272063702,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/sem.c:__se_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272063702,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376464,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376464,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580323632,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323632,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367712,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367712,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void __audit_ipc_obj(struct kern_ipc_perm * ipcp)
```

```json
{
  "name": "__audit_ipc_obj",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580423200,
      "name": "__audit_ipc_obj",
      "external": true,
      "loc": "kernel/auditsc.c:2273",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipcperms",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423200,
      "name": "__audit_ipc_obj",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
