# Function: <code>get_compat_ipc_perm</code>

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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673152,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:C_SYSC_msgctl",
        "ipc/sem.c:C_SYSC_semctl",
        "ipc/shm.c:C_SYSC_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673152,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582866448,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866448,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974576,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974576,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583155616,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155616,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583261680,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261680,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583588752,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588752,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583709072,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583709072,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733632,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733632,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094992,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094992,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584690000,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690000,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585380880,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585380880,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585611856,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611856,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585858576,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858576,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494991632,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494991632,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288870896,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288870896,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583230416,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230416,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583167568,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167568,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214448,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214448,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
```

```json
{
  "name": "get_compat_ipc_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583308336,
      "name": "get_compat_ipc_perm",
      "external": true,
      "loc": "ipc/compat.c:50",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgctl",
        "ipc/sem.c:compat_ksys_semctl",
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308336,
      "name": "get_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
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
int get_compat_ipc_perm(struct ipc64_perm * to, struct compat_ipc_perm * from)
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
