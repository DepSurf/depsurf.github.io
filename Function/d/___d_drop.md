# Function: <code>___d_drop</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581526224,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:475",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_delete",
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:d_drop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526224,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681744,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:463",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681744,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768400,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768400,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885664,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885664,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958208,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958208,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191040,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191040,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582238544,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238544,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264272,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:461",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264272,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:461",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582256,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071592229712,
      "name": "___d_drop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:486",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116752,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071594009476,
      "name": "___d_drop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:486",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583686720,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071596050774,
      "name": "___d_drop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:486",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904608,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071596573332,
      "name": "___d_drop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:487",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:shrink_dcache_for_umount",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111344,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071597477841,
      "name": "___d_drop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493454600,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493454600,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227028032,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227028032,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287015856,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287015856,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273136646,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273136646,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926944,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926944,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581864528,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864528,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918256,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918256,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void ___d_drop(struct dentry * dentry)
```

```json
{
  "name": "___d_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991328,
      "name": "___d_drop",
      "external": false,
      "loc": "fs/dcache.c:476",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991328,
      "name": "___d_drop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void ___d_drop(struct dentry * dentry)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
