# Function: <code>compat_readv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995280,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1024",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__compat_sys_preadv64",
        "fs/read_write.c:compat_SyS_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995280,
      "name": "compat_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152896,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1110",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152896,
      "name": "compat_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229584,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1139",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229584,
      "name": "compat_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274656,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1152",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274656,
      "name": "compat_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412224,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1155",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412224,
      "name": "compat_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567600,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1182",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567600,
      "name": "compat_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653232,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1179",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653232,
      "name": "compat_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771136,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1201",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771136,
      "name": "compat_readv",
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843360,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1201",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843360,
      "name": "compat_readv",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582067584,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1285",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_preadv64",
        "fs/read_write.c:__ia32_compat_sys_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067584,
      "name": "compat_readv",
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493308480,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1201",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493308480,
      "name": "compat_readv",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286849328,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1201",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286849328,
      "name": "compat_readv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812096,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1201",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812096,
      "name": "compat_readv",
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749760,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1201",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749760,
      "name": "compat_readv",
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803408,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1201",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803408,
      "name": "compat_readv",
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_readv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872624,
      "name": "compat_readv",
      "external": false,
      "loc": "fs/read_write.c:1201",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_preadv64",
        "fs/read_write.c:do_compat_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872624,
      "name": "compat_readv",
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
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
size_t compat_readv(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
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
