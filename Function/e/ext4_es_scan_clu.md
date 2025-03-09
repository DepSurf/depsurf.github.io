# Function: <code>ext4_es_scan_clu</code>

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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361968,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_da_get_block_prep",
        "fs/ext4/inode.c:ext4_da_get_block_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361968,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529968,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529968,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630976,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630976,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940112,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_insert_delayed_block",
        "fs/ext4/inode.c:ext4_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940112,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014512,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:407",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_insert_delayed_block",
        "fs/ext4/inode.c:ext4_insert_delayed_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014512,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583040048,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:407",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040048,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583377488,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:407",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377488,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890416,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:407",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890416,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515344,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:405",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515344,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743552,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:405",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743552,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584976176,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:406",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584976176,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494281176,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494281176,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227715576,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227715576,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287993824,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287993824,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273727160,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273727160,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599712,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599712,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582536880,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536880,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589824,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589824,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_es_scan_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671504,
      "name": "ext4_es_scan_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:401",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671504,
      "name": "ext4_es_scan_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool ext4_es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
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
