# Function: <code>do_pwritev</code>

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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152112,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:980",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_pwritev2",
        "fs/read_write.c:SyS_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152112,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228784,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1009",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_pwritev2",
        "fs/read_write.c:SyS_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228784,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276224,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1076",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_pwritev2",
        "fs/read_write.c:SyS_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276224,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413808,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1079",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_pwritev2",
        "fs/read_write.c:SyS_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413808,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569696,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1106",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569696,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655328,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1103",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655328,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773264,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773264,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845488,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845488,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582070631,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1209",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x64_sys_pwritev"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070224,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582118695,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1025",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x64_sys_pwritev"
      ],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117696,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582141783,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1023",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x64_sys_pwritev"
      ],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140784,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582460311,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1014",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x64_sys_pwritev"
      ],
      "caller_func": [
        "fs/read_write.c:__x64_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x64_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x64_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582459312,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582977806,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1025",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975824,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583535758,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1018",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533872,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583751406,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1017",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749520,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583953982,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1059",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952656,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493310504,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__arm64_sys_pwritev2",
        "fs/read_write.c:__arm64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493310504,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226912224,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_pwritev2",
        "fs/read_write.c:__se_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226912224,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286851808,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_pwritev2",
        "fs/read_write.c:__se_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286851808,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273050752,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_pwritev2",
        "fs/read_write.c:__se_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273050752,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581814224,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814224,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751888,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751888,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805536,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805536,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_pwritev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874752,
      "name": "do_pwritev",
      "external": false,
      "loc": "fs/read_write.c:1125",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_pwritev",
        "fs/read_write.c:__x64_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874752,
      "name": "do_pwritev",
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
ssize_t do_pwritev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, loff_t pos, int flags)
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
