# Function: <code>do_mq_open</code>

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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567088,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:771",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567088,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719584,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:771",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_open",
        "ipc/mqueue.c:SyS_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719584,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582910048,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:744",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582910048,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583018576,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:744",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018576,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583199824,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:799",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583199824,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305600,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305600,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583636816,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:879",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636816,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757232,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:879",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757232,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583781360,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:879",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781360,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143536,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:881",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x64_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143536,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744144,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:893",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744144,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585438768,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:893",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438768,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669520,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:893",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669520,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585916304,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:894",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585916304,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495043640,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__arm64_compat_sys_mq_open",
        "ipc/mqueue.c:__arm64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495043640,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228452740,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288937760,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__se_compat_sys_mq_open",
        "ipc/mqueue.c:__se_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288937760,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
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
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274323726,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_open"
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583274336,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583274336,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211472,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211472,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258368,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258368,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
```

```json
{
  "name": "do_mq_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356736,
      "name": "do_mq_open",
      "external": false,
      "loc": "ipc/mqueue.c:798",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__x32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_compat_sys_mq_open",
        "ipc/mqueue.c:__ia32_sys_mq_open",
        "ipc/mqueue.c:__x64_sys_mq_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356736,
      "name": "do_mq_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
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
int do_mq_open(const char * u_name, int oflag, umode_t mode, struct mq_attr * attr)
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
