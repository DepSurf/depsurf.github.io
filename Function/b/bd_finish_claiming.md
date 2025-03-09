# Function: <code>bd_finish_claiming</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582071392,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071392,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582148976,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148976,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582387472,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1190",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387472,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void bd_finish_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441664,
      "name": "bd_finish_claiming",
      "external": false,
      "loc": "fs/block_dev.c:1057",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441664,
      "name": "bd_finish_claiming",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582470972,
      "name": "bd_finish_claiming",
      "external": false,
      "loc": "fs/block_dev.c:1063",
      "file": "fs/block_dev.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584894521,
      "name": "bd_finish_claiming",
      "external": false,
      "loc": "block/bdev.c:619",
      "file": "block/bdev.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585593474,
      "name": "bd_finish_claiming",
      "external": false,
      "loc": "block/bdev.c:624",
      "file": "block/bdev.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586360424,
      "name": "bd_finish_claiming",
      "external": false,
      "loc": "block/bdev.c:623",
      "file": "block/bdev.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586606387,
      "name": "bd_finish_claiming",
      "external": false,
      "loc": "block/bdev.c:569",
      "file": "block/bdev.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586876314,
      "name": "bd_finish_claiming",
      "external": false,
      "loc": "block/bdev.c:560",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_open_by_dev"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493700272,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493700272,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227226804,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227226804,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287300576,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287300576,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273317020,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273317020,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582117712,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117712,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055152,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055152,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582108192,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108192,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_finish_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582180320,
      "name": "bd_finish_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1209",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180320,
      "name": "bd_finish_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void bd_finish_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```
</details>
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
<b>Param removed. </b>
<code>struct block_device * whole</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, whole, holder</code> ➡️ <code>bdev, holder</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void bd_finish_claiming(struct block_device * bdev, void * holder)
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
