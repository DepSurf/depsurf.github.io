# Function: <code>iomap_adjust_read_range</code>

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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135088,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap.c:149",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135088,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298480,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298480,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582397472,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397472,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582689024,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:82",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689024,
      "name": "iomap_adjust_read_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582760272,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:88",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760272,
      "name": "iomap_adjust_read_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582789744,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:88",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789744,
      "name": "iomap_adjust_read_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:88",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114944,
      "name": "iomap_adjust_read_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071592245129,
      "name": "iomap_adjust_read_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:82",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583607712,
      "name": "iomap_adjust_read_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
    },
    {
      "addr": 18446744071594025609,
      "name": "iomap_adjust_read_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:90",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211872,
      "name": "iomap_adjust_read_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071596061172,
      "name": "iomap_adjust_read_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:90",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584441600,
      "name": "iomap_adjust_read_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071596585282,
      "name": "iomap_adjust_read_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:196",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664016,
      "name": "iomap_adjust_read_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 470
    },
    {
      "addr": 18446744071597490749,
      "name": "iomap_adjust_read_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493997376,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493997376,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227464596,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227464596,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287643968,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287643968,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273512384,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273512384,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582366208,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366208,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303904,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303904,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582356688,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356688,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
```

```json
{
  "name": "iomap_adjust_read_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436304,
      "name": "iomap_adjust_read_range",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:64",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436304,
      "name": "iomap_adjust_read_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void iomap_adjust_read_range(struct inode * inode, struct iomap_page * iop, loff_t * pos, loff_t length, unsigned int * offp, unsigned int * lenp)
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
