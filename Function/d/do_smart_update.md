# Function: <code>do_smart_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct list_head * pt)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152784,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:973",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:exit_sem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152784,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct list_head * pt)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582369024,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:969",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582369024,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582460832,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:965",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582460832,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582539808,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:976",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539808,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582689584,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:979",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689584,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582883232,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1015",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883232,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582991840,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1014",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582991840,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583172688,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583172688,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583278656,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278656,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583613485,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1026",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583607424,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583733883,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1025",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727664,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583757879,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1027",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752064,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119545,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1030",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113792,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584719452,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1029",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584711584,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585412329,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1029",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585404368,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585643055,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1029",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635168,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585889762,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1029",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881856,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495013264,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495013264,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228421784,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228421784,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288896592,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288896592,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274299290,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:semctl_main"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274299290,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583247392,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583247392,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184544,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184544,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231424,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231424,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void do_smart_update(struct sem_array * sma, struct sembuf * sops, int nsops, int otime, struct wake_q_head * wake_q)
```

```json
{
  "name": "do_smart_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583326384,
      "name": "do_smart_update",
      "external": false,
      "loc": "ipc/sem.c:1010",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583326384,
      "name": "do_smart_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wake_q_head * wake_q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head * pt</code>
</li>
</ul>
</details>
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
