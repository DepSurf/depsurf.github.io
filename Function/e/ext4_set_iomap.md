# Function: <code>ext4_set_iomap</code>

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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length)
```

```json
{
  "name": "ext4_set_iomap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996704,
      "name": "ext4_set_iomap",
      "external": false,
      "loc": "fs/ext4/inode.c:3308",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996704,
      "name": "ext4_set_iomap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length)
```

```json
{
  "name": "ext4_set_iomap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072496,
      "name": "ext4_set_iomap",
      "external": false,
      "loc": "fs/ext4/inode.c:3334",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072496,
      "name": "ext4_set_iomap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length)
```

```json
{
  "name": "ext4_set_iomap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097872,
      "name": "ext4_set_iomap",
      "external": false,
      "loc": "fs/ext4/inode.c:3333",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097872,
      "name": "ext4_set_iomap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length)
```

```json
{
  "name": "ext4_set_iomap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_set_iomap",
      "external": false,
      "loc": "fs/ext4/inode.c:3256",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437184,
      "name": "ext4_set_iomap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071592257261,
      "name": "ext4_set_iomap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length, unsigned int flags)
```

```json
{
  "name": "ext4_set_iomap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_set_iomap",
      "external": false,
      "loc": "fs/ext4/inode.c:3306",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955376,
      "name": "ext4_set_iomap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446744071594038308,
      "name": "ext4_set_iomap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length, unsigned int flags)
```

```json
{
  "name": "ext4_set_iomap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_set_iomap",
      "external": false,
      "loc": "fs/ext4/inode.c:3394",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582848,
      "name": "ext4_set_iomap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446744071596071313,
      "name": "ext4_set_iomap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length, unsigned int flags)
```

```json
{
  "name": "ext4_set_iomap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_set_iomap",
      "external": false,
      "loc": "fs/ext4/inode.c:3177",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584809200,
      "name": "ext4_set_iomap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
    },
    {
      "addr": 18446744071596594834,
      "name": "ext4_set_iomap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length, unsigned int flags)
```

```json
{
  "name": "ext4_set_iomap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_set_iomap",
      "external": false,
      "loc": "fs/ext4/inode.c:3216",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042080,
      "name": "ext4_set_iomap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 615
    },
    {
      "addr": 18446744071597500329,
      "name": "ext4_set_iomap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void ext4_set_iomap(struct inode * inode, struct iomap * iomap, struct ext4_map_blocks * map, loff_t offset, loff_t length)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
