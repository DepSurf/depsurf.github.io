# Function: <code>__insert_pending</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357584,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1460",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357584,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525600,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1459",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525600,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582625184,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625184,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582933344,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933344,
      "name": "__insert_pending.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583007936,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1871",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007936,
      "name": "__insert_pending.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033664,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1869",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033664,
      "name": "__insert_pending.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1869",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370480,
      "name": "__insert_pending.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071592253904,
      "name": "__insert_pending.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1869",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882848,
      "name": "__insert_pending.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071594034912,
      "name": "__insert_pending.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1866",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507392,
      "name": "__insert_pending.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071596068138,
      "name": "__insert_pending.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1904",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735888,
      "name": "__insert_pending.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071596591794,
      "name": "__insert_pending.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk, struct pending_reservation * * prealloc)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1944",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973456,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071597498052,
      "name": "__insert_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494274584,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494274584,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227709356,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227709356,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287985952,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287985952,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273722044,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273722044,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593920,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593920,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531088,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531088,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584032,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584032,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__insert_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665584,
      "name": "__insert_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1850",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_delayed_block",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665584,
      "name": "__insert_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __insert_pending(struct inode * inode, ext4_lblk_t lblk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int __insert_pending(struct inode * inode, ext4_lblk_t lblk, struct pending_reservation * * prealloc)
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
