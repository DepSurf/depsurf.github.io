# Function: <code>get_rsvd</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582629662,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
```

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582937808,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582937808,
      "name": "get_rsvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
```

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012240,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1175",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012240,
      "name": "get_rsvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
```

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583035232,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1175",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583035232,
      "name": "get_rsvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
```

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1175",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370672,
      "name": "get_rsvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
    },
    {
      "addr": 18446744071592253934,
      "name": "get_rsvd.cold",
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
```

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1175",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883056,
      "name": "get_rsvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071594034942,
      "name": "get_rsvd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
```

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1172",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507616,
      "name": "get_rsvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071596068168,
      "name": "get_rsvd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
```

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1205",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736112,
      "name": "get_rsvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071596591824,
      "name": "get_rsvd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
```

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1237",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_remove_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968416,
      "name": "get_rsvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071597497582,
      "name": "get_rsvd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494279836,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227714224,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287992244,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273725990,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582598398,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582535566,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582588510,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
  "name": "get_rsvd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582670142,
      "name": "get_rsvd",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1157",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__es_remove_extent"
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
unsigned int get_rsvd(struct inode * inode, ext4_lblk_t end, struct extent_status * right_es, struct rsvd_count * rc)
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
