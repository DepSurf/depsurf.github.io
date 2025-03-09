# Function: <code>do_epoll_create</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906832,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:1938",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906832,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581987424,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:1964",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987424,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123008,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123008,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200240,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200240,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440520,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2040",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create"
      ],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438816,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582501096,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:1951",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create"
      ],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494704,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582522176,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:1957",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582522176,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582838160,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:1958",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582838160,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583398240,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:1987",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398240,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583984704,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:1989",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984704,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212816,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2038",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212816,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584427312,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2029",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427312,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493761776,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__arm64_sys_epoll_create",
        "fs/eventpoll.c:__arm64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493761776,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227285532,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_create",
        "fs/eventpoll.c:__se_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227285532,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287381104,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_create",
        "fs/eventpoll.c:__se_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287381104,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273366680,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__se_sys_epoll_create",
        "fs/eventpoll.c:__se_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273366680,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168976,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168976,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109920,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109920,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159456,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159456,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int do_epoll_create(int flags)
```

```json
{
  "name": "do_epoll_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235008,
      "name": "do_epoll_create",
      "external": false,
      "loc": "fs/eventpoll.c:2042",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:__ia32_sys_epoll_create",
        "fs/eventpoll.c:__x64_sys_epoll_create",
        "fs/eventpoll.c:__ia32_sys_epoll_create1",
        "fs/eventpoll.c:__x64_sys_epoll_create1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235008,
      "name": "do_epoll_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int do_epoll_create(int flags)
```
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
