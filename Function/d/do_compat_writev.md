# Function: <code>do_compat_writev</code>

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
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581153488,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1239",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_pwritev2",
        "fs/read_write.c:compat_SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581153488,
      "name": "do_compat_writev.isra.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581230176,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1268",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_pwritev2",
        "fs/read_write.c:compat_SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230176,
      "name": "do_compat_writev.isra.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, int flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276768,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1279",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_pwritev2",
        "fs/read_write.c:compat_SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276768,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414352,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1282",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_SyS_pwritev2",
        "fs/read_write.c:compat_SyS_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414352,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570400,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1309",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570400,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581656032,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1306",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581656032,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773952,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773952,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846176,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846176,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582071136,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1415",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071136,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493311176,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__arm64_compat_sys_pwritev2",
        "fs/read_write.c:__arm64_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493311176,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286852608,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_compat_sys_pwritev2",
        "fs/read_write.c:__se_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286852608,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581814912,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814912,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752576,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752576,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806224,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806224,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
```

```json
{
  "name": "do_compat_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875440,
      "name": "do_compat_writev",
      "external": false,
      "loc": "fs/read_write.c:1331",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__x32_compat_sys_pwritev2",
        "fs/read_write.c:__ia32_compat_sys_pwritev2",
        "fs/read_write.c:__x32_compat_sys_pwritev64v2",
        "fs/read_write.c:__x32_compat_sys_writev",
        "fs/read_write.c:__ia32_compat_sys_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875440,
      "name": "do_compat_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, int flags)
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
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
size_t do_compat_writev(compat_ulong_t fd, const struct compat_iovec * vec, compat_ulong_t vlen, rwf_t flags)
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
