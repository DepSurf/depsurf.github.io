# Function: <code>kcompat_sys_statfs64</code>

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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903104,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:338",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903104,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028656,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:352",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028656,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106592,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:343",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106592,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582343424,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:343",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582343424,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582394944,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:345",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582394944,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582422240,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:348",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582422240,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582745056,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:348",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x64_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745056,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583292048,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:348",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583292048,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876080,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:348",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876080,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097840,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:348",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097840,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313984,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:348",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313984,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493645160,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:343",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_statfs64",
        "fs/statfs.c:__arm64_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493645160,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287236704,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:343",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__se_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287236704,
      "name": "kcompat_sys_statfs64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582075328,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:343",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582075328,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012880,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:343",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012880,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066608,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:343",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066608,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
```

```json
{
  "name": "kcompat_sys_statfs64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138352,
      "name": "kcompat_sys_statfs64",
      "external": true,
      "loc": "fs/statfs.c:343",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__x32_compat_sys_statfs64",
        "fs/statfs.c:__ia32_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138352,
      "name": "kcompat_sys_statfs64",
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
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
int kcompat_sys_statfs64(const char * pathname, compat_size_t sz, struct compat_statfs64 * buf)
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
