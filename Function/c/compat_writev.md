# Function: <code>compat_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995536,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1101",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__compat_sys_pwritev64",
        "fs/read_write.c:compat_SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995536,
      "name": "compat_writev",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581153376,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1217",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153376,
      "name": "compat_writev.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581230064,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1246",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230064,
      "name": "compat_writev.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276448,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1257",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276448,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414032,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1260",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414032,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570112,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1287",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570112,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655744,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1284",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655744,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773664,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773664,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845888,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845888,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070832,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1393",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev64",
        "fs/read_write.c:__ia32_compat_sys_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070832,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493310872,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493310872,
      "name": "compat_writev",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286852192,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286852192,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581814624,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814624,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752288,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752288,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805936,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805936,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
```

```json
{
  "name": "compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875152,
      "name": "compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_compat_pwritev64",
        "fs/read_write.c:do_compat_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875152,
      "name": "compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, int flags)
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
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
size_t compat_writev(struct file * file, const struct compat_iovec * vec, long unsigned int vlen, loff_t * pos, rwf_t flags)
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
