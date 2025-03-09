# Function: <code>set_init_blocksize</code>

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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926496,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926496,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064128,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064128,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141792,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141792,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378256,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:106",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378256,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582437904,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:140",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437904,
      "name": "set_init_blocksize.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582464640,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:139",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464640,
      "name": "set_init_blocksize.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584890336,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "block/bdev.c:130",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890336,
      "name": "set_init_blocksize.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585589088,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "block/bdev.c:126",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585589088,
      "name": "set_init_blocksize.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586355776,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "block/bdev.c:125",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586355776,
      "name": "set_init_blocksize.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586602752,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "block/bdev.c:125",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602752,
      "name": "set_init_blocksize.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586872064,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "block/bdev.c:128",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:bdev_open_by_dev",
        "block/bdev.c:blkdev_get_whole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872064,
      "name": "set_init_blocksize.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493691480,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493691480,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227229668,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227229668,
      "name": "set_init_blocksize",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287291744,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287291744,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273309912,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273309912,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110528,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110528,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582047968,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047968,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101008,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101008,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void set_init_blocksize(struct block_device * bdev)
```

```json
{
  "name": "set_init_blocksize",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582173872,
      "name": "set_init_blocksize",
      "external": false,
      "loc": "fs/block_dev.c:107",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173872,
      "name": "set_init_blocksize",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void set_init_blocksize(struct block_device * bdev)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void set_init_blocksize(struct block_device * bdev)
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
