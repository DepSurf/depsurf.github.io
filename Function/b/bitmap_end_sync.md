# Function: <code>bitmap_end_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778416,
      "name": "bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/bitmap.c:1525",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_close_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778416,
      "name": "bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586176192,
      "name": "bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/bitmap.c:1532",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_sync_with_cluster",
        "drivers/md/bitmap.c:bitmap_close_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176192,
      "name": "bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586380064,
      "name": "bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/bitmap.c:1560",
      "file": "drivers/md/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_sync_with_cluster",
        "drivers/md/bitmap.c:bitmap_close_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380064,
      "name": "bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586484155,
      "name": "bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/bitmap.c:1562",
      "file": "drivers/md/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483712,
      "name": "bitmap_end_sync.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071586483888,
      "name": "bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586952219,
      "name": "bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1566",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951392,
      "name": "bitmap_end_sync.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071586951568,
      "name": "bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587247592,
      "name": "bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1566",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246720,
      "name": "bitmap_end_sync.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071587246896,
      "name": "bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```
</details>
</li>
</ul>
