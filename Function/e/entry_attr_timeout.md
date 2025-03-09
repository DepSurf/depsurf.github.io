# Function: <code>entry_attr_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582064075,
      "name": "entry_attr_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:101",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_lookup_name"
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
  "name": "entry_attr_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582286015,
      "name": "entry_attr_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:103",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
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
  "name": "entry_attr_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582374427,
      "name": "entry_attr_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:95",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
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
  "name": "entry_attr_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582459072,
      "name": "entry_attr_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:95",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
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
  "name": "entry_attr_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582609870,
      "name": "entry_attr_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:95",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
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
  "name": "entry_attr_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582802234,
      "name": "entry_attr_timeout",
      "external": false,
      "loc": "fs/fuse/dir.c:95",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582903014,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:79",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905872,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583082950,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:79",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583085120,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583188347,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185872,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583513305,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510608,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583622095,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:114",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619616,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583645215,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:114",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642304,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584002687,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:114",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999776,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584587276,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:117",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584096,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585264840,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:123",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261536,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585495455,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:123",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585491984,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494906476,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:parse_dirplusfile",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494904016,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228316260,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228316260,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288771608,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:parse_dirplusfile",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288768544,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274217708,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274215528,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583157083,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154608,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583094235,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091760,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583141115,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138640,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
```

```json
{
  "name": "entry_attr_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583234667,
      "name": "entry_attr_timeout",
      "external": true,
      "loc": "fs/fuse/dir.c:113",
      "file": "fs/fuse/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232208,
      "name": "entry_attr_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
u64 entry_attr_timeout(struct fuse_entry_out * o)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
u64 entry_attr_timeout(struct fuse_entry_out * o)
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
