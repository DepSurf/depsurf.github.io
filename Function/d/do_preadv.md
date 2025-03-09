# Function: <code>do_preadv</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581151584,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:957",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_preadv2",
        "fs/read_write.c:SyS_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151584,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228256,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:986",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_preadv2",
        "fs/read_write.c:SyS_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228256,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274432,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1053",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_preadv2",
        "fs/read_write.c:SyS_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274432,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419504,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1056",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_preadv2",
        "fs/read_write.c:SyS_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419504,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578880,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1083",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578880,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664640,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1080",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664640,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781712,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781712,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853936,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853936,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582078983,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1186",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x64_sys_preadv"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078576,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582115911,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1002",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x64_sys_preadv"
      ],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_preadv2",
        "fs/read_write.c:__ia32_compat_sys_preadv2",
        "fs/read_write.c:__x32_compat_sys_preadv64v2",
        "fs/read_write.c:__ia32_compat_sys_preadv64v2",
        "fs/read_write.c:__x32_compat_sys_preadv",
        "fs/read_write.c:__ia32_compat_sys_preadv",
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114912,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582139015,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1000",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x64_sys_preadv"
      ],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_preadv2",
        "fs/read_write.c:__ia32_compat_sys_preadv2",
        "fs/read_write.c:__x32_compat_sys_preadv64v2",
        "fs/read_write.c:__ia32_compat_sys_preadv64v2",
        "fs/read_write.c:__x32_compat_sys_preadv",
        "fs/read_write.c:__ia32_compat_sys_preadv",
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138016,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457511,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:991",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x64_sys_preadv"
      ],
      "caller_func": [
        "fs/read_write.c:__x64_compat_sys_preadv2",
        "fs/read_write.c:__ia32_compat_sys_preadv2",
        "fs/read_write.c:__x64_compat_sys_preadv64v2",
        "fs/read_write.c:__ia32_compat_sys_preadv64v2",
        "fs/read_write.c:__x64_compat_sys_preadv",
        "fs/read_write.c:__ia32_compat_sys_preadv",
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582456512,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582977550,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1002",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_preadv2",
        "fs/read_write.c:__ia32_compat_sys_preadv64v2",
        "fs/read_write.c:__ia32_compat_sys_preadv",
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972800,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583536030,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:995",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_preadv2",
        "fs/read_write.c:__ia32_compat_sys_preadv64v2",
        "fs/read_write.c:__ia32_compat_sys_preadv",
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531408,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583751678,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:994",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_preadv2",
        "fs/read_write.c:__ia32_compat_sys_preadv64v2",
        "fs/read_write.c:__ia32_compat_sys_preadv",
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745824,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583950526,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1036",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_preadv2",
        "fs/read_write.c:__ia32_compat_sys_preadv64v2",
        "fs/read_write.c:__ia32_compat_sys_preadv",
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949200,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493321904,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__arm64_sys_preadv2",
        "fs/read_write.c:__arm64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493321904,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226916920,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_preadv2",
        "fs/read_write.c:__se_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226916920,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286861584,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_preadv2",
        "fs/read_write.c:__se_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286861584,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273054294,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_preadv2",
        "fs/read_write.c:__se_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273054294,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822672,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822672,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581760336,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760336,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813984,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813984,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_preadv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883200,
      "name": "do_preadv",
      "external": false,
      "loc": "fs/read_write.c:1102",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_preadv2",
        "fs/read_write.c:__x64_sys_preadv2",
        "fs/read_write.c:__ia32_sys_preadv",
        "fs/read_write.c:__x64_sys_preadv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883200,
      "name": "do_preadv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
ssize_t do_preadv(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flags</code> ➡️ <code>rwf_t flags</code>
</li>
</ul>
</details>
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
