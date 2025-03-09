# Function: <code>mwriteprotect_range</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, bool * mmap_changing)
```

```json
{
  "name": "mwriteprotect_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582027760,
      "name": "mwriteprotect_range",
      "external": true,
      "loc": "mm/userfaultfd.c:639",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_writeprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582027760,
      "name": "mwriteprotect_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, bool * mmap_changing)
```

```json
{
  "name": "mwriteprotect_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582076464,
      "name": "mwriteprotect_range",
      "external": true,
      "loc": "mm/userfaultfd.c:639",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_writeprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076464,
      "name": "mwriteprotect_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, bool * mmap_changing)
```

```json
{
  "name": "mwriteprotect_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582102896,
      "name": "mwriteprotect_range",
      "external": true,
      "loc": "mm/userfaultfd.c:648",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_writeprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102896,
      "name": "mwriteprotect_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t * mmap_changing)
```

```json
{
  "name": "mwriteprotect_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419008,
      "name": "mwriteprotect_range",
      "external": true,
      "loc": "mm/userfaultfd.c:673",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_writeprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419008,
      "name": "mwriteprotect_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t * mmap_changing)
```

```json
{
  "name": "mwriteprotect_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933328,
      "name": "mwriteprotect_range",
      "external": true,
      "loc": "mm/userfaultfd.c:723",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_writeprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933328,
      "name": "mwriteprotect_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t * mmap_changing)
```

```json
{
  "name": "mwriteprotect_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583489040,
      "name": "mwriteprotect_range",
      "external": true,
      "loc": "mm/userfaultfd.c:744",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_writeprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489040,
      "name": "mwriteprotect_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t * mmap_changing)
```

```json
{
  "name": "mwriteprotect_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704592,
      "name": "mwriteprotect_range",
      "external": true,
      "loc": "mm/userfaultfd.c:734",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_writeprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704592,
      "name": "mwriteprotect_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, atomic_t * mmap_changing)
```

```json
{
  "name": "mwriteprotect_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901392,
      "name": "mwriteprotect_range",
      "external": true,
      "loc": "mm/userfaultfd.c:796",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_writeprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901392,
      "name": "mwriteprotect_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int mwriteprotect_range(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool enable_wp, bool * mmap_changing)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool * mmap_changing</code> ➡️ <code>atomic_t * mmap_changing</code>
</li>
</ul>
</details>
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
