# Function: <code>bitmap_print_bitmask_to_buf</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int bitmap_print_bitmask_to_buf(char * buf, const long unsigned int * maskp, int nmaskbits, loff_t off, size_t count)
```

```json
{
  "name": "bitmap_print_bitmask_to_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585209520,
      "name": "bitmap_print_bitmask_to_buf",
      "external": true,
      "loc": "lib/bitmap.c:591",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/topology.c:die_cpus_read",
        "drivers/base/node.c:cpumap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585209520,
      "name": "bitmap_print_bitmask_to_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int bitmap_print_bitmask_to_buf(char * buf, const long unsigned int * maskp, int nmaskbits, loff_t off, size_t count)
```

```json
{
  "name": "bitmap_print_bitmask_to_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586045776,
      "name": "bitmap_print_bitmask_to_buf",
      "external": true,
      "loc": "lib/bitmap.c:602",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/topology.c:die_cpus_read",
        "drivers/base/topology.c:cluster_cpus_read",
        "drivers/base/node.c:cpumap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045776,
      "name": "bitmap_print_bitmask_to_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int bitmap_print_bitmask_to_buf(char * buf, const long unsigned int * maskp, int nmaskbits, loff_t off, size_t count)
```

```json
{
  "name": "bitmap_print_bitmask_to_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587028752,
      "name": "bitmap_print_bitmask_to_buf",
      "external": true,
      "loc": "lib/bitmap.c:613",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/topology.c:die_cpus_read",
        "drivers/base/topology.c:cluster_cpus_read",
        "drivers/base/node.c:cpumap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028752,
      "name": "bitmap_print_bitmask_to_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int bitmap_print_bitmask_to_buf(char * buf, const long unsigned int * maskp, int nmaskbits, loff_t off, size_t count)
```

```json
{
  "name": "bitmap_print_bitmask_to_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587283904,
      "name": "bitmap_print_bitmask_to_buf",
      "external": true,
      "loc": "lib/bitmap.c:613",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/topology.c:die_cpus_read",
        "drivers/base/topology.c:cluster_cpus_read",
        "drivers/base/node.c:cpumap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283904,
      "name": "bitmap_print_bitmask_to_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int bitmap_print_bitmask_to_buf(char * buf, const long unsigned int * maskp, int nmaskbits, loff_t off, size_t count)
```

```json
{
  "name": "bitmap_print_bitmask_to_buf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587632480,
      "name": "bitmap_print_bitmask_to_buf",
      "external": true,
      "loc": "lib/bitmap-str.c:180",
      "file": "lib/bitmap-str.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/topology.c:die_cpus_read",
        "drivers/base/topology.c:cluster_cpus_read",
        "drivers/base/node.c:cpumap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632480,
      "name": "bitmap_print_bitmask_to_buf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int bitmap_print_bitmask_to_buf(char * buf, const long unsigned int * maskp, int nmaskbits, loff_t off, size_t count)
```
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
