# Function: <code>copy_compat_semid_to_user</code>

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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687872,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1649",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:C_SYSC_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687872,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880544,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1716",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880544,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582988640,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1723",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988640,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583169968,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1732",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169968,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275952,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1732",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275952,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583604160,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1748",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604160,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583724512,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1747",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724512,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748880,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1749",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748880,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110560,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1752",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110560,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584707200,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1750",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584707200,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585399616,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1750",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399616,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585630304,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1750",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630304,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585877072,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1750",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585877072,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495014256,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1732",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495014256,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288892304,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1732",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288892304,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583244688,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1732",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244688,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583181840,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1732",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181840,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583228720,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1732",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228720,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_semid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323408,
      "name": "copy_compat_semid_to_user",
      "external": false,
      "loc": "ipc/sem.c:1732",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:compat_ksys_semctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323408,
      "name": "copy_compat_semid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
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
int copy_compat_semid_to_user(void * buf, struct semid64_ds * in, int version)
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
