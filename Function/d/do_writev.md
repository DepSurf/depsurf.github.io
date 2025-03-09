# Function: <code>do_writev</code>

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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, int flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581151872,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:931",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_pwritev2",
        "fs/read_write.c:SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151872,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, int flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228544,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:960",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_pwritev2",
        "fs/read_write.c:SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228544,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, int flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275984,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1027",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_pwritev2",
        "fs/read_write.c:SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275984,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413568,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1030",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:SyS_pwritev2",
        "fs/read_write.c:SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413568,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569392,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1057",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569392,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655024,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1054",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655024,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772912,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772912,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845136,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845136,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582069872,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1156",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582069872,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582117344,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:972",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117344,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140432,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:970",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140432,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458960,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:961",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x64_compat_sys_pwritev64v2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458960,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582975360,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:972",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975360,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583533360,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:965",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533360,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583749008,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:964",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749008,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952144,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1006",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952144,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493310144,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__arm64_sys_pwritev2",
        "fs/read_write.c:__arm64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493310144,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226911872,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_pwritev2",
        "fs/read_write.c:__se_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226911872,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286851360,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_pwritev2",
        "fs/read_write.c:__se_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286851360,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273050516,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_pwritev2",
        "fs/read_write.c:__se_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273050516,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813872,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813872,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751536,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751536,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805184,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805184,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, rwf_t flags)
```

```json
{
  "name": "do_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581874400,
      "name": "do_writev",
      "external": false,
      "loc": "fs/read_write.c:1072",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x64_sys_pwritev2",
        "fs/read_write.c:__ia32_sys_writev",
        "fs/read_write.c:__x64_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874400,
      "name": "do_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
ssize_t do_writev(long unsigned int fd, const struct iovec * vec, long unsigned int vlen, int flags)
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
