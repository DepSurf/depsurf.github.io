# Function: <code>copy_compat_shmid_to_user</code>

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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582704976,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1174",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:C_SYSC_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704976,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582898432,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1246",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582898432,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006592,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1275",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006592,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583188080,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583188080,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583293888,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583293888,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624656,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624656,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583745184,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1287",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745184,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583769392,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1287",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769392,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131280,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1383",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131280,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584729344,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1377",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584729344,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585422752,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1393",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585422752,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585653424,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1393",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585653424,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585900192,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1389",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585900192,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495032832,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495032832,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288916800,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288916800,
      "name": "copy_compat_shmid_to_user",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262624,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262624,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583199776,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583199776,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583246656,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246656,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
```

```json
{
  "name": "copy_compat_shmid_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583341504,
      "name": "copy_compat_shmid_to_user",
      "external": false,
      "loc": "ipc/shm.c:1288",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_ksys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341504,
      "name": "copy_compat_shmid_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
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
int copy_compat_shmid_to_user(void * buf, struct shmid64_ds * in, int version)
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
