# Function: <code>ipcperms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141600,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:484",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgrcv",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:SyS_semctl",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141600,
      "name": "ipcperms",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357648,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:479",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357648,
      "name": "ipcperms",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449008,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:479",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449008,
      "name": "ipcperms",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527984,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:423",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527984,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582676368,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:486",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582676368,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582869808,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:490",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582869808,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582977984,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:490",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977984,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158880,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158880,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583264944,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583264944,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583592944,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583592944,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583713296,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713296,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583737808,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737808,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099472,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:553",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099472,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584694928,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:553",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694928,
      "name": "ipcperms",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585386144,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:553",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585386144,
      "name": "ipcperms",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616816,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:553",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616816,
      "name": "ipcperms",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585863536,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:553",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585863536,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494995520,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494995520,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228408928,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ksys_msgctl",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228408928,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288875760,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288875760,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274288858,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274288858,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233680,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233680,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170832,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170832,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217712,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217712,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int ipcperms(struct ipc_namespace * ns, struct kern_ipc_perm * ipcp, short int flag)
```

```json
{
  "name": "ipcperms",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311936,
      "name": "ipcperms",
      "external": true,
      "loc": "ipc/util.c:519",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcget",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311936,
      "name": "ipcperms",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
