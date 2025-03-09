# Function: <code>ext4_is_pending</code>

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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582364608,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1551",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364608,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532592,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1550",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532592,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634096,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634096,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943152,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943152,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017568,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1962",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017568,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043104,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1960",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043104,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1960",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592254551,
      "name": "ext4_is_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583380528,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1960",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594035521,
      "name": "ext4_is_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071583894032,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1957",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596068717,
      "name": "ext4_is_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584519168,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1995",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596592387,
      "name": "ext4_is_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584747696,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2041",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597498158,
      "name": "ext4_is_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071584980496,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494285216,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494285216,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227719244,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227719244,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287998368,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287998368,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273730006,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273730006,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602832,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602832,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582540000,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540000,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582592944,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592944,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_is_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582674976,
      "name": "ext4_is_pending",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1941",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674976,
      "name": "ext4_is_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ext4_is_pending(struct inode * inode, ext4_lblk_t lblk)
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
