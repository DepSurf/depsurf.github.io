# Function: <code>mpage_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259008,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:67",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259008,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424624,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:69",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424624,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581505824,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:69",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505824,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558304,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:70",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558304,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581702576,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702576,
      "name": "mpage_alloc.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581869344,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869344,
      "name": "mpage_alloc.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581954416,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954416,
      "name": "mpage_alloc.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582087072,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582087072,
      "name": "mpage_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582164512,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164512,
      "name": "mpage_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400816,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400816,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453808,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453808,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480880,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480880,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582793840,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793840,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493718944,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493718944,
      "name": "mpage_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227244300,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227244300,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287323712,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287323712,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273330296,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273330296,
      "name": "mpage_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582133248,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133248,
      "name": "mpage_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582070688,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070688,
      "name": "mpage_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123728,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123728,
      "name": "mpage_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582196720,
      "name": "mpage_alloc",
      "external": false,
      "loc": "fs/mpage.c:71",
      "file": "fs/mpage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196720,
      "name": "mpage_alloc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct bio * mpage_alloc(struct block_device * bdev, sector_t first_sector, int nr_vecs, gfp_t gfp_flags)
```
</details>
</li>
</ul>
