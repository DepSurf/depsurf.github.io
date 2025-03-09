# Function: <code>kcompat_sys_fstatfs64</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903280,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:357",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903280,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028832,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:371",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028832,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106768,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:362",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106768,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582343600,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:362",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582343600,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582395120,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:364",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582395120,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582422416,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:367",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582422416,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745232,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:367",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x64_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745232,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292240,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:367",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292240,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876304,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:367",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876304,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584098064,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:367",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584098064,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584314208,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:367",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314208,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493645360,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:362",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_fstatfs64",
        "fs/statfs.c:__arm64_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493645360,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287236944,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:362",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__se_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287236944,
      "name": "kcompat_sys_fstatfs64",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582075504,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:362",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582075504,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582013056,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:362",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013056,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066784,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:362",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066784,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_fstatfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138528,
      "name": "kcompat_sys_fstatfs64",
      "external": true,
      "loc": "fs/statfs.c:362",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_fstatfs64",
        "fs/statfs.c:__ia32_compat_sys_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138528,
      "name": "kcompat_sys_fstatfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
```
</details>
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
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
int kcompat_sys_fstatfs64(unsigned int fd, compat_size_t sz, struct compat_statfs64 * buf)
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
