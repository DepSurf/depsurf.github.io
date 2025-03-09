# Function: <code>alloc_io_context</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_context * alloc_io_context(gfp_t gfp_flags, int node)
```

```json
{
  "name": "alloc_io_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585650368,
      "name": "alloc_io_context",
      "external": false,
      "loc": "block/blk-ioc.c:233",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:__copy_io",
        "block/blk-ioc.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650368,
      "name": "alloc_io_context",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_context * alloc_io_context(gfp_t gfp_flags, int node)
```

```json
{
  "name": "alloc_io_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586423456,
      "name": "alloc_io_context",
      "external": false,
      "loc": "block/blk-ioc.c:233",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:__copy_io",
        "block/blk-ioc.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586423456,
      "name": "alloc_io_context",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_context * alloc_io_context(gfp_t gfp_flags, int node)
```

```json
{
  "name": "alloc_io_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671008,
      "name": "alloc_io_context",
      "external": false,
      "loc": "block/blk-ioc.c:229",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:__copy_io",
        "block/blk-ioc.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671008,
      "name": "alloc_io_context",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_context * alloc_io_context(gfp_t gfp_flags, int node)
```

```json
{
  "name": "alloc_io_context",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586941904,
      "name": "alloc_io_context",
      "external": false,
      "loc": "block/blk-ioc.c:229",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq",
        "block/blk-ioc.c:__copy_io",
        "block/blk-ioc.c:set_task_ioprio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941904,
      "name": "alloc_io_context",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct io_context * alloc_io_context(gfp_t gfp_flags, int node)
```
</details>
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
