# Function: <code>__es_find_extent_range</code>

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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358928,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358928,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526976,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    },
    {
      "addr": 18446744071582533813,
      "name": "__es_find_extent_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582626560,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626560,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582936800,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936800,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011232,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011232,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583034224,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034224,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583372352,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372352,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583886272,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886272,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511040,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:254",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511040,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584740880,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584740880,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584973152,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:257",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:__revise_pending",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973152,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494276376,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494276376,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227710652,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227710652,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287987856,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287987856,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273723368,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273723368,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595296,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595296,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532464,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532464,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585408,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585408,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
```

```json
{
  "name": "__es_find_extent_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666960,
      "name": "__es_find_extent_range",
      "external": false,
      "loc": "fs/ext4/extents_status.c:256",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:__es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666960,
      "name": "__es_find_extent_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __es_find_extent_range(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk, ext4_lblk_t end, struct extent_status * es)
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
