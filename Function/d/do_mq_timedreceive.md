# Function: <code>do_mq_timedreceive</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582565728,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565728,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582718224,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718224,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1027",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917728,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1282
    },
    {
      "addr": 18446744071582921847,
      "name": "do_mq_timedreceive.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1027",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026864,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1291
    },
    {
      "addr": 18446744071583030431,
      "name": "do_mq_timedreceive.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1082",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208688,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
    },
    {
      "addr": 18446744071583212255,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314464,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
    },
    {
      "addr": 18446744071583318031,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1164",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645360,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1316
    },
    {
      "addr": 18446744071583649311,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1164",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766544,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1316
    },
    {
      "addr": 18446744071591361420,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1167",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790736,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1314
    },
    {
      "addr": 18446744071591304243,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153600,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1169",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153600,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584751792,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1181",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751792,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446784,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1180",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446784,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585678000,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1180",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678000,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1062
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585924832,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1180",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585924832,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495050424,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__arm64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__arm64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495050424,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228447176,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__se_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228447176,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1452
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288940112,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__se_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288940112,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274325500,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_timedreceive"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583283200,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
    },
    {
      "addr": 18446744071583286767,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220336,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
    },
    {
      "addr": 18446744071583223903,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583267232,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
    },
    {
      "addr": 18446744071583270799,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedreceive",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_timedreceive",
      "external": false,
      "loc": "ipc/mqueue.c:1081",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358752,
      "name": "do_mq_timedreceive",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071583365303,
      "name": "do_mq_timedreceive.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec * ts)
```
</details>
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
<code>struct timespec * ts</code> ➡️ <code>struct timespec64 * ts</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_mq_timedreceive(mqd_t mqdes, char * u_msg_ptr, size_t msg_len, unsigned int * u_msg_prio, struct timespec64 * ts)
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
