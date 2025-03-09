# Function: <code>ksys_lseek</code>

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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566672,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566672,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652304,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652304,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581769680,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769680,
      "name": "ksys_lseek",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841904,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841904,
      "name": "ksys_lseek",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064576,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064576,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582108816,
      "name": "ksys_lseek",
      "external": false,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108816,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133760,
      "name": "ksys_lseek",
      "external": false,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133760,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450416,
      "name": "ksys_lseek",
      "external": false,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450416,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969312,
      "name": "ksys_lseek",
      "external": false,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969312,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528720,
      "name": "ksys_lseek",
      "external": false,
      "loc": "fs/read_write.c:293",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528720,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746528,
      "name": "ksys_lseek",
      "external": false,
      "loc": "fs/read_write.c:293",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746528,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945904,
      "name": "ksys_lseek",
      "external": false,
      "loc": "fs/read_write.c:293",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945904,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493306696,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__arm64_compat_sys_lseek",
        "fs/read_write.c:__arm64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493306696,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226909208,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226909208,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286847040,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_compat_sys_lseek",
        "fs/read_write.c:__se_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286847040,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273048620,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273048620,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581810640,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581810640,
      "name": "ksys_lseek",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748304,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748304,
      "name": "ksys_lseek",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801952,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801952,
      "name": "ksys_lseek",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
```

```json
{
  "name": "ksys_lseek",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871168,
      "name": "ksys_lseek",
      "external": true,
      "loc": "fs/read_write.c:304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_lseek",
        "fs/read_write.c:__ia32_compat_sys_lseek",
        "fs/read_write.c:__ia32_sys_lseek",
        "fs/read_write.c:__x64_sys_lseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871168,
      "name": "ksys_lseek",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
off_t ksys_lseek(unsigned int fd, off_t offset, unsigned int whence)
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
