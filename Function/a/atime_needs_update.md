# Function: <code>atime_needs_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110368,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1606",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110368,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276000,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1616",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/namei.c:link_path_walk",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276000,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793776,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1680",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793776,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912384,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1693",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912384,
      "name": "atime_needs_update",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581984976,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984976,
      "name": "atime_needs_update",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218608,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1788",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218608,
      "name": "atime_needs_update",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266032,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1789",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266032,
      "name": "atime_needs_update",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291312,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1797",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291312,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610112,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1802",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610112,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583142880,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1883",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583142880,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583714832,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1885",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714832,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932656,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1929",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932656,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139040,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1932",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139040,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493496208,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493496208,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227055360,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227055360,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287059184,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287059184,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273170970,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273170970,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953712,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953712,
      "name": "atime_needs_update",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891280,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891280,
      "name": "atime_needs_update",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945024,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945024,
      "name": "atime_needs_update",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```

```json
{
  "name": "atime_needs_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015056,
      "name": "atime_needs_update",
      "external": true,
      "loc": "fs/inode.c:1704",
      "file": "fs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:trailing_symlink",
        "fs/inode.c:touch_atime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015056,
      "name": "atime_needs_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool atime_needs_update(const struct path * path, struct inode * inode)
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
