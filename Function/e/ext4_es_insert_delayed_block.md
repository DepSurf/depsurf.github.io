# Function: <code>ext4_es_insert_delayed_block</code>

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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582364736,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1576",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364736,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532736,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1575",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532736,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634240,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634240,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943296,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943296,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017712,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1987",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017712,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043248,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1985",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043248,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380688,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1985",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380688,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894192,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1985",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894192,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584519344,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1982",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519344,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584747872,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2018",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584747872,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
void ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584980672,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2064",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980672,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494285456,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494285456,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227719420,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227719420,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287998624,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287998624,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273730124,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273730124,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602976,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602976,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582540144,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540144,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593088,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593088,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
```

```json
{
  "name": "ext4_es_insert_delayed_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675120,
      "name": "ext4_es_insert_delayed_block",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1966",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675120,
      "name": "ext4_es_insert_delayed_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int ext4_es_insert_delayed_block(struct inode * inode, ext4_lblk_t lblk, bool allocated)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
