# Function: <code>ksys_getdents64</code>

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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668496,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:295",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668496,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755104,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:295",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755104,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872560,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:295",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872560,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944880,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944880,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175920,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:351",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175920,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493439256,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__arm64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493439256,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227011200,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__se_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227011200,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286994304,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__se_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286994304,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273130796,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__se_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273130796,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581913616,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913616,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581851200,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851200,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581904928,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904928,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```

```json
{
  "name": "ksys_getdents64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974544,
      "name": "ksys_getdents64",
      "external": true,
      "loc": "fs/readdir.c:353",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:__ia32_sys_getdents64",
        "fs/readdir.c:__x64_sys_getdents64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974544,
      "name": "ksys_getdents64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int ksys_getdents64(unsigned int fd, struct linux_dirent64 * dirent, unsigned int count)
```
</details>
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
