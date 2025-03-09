# Function: <code>ext4_es_scan_range</code>

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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361888,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361888,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529888,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529888,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582630896,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630896,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939920,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939920,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014304,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:361",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014304,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583039840,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:361",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583039840,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583377280,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:361",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377280,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890128,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:361",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890128,
      "name": "ext4_es_scan_range",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515040,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:359",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515040,
      "name": "ext4_es_scan_range",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743296,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:359",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743296,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584975920,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:360",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584975920,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494280968,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494280968,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227715460,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227715460,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287993680,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287993680,
      "name": "ext4_es_scan_range",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273727068,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273727068,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582599632,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582599632,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582536800,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536800,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582589744,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589744,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
```

```json
{
  "name": "ext4_es_scan_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671408,
      "name": "ext4_es_scan_range",
      "external": true,
      "loc": "fs/ext4/extents_status.c:358",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671408,
      "name": "ext4_es_scan_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool ext4_es_scan_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end)
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
