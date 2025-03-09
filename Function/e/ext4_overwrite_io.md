# Function: <code>ext4_overwrite_io</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool ext4_overwrite_io(struct inode * inode, loff_t pos, loff_t len)
```

```json
{
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813392,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:128",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813392,
      "name": "ext4_overwrite_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581932751,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:135",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582081415,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:138",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582269539,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:138",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582368193,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:138",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582536582,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:138",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582637621,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582946365,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:191",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dio_write_checks"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583021053,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:190",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dio_write_checks"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583047891,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dio_write_iter"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583384103,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583897912,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:191",
      "file": "fs/ext4/file.c",
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584522632,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:206",
      "file": "fs/ext4/file.c",
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584751689,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:217",
      "file": "fs/ext4/file.c",
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584984473,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:217",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dio_write_checks"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494289816,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227722048,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288003416,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273733024,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582606357,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582543525,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582596469,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
  "name": "ext4_overwrite_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582678533,
      "name": "ext4_overwrite_io",
      "external": false,
      "loc": "fs/ext4/file.c:139",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool ext4_overwrite_io(struct inode * inode, loff_t pos, loff_t len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool ext4_overwrite_io(struct inode * inode, loff_t pos, loff_t len)
```
</details>
</li>
</ul>
