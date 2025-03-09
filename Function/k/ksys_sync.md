# Function: <code>ksys_sync</code>

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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804336,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "fs/sync.c:__x64_sys_sync",
        "drivers/tty/sysrq.c:sysrq_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804336,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891344,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_ioctl",
        "fs/sync.c:__x64_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891344,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582016464,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__x64_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582016464,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094416,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__x64_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094416,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582331552,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:110",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__do_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582331552,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382976,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:110",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__do_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382976,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582410256,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__do_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410256,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732640,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:110",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__do_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732640,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583277920,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:97",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__do_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583277920,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860608,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:97",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__do_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860608,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082368,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:97",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__do_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082368,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298432,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:97",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__do_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298432,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493630480,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__arm64_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493630480,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227170448,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227170448,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287221024,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287221024,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273270234,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273270234,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063152,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__x64_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063152,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000704,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__x64_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000704,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054432,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__x64_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054432,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
```

```json
{
  "name": "ksys_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126112,
      "name": "ksys_sync",
      "external": true,
      "loc": "fs/sync.c:109",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:ksys_sync_helper",
        "fs/sync.c:__x64_sys_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126112,
      "name": "ksys_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void ksys_sync()
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
