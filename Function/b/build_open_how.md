# Function: <code>build_open_how</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct open_how build_open_how(int flags, umode_t mode)
```

```json
{
  "name": "build_open_how",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055519,
      "name": "build_open_how",
      "external": true,
      "loc": "fs/open.c:990",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open",
        "fs/open.c:file_open_root",
        "fs/open.c:file_open_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054352,
      "name": "build_open_how",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct open_how build_open_how(int flags, umode_t mode)
```

```json
{
  "name": "build_open_how",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582105375,
      "name": "build_open_how",
      "external": true,
      "loc": "fs/open.c:979",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open",
        "fs/open.c:file_open_root",
        "fs/open.c:file_open_name"
      ],
      "caller_func": [
        "fs/io_uring.c:io_req_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104192,
      "name": "build_open_how",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct open_how build_open_how(int flags, umode_t mode)
```

```json
{
  "name": "build_open_how",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582130319,
      "name": "build_open_how",
      "external": true,
      "loc": "fs/open.c:987",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x32_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open",
        "fs/open.c:file_open_root",
        "fs/open.c:file_open_name"
      ],
      "caller_func": [
        "fs/io_uring.c:io_req_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129104,
      "name": "build_open_how",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct open_how build_open_how(int flags, umode_t mode)
```

```json
{
  "name": "build_open_how",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582446975,
      "name": "build_open_how",
      "external": true,
      "loc": "fs/open.c:1005",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__x64_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__x64_compat_sys_open",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open",
        "fs/open.c:file_open_root",
        "fs/open.c:file_open_name"
      ],
      "caller_func": [
        "fs/io_uring.c:io_req_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445744,
      "name": "build_open_how",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct open_how build_open_how(int flags, umode_t mode)
```

```json
{
  "name": "build_open_how",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582965855,
      "name": "build_open_how",
      "external": true,
      "loc": "fs/open.c:1070",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open",
        "fs/open.c:file_open_root",
        "fs/open.c:file_open_name"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_openat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964336,
      "name": "build_open_how",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct open_how build_open_how(int flags, umode_t mode)
```

```json
{
  "name": "build_open_how",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583524911,
      "name": "build_open_how",
      "external": true,
      "loc": "fs/open.c:1102",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open",
        "fs/open.c:file_open_root",
        "fs/open.c:file_open_name"
      ],
      "caller_func": [
        "io_uring/openclose.c:io_openat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583523280,
      "name": "build_open_how",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct open_how build_open_how(int flags, umode_t mode)
```

```json
{
  "name": "build_open_how",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583740319,
      "name": "build_open_how",
      "external": true,
      "loc": "fs/open.c:1191",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open",
        "fs/open.c:file_open_root",
        "fs/open.c:file_open_name"
      ],
      "caller_func": [
        "io_uring/openclose.c:io_openat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738624,
      "name": "build_open_how",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct open_how build_open_how(int flags, umode_t mode)
```

```json
{
  "name": "build_open_how",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583942207,
      "name": "build_open_how",
      "external": true,
      "loc": "fs/open.c:1188",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_creat",
        "fs/open.c:__x64_sys_creat",
        "fs/open.c:__ia32_compat_sys_openat",
        "fs/open.c:__ia32_compat_sys_open",
        "fs/open.c:__ia32_sys_openat",
        "fs/open.c:__x64_sys_openat",
        "fs/open.c:__ia32_sys_open",
        "fs/open.c:__x64_sys_open",
        "fs/open.c:file_open_root",
        "fs/open.c:file_open_name"
      ],
      "caller_func": [
        "io_uring/openclose.c:io_openat_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940512,
      "name": "build_open_how",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct open_how build_open_how(int flags, umode_t mode)
```
</details>
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
