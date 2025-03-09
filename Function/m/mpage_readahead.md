# Function: <code>mpage_readahead</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
```

```json
{
  "name": "mpage_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582405872,
      "name": "mpage_readahead",
      "external": true,
      "loc": "fs/mpage.c:379",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_readahead",
        "fs/fat/inode.c:fat_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405872,
      "name": "mpage_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
```

```json
{
  "name": "mpage_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458816,
      "name": "mpage_readahead",
      "external": true,
      "loc": "fs/mpage.c:379",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_readahead",
        "fs/fat/inode.c:fat_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458816,
      "name": "mpage_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
```

```json
{
  "name": "mpage_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483616,
      "name": "mpage_readahead",
      "external": true,
      "loc": "fs/mpage.c:377",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_readahead",
        "fs/fat/inode.c:fat_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483616,
      "name": "mpage_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
```

```json
{
  "name": "mpage_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582797184,
      "name": "mpage_readahead",
      "external": true,
      "loc": "fs/mpage.c:377",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_readahead",
        "block/fops.c:blkdev_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797184,
      "name": "mpage_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
```

```json
{
  "name": "mpage_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583349696,
      "name": "mpage_readahead",
      "external": true,
      "loc": "fs/mpage.c:344",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_readahead",
        "block/fops.c:blkdev_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349696,
      "name": "mpage_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
```

```json
{
  "name": "mpage_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932912,
      "name": "mpage_readahead",
      "external": true,
      "loc": "fs/mpage.c:349",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_readahead",
        "block/fops.c:blkdev_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932912,
      "name": "mpage_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
```

```json
{
  "name": "mpage_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145712,
      "name": "mpage_readahead",
      "external": true,
      "loc": "fs/mpage.c:370",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_readahead",
        "block/fops.c:blkdev_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145712,
      "name": "mpage_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
```

```json
{
  "name": "mpage_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361488,
      "name": "mpage_readahead",
      "external": true,
      "loc": "fs/mpage.c:369",
      "file": "fs/mpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/inode.c:fat_readahead",
        "block/fops.c:blkdev_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361488,
      "name": "mpage_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void mpage_readahead(struct readahead_control * rac, get_block_t * get_block)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
