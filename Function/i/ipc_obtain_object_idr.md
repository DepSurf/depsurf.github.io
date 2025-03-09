# Function: <code>ipc_obtain_object_idr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582142096,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:558",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142096,
      "name": "ipc_obtain_object_idr",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582358405,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:553",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock"
      ],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358144,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582449765,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:553",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449504,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582528645,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:497",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528464,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582677045,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:560",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582676848,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582870485,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:564",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:shmctl_stat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870288,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582978533,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:564",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978464,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583159429,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159360,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583265493,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265424,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583594085,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcctl_obtain_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593424,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583714441,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcctl_obtain_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713776,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583738953,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcctl_obtain_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738288,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584100065,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:627",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592290607,
      "name": "ipc_obtain_object_idr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584099952,
      "name": "ipc_obtain_object_idr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584695553,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:627",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594072709,
      "name": "ipc_obtain_object_idr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071584695424,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585386833,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:627",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:__shm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596092563,
      "name": "ipc_obtain_object_idr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585386688,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585617505,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:627",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:__shm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596615914,
      "name": "ipc_obtain_object_idr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585617360,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585864225,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:627",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:__shm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597521818,
      "name": "ipc_obtain_object_idr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585864080,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494996140,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494996016,
      "name": "ipc_obtain_object_idr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228409628,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:ksys_msgctl",
        "ipc/sem.c:ksys_semctl",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:__shm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228409548,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288876564,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288876400,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274289410,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274289304,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583234229,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234160,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583171381,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583171312,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583218261,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218192,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct kern_ipc_perm * ipc_obtain_object_idr(struct ipc_ids * ids, int id)
```

```json
{
  "name": "ipc_obtain_object_idr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583312485,
      "name": "ipc_obtain_object_idr",
      "external": true,
      "loc": "ipc/util.c:593",
      "file": "ipc/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check"
      ],
      "caller_func": [
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_stat",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shm_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312416,
      "name": "ipc_obtain_object_idr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
