# Function: <code>iomap_write_end_inline</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582139292,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap.c:750",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582303456,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582402480,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
int iomap_write_end_inline(struct inode * inode, struct page * page, struct iomap * iomap, loff_t pos, unsigned int copied)
```

```json
{
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582689264,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:713",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582689264,
      "name": "iomap_write_end_inline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
size_t iomap_write_end_inline(struct inode * inode, struct page * page, struct iomap * iomap, loff_t pos, size_t copied)
```

```json
{
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763504,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:691",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582763504,
      "name": "iomap_write_end_inline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582796385,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:691",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583121941,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:676",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583605669,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:679",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584210319,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:693",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584440109,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:715",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584662565,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:818",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494002896,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227469308,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287651312,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273516892,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582371216,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582308912,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582361696,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
  "name": "iomap_write_end_inline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582441392,
      "name": "iomap_write_end_inline",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:682",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
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
int iomap_write_end_inline(struct inode * inode, struct page * page, struct iomap * iomap, loff_t pos, unsigned int copied)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int copied</code> ➡️ <code>size_t copied</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>size_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
size_t iomap_write_end_inline(struct inode * inode, struct page * page, struct iomap * iomap, loff_t pos, size_t copied)
```
</details>
</li>
</ul>
