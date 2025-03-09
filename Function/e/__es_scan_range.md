# Function: <code>__es_scan_range</code>

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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359216,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359216,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527232,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:__es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527232,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582626832,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626832,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582937455,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583011887,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:341",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583034881,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:341",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
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
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583372889,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:341",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
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
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583889248,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:341",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
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
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584514096,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:339",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
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
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584742457,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:339",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
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
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584974933,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:340",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494276672,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494276672,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227710976,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227710976,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287988336,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287988336,
      "name": "__es_scan_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273723566,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273723566,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595568,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595568,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532736,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532736,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585680,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585680,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "__es_scan_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667232,
      "name": "__es_scan_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:338",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_insert_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667232,
      "name": "__es_scan_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
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
bool __es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t start, ext4_lblk_t end)
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
