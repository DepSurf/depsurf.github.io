# Function: <code>iomap_dio_inline_actor</code>

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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582138667,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap.c:1746",
      "file": "fs/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582309377,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:337",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582408385,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
loff_t iomap_dio_inline_actor(struct inode * inode, loff_t pos, loff_t length, struct iomap_dio * dio, struct iomap * iomap)
```

```json
{
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582701744,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:345",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582701744,
      "name": "iomap_dio_inline_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
loff_t iomap_dio_inline_actor(struct inode * inode, loff_t pos, loff_t length, struct iomap_dio * dio, struct iomap * iomap)
```

```json
{
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772976,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:347",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772976,
      "name": "iomap_dio_inline_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
loff_t iomap_dio_inline_actor(struct inode * inode, loff_t pos, loff_t length, struct iomap_dio * dio, struct iomap * iomap)
```

```json
{
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582801968,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:377",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582801968,
      "name": "iomap_dio_inline_actor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494009708,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227474724,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287661848,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273522954,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582377121,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582314817,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582367601,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
  "name": "iomap_dio_inline_actor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582447297,
      "name": "iomap_dio_inline_actor",
      "external": false,
      "loc": "fs/iomap/direct-io.c:335",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_actor"
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
loff_t iomap_dio_inline_actor(struct inode * inode, loff_t pos, loff_t length, struct iomap_dio * dio, struct iomap * iomap)
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
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
loff_t iomap_dio_inline_actor(struct inode * inode, loff_t pos, loff_t length, struct iomap_dio * dio, struct iomap * iomap)
```
</details>
</li>
</ul>
