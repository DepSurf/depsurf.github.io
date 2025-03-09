# Function: <code>iomap_to_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581393083,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1897",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581471508,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1939",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581527038,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1936",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581669342,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1896",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581832555,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1867",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581919803,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1875",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582057011,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582134787,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
void iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, struct iomap * iomap)
```

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582365984,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1920",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365984,
      "name": "iomap_to_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, struct iomap * iomap)
```

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582424784,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1919",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582424784,
      "name": "iomap_to_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, struct iomap * iomap)
```

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582445648,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1939",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445648,
      "name": "iomap_to_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, const struct iomap * iomap)
```

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1918",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768272,
      "name": "iomap_to_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071592232073,
      "name": "iomap_to_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, const struct iomap * iomap)
```

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1914",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312224,
      "name": "iomap_to_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071594011819,
      "name": "iomap_to_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, const struct iomap * iomap)
```

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1899",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897952,
      "name": "iomap_to_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    },
    {
      "addr": 18446744071596052062,
      "name": "iomap_to_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, const struct iomap * iomap)
```

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:2036",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120944,
      "name": "iomap_to_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071596574590,
      "name": "iomap_to_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, const struct iomap * iomap)
```

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:2001",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__block_write_begin_int"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584337360,
      "name": "iomap_to_bh",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071597479261,
      "name": "iomap_to_bh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493679992,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227211840,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287282032,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273303336,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582103523,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582040963,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582094003,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
  "name": "iomap_to_bh",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582166769,
      "name": "iomap_to_bh",
      "external": false,
      "loc": "fs/buffer.c:1876",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__block_write_begin_int"
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
void iomap_to_bh(struct inode * inode, sector_t block, struct buffer_head * bh, struct iomap * iomap)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap * iomap</code> ➡️ <code>const struct iomap * iomap</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
