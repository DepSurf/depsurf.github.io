# Function: <code>blk_next_bio</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720816,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720816,
      "name": "blk_next_bio",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583908976,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908976,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012176,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012176,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584404391,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard"
      ],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407104,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584520100,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard"
      ],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523008,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584552718,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard"
      ],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555584,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584964126,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard"
      ],
      "caller_func": [
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963936,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct bio * blk_next_bio(struct bio * bio, struct block_device * bdev, unsigned int nr_pages, unsigned int opf, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585608400,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/bio.c:343",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608400,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct bio * blk_next_bio(struct bio * bio, struct block_device * bdev, unsigned int nr_pages, blk_opf_t opf, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586377280,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/bio.c:349",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586377280,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct bio * blk_next_bio(struct bio * bio, struct block_device * bdev, unsigned int nr_pages, blk_opf_t opf, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586623600,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/bio.c:348",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586623600,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct bio * blk_next_bio(struct bio * bio, struct block_device * bdev, unsigned int nr_pages, blk_opf_t opf, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586895104,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/bio.c:348",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:blkdev_issue_secure_erase",
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_zone_mgmt",
        "block/blk-zoned.c:blkdev_zone_reset_all_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895104,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495842176,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495842176,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229190120,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229190120,
      "name": "blk_next_bio",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290034672,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290034672,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274972574,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274972574,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980912,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980912,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916768,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916768,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964672,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964672,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```

```json
{
  "name": "blk_next_bio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584066752,
      "name": "blk_next_bio",
      "external": true,
      "loc": "block/blk-lib.c:13",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-lib.c:__blkdev_issue_zero_pages",
        "block/blk-lib.c:__blkdev_issue_write_zeroes",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:__blkdev_issue_discard",
        "block/blk-zoned.c:blkdev_reset_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584066752,
      "name": "blk_next_bio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct bio * blk_next_bio(struct bio * bio, unsigned int nr_pages, gfp_t gfp)
```
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int opf</code>
</li>
<li>
<b>Param reordered. </b>
<code>bio, nr_pages, gfp</code> ➡️ <code>bio, bdev, nr_pages, opf, gfp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int opf</code> ➡️ <code>blk_opf_t opf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
