# Function: <code>do_mq_notify</code>

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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582564624,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564624,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717120,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_notify",
        "ipc/mqueue.c:SyS_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717120,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1104
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582914112,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1162",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582914112,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1091
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583023632,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1162",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023632,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1091
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583207008,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1217",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207008,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312784,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312784,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583642768,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1301",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642768,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1229
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583763856,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1301",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763856,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1320
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788032,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1304",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788032,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1316
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584150848,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1306",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x64_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150848,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1316
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584753680,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1318",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584753680,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585448752,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1317",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448752,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1191
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679984,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1317",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679984,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585926832,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1316",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585926832,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495054768,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__arm64_compat_sys_mq_notify",
        "ipc/mqueue.c:__arm64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495054768,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228450980,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228450980,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1112
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288945088,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_compat_sys_mq_notify",
        "ipc/mqueue.c:__se_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288945088,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274326704,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_notify"
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281520,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281520,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218656,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218656,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265552,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265552,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```

```json
{
  "name": "do_mq_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361584,
      "name": "do_mq_notify",
      "external": false,
      "loc": "ipc/mqueue.c:1216",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_compat_sys_mq_notify",
        "ipc/mqueue.c:__ia32_sys_mq_notify",
        "ipc/mqueue.c:__x64_sys_mq_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361584,
      "name": "do_mq_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1129
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
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_mq_notify(mqd_t mqdes, const struct sigevent * notification)
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
