# Function: <code>ipcctl_obtain_check</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979408,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:659",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979408,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160336,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160336,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266400,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266400,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583594080,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583594080,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583714432,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714432,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583738944,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738944,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584100656,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:722",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100656,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584696192,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:722",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584696192,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585387520,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:722",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585387520,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618208,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:722",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618208,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585864928,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:722",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585864928,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494997120,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494997120,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228410620,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:ksys_semctl",
        "ipc/shm.c:ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228410620,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288877824,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288877824,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274290250,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:__se_sys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274290250,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583235136,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235136,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583172288,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583172288,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219168,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219168,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```

```json
{
  "name": "ipcctl_obtain_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583313408,
      "name": "ipcctl_obtain_check",
      "external": true,
      "loc": "ipc/util.c:688",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:msgctl_down",
        "ipc/sem.c:semctl_down",
        "ipc/shm.c:shmctl_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313408,
      "name": "ipcctl_obtain_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct kern_ipc_perm * ipcctl_obtain_check(struct ipc_namespace * ns, struct ipc_ids * ids, int id, int cmd, struct ipc64_perm * perm, int extra_perm)
```
</details>
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
