# Function: <code>__revise_pending</code>

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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582362502,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1720",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582530457,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1719",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582631524,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
void __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582937344,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582937344,
      "name": "__revise_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011776,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2134",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011776,
      "name": "__revise_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583034768,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2132",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034768,
      "name": "__revise_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
void __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2132",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372736,
      "name": "__revise_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071592254456,
      "name": "__revise_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2132",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583889104,
      "name": "__revise_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071594035442,
      "name": "__revise_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2129",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513952,
      "name": "__revise_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071596068638,
      "name": "__revise_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2176",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742304,
      "name": "__revise_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    },
    {
      "addr": 18446744071596592294,
      "name": "__revise_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len, struct pending_reservation * * prealloc)
```

```json
{
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2238",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974800,
      "name": "__revise_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    },
    {
      "addr": 18446744071597498082,
      "name": "__revise_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494281940,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227716136,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287994624,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273727590,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582600260,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582537428,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582590372,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
  "name": "__revise_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582672106,
      "name": "__revise_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:2110",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
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
void __revise_pending(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pending_reservation * * prealloc</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
