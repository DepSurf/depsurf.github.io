# Function: <code>d_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097744,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2232",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097744,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581263200,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2180",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263200,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581341248,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2189",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341248,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581396624,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2219",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396624,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538208,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2231",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538208,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695472,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2255",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695472,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781840,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2236",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781840,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899600,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899600,
      "name": "d_lookup",
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581972208,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581972208,
      "name": "d_lookup",
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582204848,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2329",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_hash_and_lookup"
      ],
      "caller_func": [
        "fs/namei.c:lookup_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204848,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582252400,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2336",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_hash_and_lookup"
      ],
      "caller_func": [
        "fs/namei.c:lookup_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252400,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582278276,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2363",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_hash_and_lookup"
      ],
      "caller_func": [
        "fs/namei.c:lookup_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278128,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582596740,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2364",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_hash_and_lookup"
      ],
      "caller_func": [
        "fs/namei.c:lookup_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596592,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583127413,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2389",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_hash_and_lookup"
      ],
      "caller_func": [
        "fs/namei.c:lookup_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127264,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583697557,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2423",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_hash_and_lookup"
      ],
      "caller_func": [
        "fs/namei.c:lookup_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697392,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583915429,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2423",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_hash_and_lookup"
      ],
      "caller_func": [
        "fs/namei.c:lookup_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915264,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584121253,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2247",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_hash_and_lookup"
      ],
      "caller_func": [
        "fs/namei.c:lookup_dcache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121088,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493476760,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493476760,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227040580,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227040580,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287037184,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287037184,
      "name": "d_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273155880,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273155880,
      "name": "d_lookup",
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940944,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940944,
      "name": "d_lookup",
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878528,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878528,
      "name": "d_lookup",
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932256,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932256,
      "name": "d_lookup",
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
struct dentry * d_lookup(const struct dentry * parent, const struct qstr * name)
```

```json
{
  "name": "d_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002432,
      "name": "d_lookup",
      "external": true,
      "loc": "fs/dcache.c:2308",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_open",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_dcache",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fuse/dir.c:fuse_reverse_inval_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002432,
      "name": "d_lookup",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
