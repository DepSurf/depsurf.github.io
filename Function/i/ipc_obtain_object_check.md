# Function: <code>ipc_obtain_object_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142352,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:617",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:exit_sem",
        "ipc/shm.c:SyS_shmctl",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142352,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358400,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:612",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358400,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449760,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:612",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449760,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528640,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:556",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:SyS_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528640,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582677040,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:622",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582677040,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870480,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:626",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_pre_down_nolock",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870480,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582978528,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:587",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978528,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583159424,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159424,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265488,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265488,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583594085,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcctl_obtain_check"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593488,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583714441,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcctl_obtain_check"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713840,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583738953,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcctl_obtain_check"
      ],
      "caller_func": [
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738352,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:650",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592290638,
      "name": "ipc_obtain_object_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584100048,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:650",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594072740,
      "name": "ipc_obtain_object_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584695536,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:650",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596092594,
      "name": "ipc_obtain_object_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585386816,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:650",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596615945,
      "name": "ipc_obtain_object_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585617488,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:650",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597521849,
      "name": "ipc_obtain_object_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585864208,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494996104,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494996104,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228409608,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:ksys_msgctl",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228409608,
      "name": "ipc_obtain_object_check",
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288876528,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288876528,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274289390,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274289390,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234224,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234224,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583171376,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583171376,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218256,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218256,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct kern_ipc_perm * ipc_obtain_object_check(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312480,
      "name": "ipc_obtain_object_check",
      "external": true,
      "loc": "ipc/util.c:616",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:find_alloc_undo",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_do_lock",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312480,
      "name": "ipc_obtain_object_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
