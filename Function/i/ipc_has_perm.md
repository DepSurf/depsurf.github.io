# Function: <code>ipc_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582278288,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5196",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat",
        "security/selinux/hooks.c:selinux_ipc_permission"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278288,
      "name": "ipc_has_perm.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582497248,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5340",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497248,
      "name": "ipc_has_perm.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582588496,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5421",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588496,
      "name": "ipc_has_perm.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582661920,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5367",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582661920,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817536,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5382",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817536,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583019072,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5953",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019072,
      "name": "ipc_has_perm.isra.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583125216,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5645",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125216,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311904,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5844",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311904,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583417072,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417072,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583778956,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5900",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semctl",
        "security/selinux/hooks.c:selinux_shm_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583758240,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583899667,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5916",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semctl",
        "security/selinux/hooks.c:selinux_shm_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879744,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583925939,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:6080",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semctl",
        "security/selinux/hooks.c:selinux_shm_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905856,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584290019,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:6065",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semctl",
        "security/selinux/hooks.c:selinux_shm_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584269568,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584909171,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5964",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semctl",
        "security/selinux/hooks.c:selinux_shm_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884304,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585618115,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5979",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semctl",
        "security/selinux/hooks.c:selinux_shm_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585590864,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585847902,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5932",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semctl",
        "security/selinux/hooks.c:selinux_shm_shmctl",
        "security/selinux/hooks.c:selinux_shm_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821808,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586097902,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:6017",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semctl",
        "security/selinux/hooks.c:selinux_shm_shmctl",
        "security/selinux/hooks.c:selinux_shm_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070208,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495173312,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495173312,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228560304,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228560304,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289111296,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289111296,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274415592,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274415592,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385808,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385808,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322896,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322896,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369584,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369584,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```

```json
{
  "name": "ipc_has_perm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583465168,
      "name": "ipc_has_perm",
      "external": false,
      "loc": "security/selinux/hooks.c:5902",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_ipc_permission",
        "security/selinux/hooks.c:selinux_sem_semop",
        "security/selinux/hooks.c:selinux_shm_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583465168,
      "name": "ipc_has_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int ipc_has_perm(struct kern_ipc_perm * ipc_perms, u32 perms)
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
