# Function: <code>clone_verify_area</code>

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
int clone_verify_area(struct file * file, loff_t pos, u64 len, bool write)
```

```json
{
  "name": "clone_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146288,
      "name": "clone_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1625",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146288,
      "name": "clone_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int clone_verify_area(struct file * file, loff_t pos, u64 len, bool write)
```

```json
{
  "name": "clone_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581221472,
      "name": "clone_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1669",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221472,
      "name": "clone_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int clone_verify_area(struct file * file, loff_t pos, u64 len, bool write)
```

```json
{
  "name": "clone_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268464,
      "name": "clone_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1685",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268464,
      "name": "clone_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int clone_verify_area(struct file * file, loff_t pos, u64 len, bool write)
```

```json
{
  "name": "clone_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407552,
      "name": "clone_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1688",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407552,
      "name": "clone_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int clone_verify_area(struct file * file, loff_t pos, u64 len, bool write)
```

```json
{
  "name": "clone_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581562800,
      "name": "clone_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1715",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:vfs_clone_file_range",
        "fs/read_write.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562800,
      "name": "clone_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int clone_verify_area(struct file * file, loff_t pos, u64 len, bool write)
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int clone_verify_area(struct file * file, loff_t pos, u64 len, bool write)
```
</details>
</li>
</ul>
