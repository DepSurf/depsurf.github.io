# Function: <code>__remove_pending</code>

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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357312,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1509",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357312,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525488,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1508",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525488,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624896,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624896,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933232,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_remove_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933232,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583007824,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1920",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_remove_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007824,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583033552,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1918",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_remove_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033552,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1918",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_remove_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583370336,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071592253874,
      "name": "__remove_pending.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1918",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_remove_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882384,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071594034882,
      "name": "__remove_pending.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1915",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_remove_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584506896,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071596068108,
      "name": "__remove_pending.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1953",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_remove_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735392,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071596591764,
      "name": "__remove_pending.cold",
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1999",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_remove_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968224,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071597497552,
      "name": "__remove_pending.cold",
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494274200,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494274200,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227708576,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227708576,
      "name": "__remove_pending",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287985504,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287985504,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273721740,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273721740,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593632,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593632,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530800,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530800,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582583744,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582583744,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "__remove_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665296,
      "name": "__remove_pending",
      "external": false,
      "loc": "fs/ext4/extents_status.c:1899",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_remove_pending",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665296,
      "name": "__remove_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __remove_pending(struct inode * inode, ext4_lblk_t lblk)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
