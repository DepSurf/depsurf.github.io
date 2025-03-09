# Function: <code>security_sem_semop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_sem_semop(struct sem_array * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248800,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1119",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248800,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int security_sem_semop(struct sem_array * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467456,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1143",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467456,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int security_sem_semop(struct sem_array * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559920,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1164",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559920,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int security_sem_semop(struct sem_array * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582647728,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1912",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SYSC_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582647728,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int security_sem_semop(struct sem_array * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802784,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1886",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582802784,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998352,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1268",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998352,
      "name": "security_sem_semop",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110912,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1912",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110912,
      "name": "security_sem_semop",
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297408,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1931",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583297408,
      "name": "security_sem_semop",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583402304,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583402304,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583742064,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:2172",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742064,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583862384,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:2189",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583862384,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583888560,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:2252",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888560,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252272,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:2260",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252272,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584862784,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:2271",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584862784,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585568208,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:2347",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568208,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585799120,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:3974",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585799120,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586047056,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:4003",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047056,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495155320,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495155320,
      "name": "security_sem_semop",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228542808,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228542808,
      "name": "security_sem_semop",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289084128,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289084128,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274401566,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274401566,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583371040,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583371040,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583308144,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308144,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354816,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354816,
      "name": "security_sem_semop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int security_sem_semop(struct kern_ipc_perm * sma, struct sembuf * sops, unsigned int nsops, int alter)
```

```json
{
  "name": "security_sem_semop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450000,
      "name": "security_sem_semop",
      "external": true,
      "loc": "security/security.c:1970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450000,
      "name": "security_sem_semop",
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
