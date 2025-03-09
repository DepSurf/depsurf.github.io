# Function: <code>depot_alloc_stack</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct stack_record * depot_alloc_stack(long unsigned int * entries, int size, u32 hash, void * * prealloc)
```

```json
{
  "name": "depot_alloc_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "depot_alloc_stack",
      "external": false,
      "loc": "lib/stackdepot.c:109",
      "file": "lib/stackdepot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/stackdepot.c:__stack_depot_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586641104,
      "name": "depot_alloc_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
    },
    {
      "addr": 18446744071594199480,
      "name": "depot_alloc_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct stack_record * depot_alloc_stack(long unsigned int * entries, int size, u32 hash, void * * prealloc)
```

```json
{
  "name": "depot_alloc_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "depot_alloc_stack",
      "external": false,
      "loc": "lib/stackdepot.c:120",
      "file": "lib/stackdepot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/stackdepot.c:__stack_depot_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884992,
      "name": "depot_alloc_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446744071596201273,
      "name": "depot_alloc_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct stack_record * depot_alloc_stack(long unsigned int * entries, int size, u32 hash, void * * prealloc)
```

```json
{
  "name": "depot_alloc_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "depot_alloc_stack",
      "external": false,
      "loc": "lib/stackdepot.c:260",
      "file": "lib/stackdepot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/stackdepot.c:__stack_depot_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156832,
      "name": "depot_alloc_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071596726487,
      "name": "depot_alloc_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct stack_record * depot_alloc_stack(long unsigned int * entries, unsigned int nr_entries, u32 hash, depot_flags_t flags, void * * prealloc)
```

```json
{
  "name": "depot_alloc_stack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "depot_alloc_stack",
      "external": false,
      "loc": "lib/stackdepot.c:423",
      "file": "lib/stackdepot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/stackdepot.c:stack_depot_save_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588446576,
      "name": "depot_alloc_stack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    },
    {
      "addr": 18446744071597634760,
      "name": "depot_alloc_stack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct stack_record * depot_alloc_stack(long unsigned int * entries, int size, u32 hash, void * * prealloc)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_entries</code>
</li>
<li>
<b>Param added. </b>
<code>depot_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int size</code>
</li>
<li>
<b>Param reordered. </b>
<code>entries, size, hash, prealloc</code> ➡️ <code>entries, nr_entries, hash, flags, prealloc</code>
</li>
</ul>
</details>
</li>
</ul>
