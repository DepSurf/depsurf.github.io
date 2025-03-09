# Function: <code>mcopy_continue</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t mcopy_continue(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool * mmap_changing)
```

```json
{
  "name": "mcopy_continue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101472,
      "name": "mcopy_continue",
      "external": true,
      "loc": "mm/userfaultfd.c:641",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101472,
      "name": "mcopy_continue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1423
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
ssize_t mcopy_continue(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, atomic_t * mmap_changing)
```

```json
{
  "name": "mcopy_continue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582416864,
      "name": "mcopy_continue",
      "external": true,
      "loc": "mm/userfaultfd.c:666",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582416864,
      "name": "mcopy_continue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2138
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
ssize_t mcopy_continue(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, atomic_t * mmap_changing)
```

```json
{
  "name": "mcopy_continue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930768,
      "name": "mcopy_continue",
      "external": true,
      "loc": "mm/userfaultfd.c:699",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930768,
      "name": "mcopy_continue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2294
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
ssize_t mcopy_continue(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, atomic_t * mmap_changing)
```

```json
{
  "name": "mcopy_continue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583486512,
      "name": "mcopy_continue",
      "external": true,
      "loc": "mm/userfaultfd.c:720",
      "file": "mm/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486512,
      "name": "mcopy_continue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2236
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
ssize_t mcopy_continue(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, bool * mmap_changing)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
ssize_t mcopy_continue(struct mm_struct * dst_mm, long unsigned int start, long unsigned int len, atomic_t * mmap_changing)
```
</details>
</li>
</ul>
