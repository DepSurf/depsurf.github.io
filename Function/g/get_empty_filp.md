# Function: <code>get_empty_filp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * get_empty_filp()
```

```json
{
  "name": "get_empty_filp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999824,
      "name": "get_empty_filp",
      "external": true,
      "loc": "fs/file_table.c:103",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999824,
      "name": "get_empty_filp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct file * get_empty_filp()
```

```json
{
  "name": "get_empty_filp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158080,
      "name": "get_empty_filp",
      "external": true,
      "loc": "fs/file_table.c:103",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158080,
      "name": "get_empty_filp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct file * get_empty_filp()
```

```json
{
  "name": "get_empty_filp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234800,
      "name": "get_empty_filp",
      "external": true,
      "loc": "fs/file_table.c:103",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234800,
      "name": "get_empty_filp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
struct file * get_empty_filp()
```

```json
{
  "name": "get_empty_filp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281920,
      "name": "get_empty_filp",
      "external": true,
      "loc": "fs/file_table.c:104",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281920,
      "name": "get_empty_filp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
struct file * get_empty_filp()
```

```json
{
  "name": "get_empty_filp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581421440,
      "name": "get_empty_filp",
      "external": true,
      "loc": "fs/file_table.c:104",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421440,
      "name": "get_empty_filp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * get_empty_filp()
```

```json
{
  "name": "get_empty_filp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_empty_filp",
      "external": true,
      "loc": "fs/file_table.c:103",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_clone_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580987,
      "name": "get_empty_filp.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581579328,
      "name": "get_empty_filp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
    }
  ]
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct file * get_empty_filp()
```
</details>
</li>
</ul>
