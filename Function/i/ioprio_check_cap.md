# Function: <code>ioprio_check_cap</code>

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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672144,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:64",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672144,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779424,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:64",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779424,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583969184,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969184,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072544,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072544,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584464224,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464224,
      "name": "ioprio_check_cap",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584579248,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584579248,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584611312,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584611312,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585025744,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__do_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585025744,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742656,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:33",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__do_sys_ioprio_set",
        "io_uring/io_uring.c:io_prep_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742656,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586524944,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:33",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__do_sys_ioprio_set",
        "io_uring/rw.c:io_prep_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586524944,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586771168,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:33",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__do_sys_ioprio_set",
        "io_uring/rw.c:io_prep_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771168,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043776,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:33",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__do_sys_ioprio_set",
        "io_uring/rw.c:io_prep_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043776,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495915208,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__arm64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495915208,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229256872,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229256872,
      "name": "ioprio_check_cap",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290125504,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290125504,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275027920,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "block/ioprio.c:__se_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275027920,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584041280,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041280,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583977040,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977040,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025040,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025040,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int ioprio_check_cap(int ioprio)
```

```json
{
  "name": "ioprio_check_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127600,
      "name": "ioprio_check_cap",
      "external": true,
      "loc": "block/ioprio.c:65",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_prep_rw",
        "fs/io_uring.c:io_prep_rw",
        "block/ioprio.c:__ia32_sys_ioprio_set",
        "block/ioprio.c:__x64_sys_ioprio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127600,
      "name": "ioprio_check_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int ioprio_check_cap(int ioprio)
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
