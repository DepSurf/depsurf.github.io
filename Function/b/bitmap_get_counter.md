# Function: <code>bitmap_get_counter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bitmap_counter_t * bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777696,
      "name": "bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/bitmap.c:1314",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_start_sync",
        "drivers/md/bitmap.c:bitmap_end_sync",
        "drivers/md/bitmap.c:bitmap_set_memory_bits",
        "drivers/md/bitmap.c:bitmap_startwrite",
        "drivers/md/bitmap.c:bitmap_endwrite",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777696,
      "name": "bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
bitmap_counter_t * bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586175744,
      "name": "bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/bitmap.c:1321",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_set_memory_bits",
        "drivers/md/bitmap.c:bitmap_end_sync",
        "drivers/md/bitmap.c:bitmap_start_sync",
        "drivers/md/bitmap.c:bitmap_endwrite",
        "drivers/md/bitmap.c:bitmap_startwrite",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586175744,
      "name": "bitmap_get_counter",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bitmap_counter_t * bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586379616,
      "name": "bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/bitmap.c:1349",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_set_memory_bits",
        "drivers/md/bitmap.c:bitmap_end_sync",
        "drivers/md/bitmap.c:bitmap_start_sync",
        "drivers/md/bitmap.c:bitmap_endwrite",
        "drivers/md/bitmap.c:bitmap_startwrite",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586379616,
      "name": "bitmap_get_counter",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bitmap_counter_t * bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586483248,
      "name": "bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/bitmap.c:1351",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_resize",
        "drivers/md/bitmap.c:bitmap_set_memory_bits",
        "drivers/md/bitmap.c:bitmap_start_sync",
        "drivers/md/bitmap.c:bitmap_endwrite",
        "drivers/md/bitmap.c:bitmap_startwrite",
        "drivers/md/bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483248,
      "name": "bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bitmap_counter_t * bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950928,
      "name": "bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1355",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:bitmap_start_sync",
        "drivers/md/md-bitmap.c:bitmap_endwrite",
        "drivers/md/md-bitmap.c:bitmap_startwrite",
        "drivers/md/md-bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950928,
      "name": "bitmap_get_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bitmap_counter_t * bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```

```json
{
  "name": "bitmap_get_counter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587246240,
      "name": "bitmap_get_counter",
      "external": false,
      "loc": "drivers/md/md-bitmap.c:1355",
      "file": "drivers/md/md-bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_resize",
        "drivers/md/md-bitmap.c:bitmap_set_memory_bits",
        "drivers/md/md-bitmap.c:bitmap_start_sync",
        "drivers/md/md-bitmap.c:bitmap_endwrite",
        "drivers/md/md-bitmap.c:bitmap_startwrite",
        "drivers/md/md-bitmap.c:bitmap_daemon_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246240,
      "name": "bitmap_get_counter",
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
bitmap_counter_t * bitmap_get_counter(struct bitmap_counts * bitmap, sector_t offset, sector_t * blocks, int create)
```
</details>
</li>
</ul>
