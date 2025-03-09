# Function: <code>fuse_change_entry_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582064177,
      "name": "fuse_change_entry_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:89",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_lookup"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582285813,
      "name": "fuse_change_entry_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:91",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582374209,
      "name": "fuse_change_entry_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:83",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582458794,
      "name": "fuse_change_entry_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:83",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582609592,
      "name": "fuse_change_entry_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:83",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582802704,
      "name": "fuse_change_entry_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:83",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902480,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:68",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902480,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583081664,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:68",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583081664,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583185792,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185792,
      "name": "fuse_change_entry_timeout",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583513417,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510464,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583622186,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:103",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619472,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583645306,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:103",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642160,
      "name": "fuse_change_entry_timeout",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584002778,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:103",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999632,
      "name": "fuse_change_entry_timeout",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584587372,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:106",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583952,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585264936,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:112",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261376,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585495557,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:112",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585491824,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585732341,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:112",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585728592,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494903912,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494903912,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228316160,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228316160,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288768448,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288768448,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274215462,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274215462,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154528,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154528,
      "name": "fuse_change_entry_timeout",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091680,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091680,
      "name": "fuse_change_entry_timeout",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138560,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138560,
      "name": "fuse_change_entry_timeout",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
```

```json
{
  "name": "fuse_change_entry_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232128,
      "name": "fuse_change_entry_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:102",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232128,
      "name": "fuse_change_entry_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void fuse_change_entry_timeout(struct dentry * entry, struct fuse_entry_out * o)
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
