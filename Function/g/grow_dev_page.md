# Function: <code>grow_dev_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581219940,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:992",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581387289,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:985",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581465829,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:986",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581520526,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:983",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581662670,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:949",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581827187,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:920",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581913315,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:928",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582050460,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582128312,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int grow_dev_page(struct block_device * bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp)
```

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582366800,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:955",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366800,
      "name": "grow_dev_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int grow_dev_page(struct block_device * bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp)
```

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582425584,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:954",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582425584,
      "name": "grow_dev_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
int grow_dev_page(struct block_device * bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp)
```

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453264,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:954",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453264,
      "name": "grow_dev_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int grow_dev_page(struct block_device * bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp)
```

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776688,
      "name": "grow_dev_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
    },
    {
      "addr": 18446744071592232705,
      "name": "grow_dev_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int grow_dev_page(struct block_device * bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp)
```

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:926",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323776,
      "name": "grow_dev_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
    },
    {
      "addr": 18446744071594012545,
      "name": "grow_dev_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int grow_dev_page(struct block_device * bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp)
```

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:926",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__getblk_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909616,
      "name": "grow_dev_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
    },
    {
      "addr": 18446744071596052645,
      "name": "grow_dev_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584138654,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:1043",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_slow"
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
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493670972,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227203488,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_slow"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287272028,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273297402,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582097048,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582034488,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582087528,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "grow_dev_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582160227,
      "name": "grow_dev_page",
      "external": false,
      "loc": "fs/buffer.c:929",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int grow_dev_page(struct block_device * bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int grow_dev_page(struct block_device * bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp)
```
</details>
</li>
</ul>
