# Function: <code>__disk_get_part</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583447484,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:85",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450752,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583658944,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:97",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662032,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583765216,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:110",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768816,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583952091,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958336,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584055579,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061808,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584461179,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:148",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "block/bio.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458704,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584576433,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:165",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt"
      ],
      "caller_func": [
        "block/bio.c:guard_bio_eod",
        "block/blk-core.c:submit_bio_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574432,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495895404,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495903600,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229238784,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229246528,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290100088,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290111248,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275012426,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275019078,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584024315,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030544,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583960123,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966336,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584008075,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014304,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "__disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584110551,
      "name": "__disk_get_part",
      "external": true,
      "loc": "block/genhd.c:111",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:disk_get_part"
      ],
      "caller_func": [
        "fs/buffer.c:guard_bio_eod",
        "block/blk-core.c:generic_make_request_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116832,
      "name": "__disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct hd_struct * __disk_get_part(struct gendisk * disk, int partno)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct hd_struct *</code> ➡️ <code>struct block_device *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct block_device * __disk_get_part(struct gendisk * disk, int partno)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
