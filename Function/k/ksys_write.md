# Function: <code>ksys_write</code>

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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577024,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:617",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577024,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662784,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:617",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662784,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581779872,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779872,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852096,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852096,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582076832,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:654",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076832,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122784,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:649",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122784,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147664,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:647",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147664,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582464496,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:638",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464496,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984064,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:633",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984064,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583544192,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583544192,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583760144,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760144,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583962832,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:632",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962832,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493319240,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__arm64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493319240,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226915348,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__se_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226915348,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286858992,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__se_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286858992,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273053012,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__se_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273053012,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581820832,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820832,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758496,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758496,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812144,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812144,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
```

```json
{
  "name": "ksys_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881360,
      "name": "ksys_write",
      "external": true,
      "loc": "fs/read_write.c:626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:xwrite",
        "fs/read_write.c:__ia32_sys_write",
        "fs/read_write.c:__x64_sys_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881360,
      "name": "ksys_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ssize_t ksys_write(unsigned int fd, const char * buf, size_t count)
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
