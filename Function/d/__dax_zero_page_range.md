# Function: <code>__dax_zero_page_range</code>

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
int __dax_zero_page_range(struct block_device * bdev, sector_t sector, unsigned int offset, unsigned int length)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493424,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1169",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493424,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int __dax_zero_page_range(struct block_device * bdev, sector_t sector, unsigned int offset, unsigned int length)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575232,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:970",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575232,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635632,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:902",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635632,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780480,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:914",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780480,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581954288,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1148",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954288,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582040480,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1054",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040480,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582201584,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1059",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201584,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582282416,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1060",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282416,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493856792,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1060",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493856792,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287484656,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1060",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287484656,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273425496,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1060",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273425496,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582251152,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1060",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582251152,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582188880,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1060",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188880,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582241632,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1060",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582241632,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```

```json
{
  "name": "__dax_zero_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582322512,
      "name": "__dax_zero_page_range",
      "external": true,
      "loc": "fs/dax.c:1060",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322512,
      "name": "__dax_zero_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, sector_t sector, unsigned int offset, unsigned int length)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dax_device * dax_dev</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int length</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, sector, offset, length</code> ➡️ <code>bdev, dax_dev, sector, offset, size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __dax_zero_page_range(struct block_device * bdev, struct dax_device * dax_dev, sector_t sector, unsigned int offset, unsigned int size)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
