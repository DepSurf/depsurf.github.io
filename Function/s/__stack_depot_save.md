# Function: <code>__stack_depot_save</code>

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
depot_stack_handle_t __stack_depot_save(long unsigned int * entries, unsigned int nr_entries, gfp_t alloc_flags, bool can_alloc)
```

```json
{
  "name": "__stack_depot_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__stack_depot_save",
      "external": true,
      "loc": "lib/stackdepot.c:364",
      "file": "lib/stackdepot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/stackdepot.c:stack_depot_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594199500,
      "name": "__stack_depot_save.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586641568,
      "name": "__stack_depot_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
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
depot_stack_handle_t __stack_depot_save(long unsigned int * entries, unsigned int nr_entries, unsigned int extra_bits, gfp_t alloc_flags, bool can_alloc)
```

```json
{
  "name": "__stack_depot_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__stack_depot_save",
      "external": true,
      "loc": "lib/stackdepot.c:419",
      "file": "lib/stackdepot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/stackdepot.c:stack_depot_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596201293,
      "name": "__stack_depot_save.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587885472,
      "name": "__stack_depot_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
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
depot_stack_handle_t __stack_depot_save(long unsigned int * entries, unsigned int nr_entries, gfp_t alloc_flags, bool can_alloc)
```

```json
{
  "name": "__stack_depot_save",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__stack_depot_save",
      "external": true,
      "loc": "lib/stackdepot.c:358",
      "file": "lib/stackdepot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/stackdepot.c:stack_depot_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596726507,
      "name": "__stack_depot_save.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588157344,
      "name": "__stack_depot_save",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 883
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
depot_stack_handle_t __stack_depot_save(long unsigned int * entries, unsigned int nr_entries, gfp_t alloc_flags, bool can_alloc)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int extra_bits</code>
</li>
<li>
<b>Param reordered. </b>
<code>entries, nr_entries, alloc_flags, can_alloc</code> ➡️ <code>entries, nr_entries, extra_bits, alloc_flags, can_alloc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int extra_bits</code>
</li>
<li>
<b>Param reordered. </b>
<code>entries, nr_entries, extra_bits, alloc_flags, can_alloc</code> ➡️ <code>entries, nr_entries, alloc_flags, can_alloc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
depot_stack_handle_t __stack_depot_save(long unsigned int * entries, unsigned int nr_entries, gfp_t alloc_flags, bool can_alloc)
```
</details>
</li>
</ul>
