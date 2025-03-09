# Function: <code>iomap_seek_data</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725312,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap.c:653",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725312,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871424,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap.c:654",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871424,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054112,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap.c:769",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054112,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148192,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap.c:1403",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148192,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582310624,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310624,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582409680,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409680,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582703408,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582703408,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582774688,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582774688,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582803680,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:80",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803680,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
loff_t iomap_seek_data(struct inode * inode, loff_t pos, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132112,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:80",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132112,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
loff_t iomap_seek_data(struct inode * inode, loff_t pos, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621072,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:80",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621072,
      "name": "iomap_seek_data",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t pos, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225264,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:80",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225264,
      "name": "iomap_seek_data",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t pos, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454704,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:80",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454704,
      "name": "iomap_seek_data",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t pos, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584677824,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:80",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584677824,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494013304,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494013304,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227478540,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227478540,
      "name": "iomap_seek_data",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287664048,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287664048,
      "name": "iomap_seek_data",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273524210,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273524210,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378416,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378416,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316112,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316112,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582368896,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368896,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_seek_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448592,
      "name": "iomap_seek_data",
      "external": true,
      "loc": "fs/iomap/seek.c:186",
      "file": "fs/iomap/seek.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_llseek"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448592,
      "name": "iomap_seek_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
loff_t iomap_seek_data(struct inode * inode, loff_t offset, const struct iomap_ops * ops)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<b>Param added. </b>
<code>loff_t pos</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t offset</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
