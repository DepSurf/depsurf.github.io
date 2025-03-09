# Function: <code>locate_meta_index</code>

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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582132351,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:60",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage"
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582222092,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:60",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage"
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582306935,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:60",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage"
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582456103,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:60",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage"
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582647027,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:60",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage"
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582748789,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:60",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage"
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582921883,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583028427,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct meta_index * locate_meta_index(struct inode * inode, int offset, int index)
```

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583345856,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345856,
      "name": "locate_meta_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
struct meta_index * locate_meta_index(struct inode * inode, int offset, int index)
```

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462304,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462304,
      "name": "locate_meta_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583485416,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583839885,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584408173,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585064381,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:48",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:fill_meta_index"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585293630,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:48",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:fill_meta_index"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585527470,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:48",
      "file": "fs/squashfs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:fill_meta_index"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494724444,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228159140,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288546724,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274072234,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582997163,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582934315,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582985771,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locate_meta_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583074843,
      "name": "locate_meta_index",
      "external": false,
      "loc": "fs/squashfs/file.c:47",
      "file": "fs/squashfs/file.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct meta_index * locate_meta_index(struct inode * inode, int offset, int index)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct meta_index * locate_meta_index(struct inode * inode, int offset, int index)
```
</details>
</li>
</ul>
