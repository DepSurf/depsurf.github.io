# Function: <code>do_mq_timedsend</code>

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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582563456,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_timedsend",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563456,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715952,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_timedsend",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715952,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582916112,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:909",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_timedsend",
        "ipc/mqueue.c:__ia32_compat_sys_mq_timedsend",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916112,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583025248,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:909",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_timedsend",
        "ipc/mqueue.c:__ia32_compat_sys_mq_timedsend",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583025248,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205376,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:964",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205376,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311152,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311152,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583641072,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:1044",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641072,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583762160,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:1044",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583762160,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786304,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:1047",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786304,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1013
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584149120,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:1049",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584149120,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1013
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584749872,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:1061",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584749872,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585444784,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:1060",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585444784,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585675968,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:1060",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675968,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1114
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585922784,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:1061",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585922784,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495052424,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__arm64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__arm64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495052424,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228448628,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__se_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228448628,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288942544,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__se_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288942544,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
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
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274324720,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_timedsend"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279888,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279888,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217024,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217024,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583263920,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583263920,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
```

```json
{
  "name": "do_mq_timedsend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355440,
      "name": "do_mq_timedsend",
      "external": false,
      "loc": "ipc/mqueue.c:963",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__x64_sys_mq_timedsend_time32",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355440,
      "name": "do_mq_timedsend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec * ts)
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
int do_mq_timedsend(mqd_t mqdes, const char * u_msg_ptr, size_t msg_len, unsigned int msg_prio, struct timespec64 * ts)
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
