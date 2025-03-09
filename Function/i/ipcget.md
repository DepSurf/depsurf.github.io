# Function: <code>ipcget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142496,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:640",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgget",
        "ipc/sem.c:SyS_semget",
        "ipc/shm.c:SyS_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142496,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358544,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:635",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgget",
        "ipc/sem.c:SyS_semget",
        "ipc/shm.c:SyS_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358544,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582449904,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:635",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgget",
        "ipc/sem.c:SyS_semget",
        "ipc/shm.c:SyS_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449904,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528736,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:579",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgget",
        "ipc/sem.c:SyS_semget",
        "ipc/shm.c:SyS_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528736,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582677152,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:645",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:SyS_msgget",
        "ipc/sem.c:SyS_semget",
        "ipc/shm.c:SyS_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582677152,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870592,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:649",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870592,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 617
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582978624,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:610",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978624,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 637
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583159520,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159520,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265584,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265584,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583593600,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:__ia32_sys_semget",
        "ipc/sem.c:__x64_sys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593600,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583713952,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:__ia32_sys_semget",
        "ipc/sem.c:__x64_sys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713952,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583738464,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:__ia32_sys_semget",
        "ipc/sem.c:__x64_sys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738464,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584100176,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:673",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:__ia32_sys_semget",
        "ipc/sem.c:__x64_sys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584100176,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584695696,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:673",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:__ia32_sys_semget",
        "ipc/sem.c:__x64_sys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695696,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585386992,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:673",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:__ia32_sys_semget",
        "ipc/sem.c:__x64_sys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585386992,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585617664,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:673",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:__ia32_sys_semget",
        "ipc/sem.c:__x64_sys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585617664,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585864384,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:673",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:__ia32_sys_semget",
        "ipc/sem.c:__x64_sys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585864384,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494996248,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__arm64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__arm64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494996248,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228409704,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:ksys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:ksys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228409704,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288876688,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__se_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288876688,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 936
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274289494,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__se_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274289494,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234320,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234320,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583171472,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583171472,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218352,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218352,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
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
int ipcget(struct ipc_namespace * ns, struct ipc_ids * ids, const struct ipc_ops * ops, struct ipc_params * params)
```

```json
{
  "name": "ipcget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312576,
      "name": "ipcget",
      "external": true,
      "loc": "ipc/util.c:639",
      "file": "ipc/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_sys_msgget",
        "ipc/msg.c:__x64_sys_msgget",
        "ipc/sem.c:ksys_semget",
        "ipc/shm.c:__ia32_sys_shmget",
        "ipc/shm.c:__x64_sys_shmget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312576,
      "name": "ipcget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
