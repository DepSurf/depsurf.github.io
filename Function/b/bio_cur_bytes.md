# Function: <code>bio_cur_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582738454,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:134",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_dump_rq_flags",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_end_request_cur",
        "block/blk-core.c:__blk_end_request_cur"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583034994,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:107",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:blk_end_request_cur",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583140002,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:102",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:blk_end_request_cur",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583194772,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:102",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583371268,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:110",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583580804,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:114",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__blk_end_request_cur",
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565536,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691387,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:110",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683536,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583880176,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872208,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583983348,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975104,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584364836,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584362512,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584483331,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:87",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479328,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584517737,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:90",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513984,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584928016,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925392,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495808016,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495795072,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229159352,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    },
    {
      "addr": 3232335664,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "drivers/mtd/mtd_blkdevs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work",
        "drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229150732,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289993904,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289982992,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274945712,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274939436,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583952084,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943840,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583889012,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880784,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583935844,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927600,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
unsigned int bio_cur_bytes(struct bio * bio)
```

```json
{
  "name": "bio_cur_bytes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584037620,
      "name": "bio_cur_bytes",
      "external": false,
      "loc": "include/linux/bio.h:89",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_update_request"
      ],
      "caller_func": [
        "block/blk-core.c:blk_update_request",
        "block/blk-core.c:blk_dump_rq_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028992,
      "name": "bio_cur_bytes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
unsigned int bio_cur_bytes(struct bio * bio)
```
</details>
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
unsigned int bio_cur_bytes(struct bio * bio)
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
