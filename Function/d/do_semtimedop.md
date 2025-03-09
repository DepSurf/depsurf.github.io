# Function: <code>do_semtimedop</code>

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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582692240,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1861",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semop",
        "ipc/sem.c:compat_SyS_semtimedop",
        "ipc/sem.c:compat_SyS_semtimedop",
        "ipc/sem.c:SyS_semtimedop",
        "ipc/sem.c:SyS_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692240,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4284
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582890480,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1936",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890480,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3961
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998624,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1943",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998624,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3886
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583179808,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1965",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179808,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3031
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285728,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285728,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2908
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583615248,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1982",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615248,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3114
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583735664,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1981",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735664,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3299
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583762528,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1983",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583762528,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3116
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127456,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:2226",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127456,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584724624,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:2223",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724624,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585417712,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:2224",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585417712,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585648336,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:2224",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585648336,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585895072,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:2222",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__ia32_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:__x64_sys_semtimedop_time32",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__ia32_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:__x64_sys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585895072,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495022136,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__arm64_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495022136,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3012
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228429764,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228429764,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2732
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288906848,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288906848,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4636
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274304646,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__se_sys_semop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274304646,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2572
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583254464,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254464,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2908
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191616,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191616,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2908
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238496,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238496,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2908
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec64 * timeout)
```

```json
{
  "name": "do_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583330224,
      "name": "do_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1966",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:__ia32_sys_semop",
        "ipc/sem.c:__x64_sys_semop",
        "ipc/sem.c:compat_ksys_semtimedop",
        "ipc/sem.c:ksys_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330224,
      "name": "do_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3047
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
long int do_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec * timeout</code> ➡️ <code>const struct timespec64 * timeout</code>
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
