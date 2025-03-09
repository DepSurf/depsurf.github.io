# Function: <code>do_compat_pwritev64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581153680,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1264",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_pwritev2",
        "fs/read_write.c:compat_SyS_pwritev64v2",
        "fs/read_write.c:compat_SyS_pwritev",
        "fs/read_write.c:compat_SyS_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153680,
      "name": "do_compat_pwritev64.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581230368,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1293",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_pwritev2",
        "fs/read_write.c:compat_SyS_pwritev64v2",
        "fs/read_write.c:compat_SyS_pwritev",
        "fs/read_write.c:compat_SyS_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230368,
      "name": "do_compat_pwritev64.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276976,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1304",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_pwritev2",
        "fs/read_write.c:compat_SyS_pwritev64v2",
        "fs/read_write.c:compat_SyS_pwritev",
        "fs/read_write.c:compat_SyS_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276976,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414560,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1307",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_pwritev2",
        "fs/read_write.c:compat_SyS_pwritev64v2",
        "fs/read_write.c:compat_SyS_pwritev",
        "fs/read_write.c:compat_SyS_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414560,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570656,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1334",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570656,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656288,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656288,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774208,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1356",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774208,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846432,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1356",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846432,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582071975,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1440",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071392,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493311448,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1356",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__arm64_compat_sys_pwritev2",
        "fs/read_write.c:__arm64_compat_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493311448,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286852944,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1356",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_compat_sys_pwritev2",
        "fs/read_write.c:__se_compat_sys_pwritev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286852944,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815168,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1356",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815168,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752832,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1356",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752832,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806480,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1356",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806480,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
```

```json
{
  "name": "do_compat_pwritev64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875696,
      "name": "do_compat_pwritev64",
      "external": false,
      "loc": "fs/read_write.c:1356",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__ia32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_pwritev",
        "fs/read_write.c:__ia32_compat_sys_pwritev",
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875696,
      "name": "do_compat_pwritev64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, int flags)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
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
long int do_compat_pwritev64(long unsigned int fd, const struct compat_iovec * vec, long unsigned int vlen, loff_t pos, rwf_t flags)
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
