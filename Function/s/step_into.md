# Function: <code>step_into</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289845,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1732",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581339086,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1742",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581480119,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1740",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581640176,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1727",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581726595,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1768",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581845991,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1766",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581918518,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry, struct inode * inode, unsigned int seq)
```

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134656,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1686",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134656,
      "name": "step_into",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry, struct inode * inode, unsigned int seq)
```

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582181152,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1682",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181152,
      "name": "step_into",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry, struct inode * inode, unsigned int seq)
```

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582202608,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1768",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202608,
      "name": "step_into",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry, struct inode * inode, unsigned int seq)
```

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1796",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520352,
      "name": "step_into",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
    },
    {
      "addr": 18446744071592229490,
      "name": "step_into.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry, struct inode * inode, unsigned int seq)
```

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1842",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component",
        "fs/namei.c:handle_dots",
        "fs/namei.c:handle_dots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583059408,
      "name": "step_into",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
    },
    {
      "addr": 18446744071594009231,
      "name": "step_into.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry)
```

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1826",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component",
        "fs/namei.c:handle_dots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625840,
      "name": "step_into",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
    },
    {
      "addr": 18446744071596050585,
      "name": "step_into.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry)
```

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1831",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component",
        "fs/namei.c:handle_dots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844912,
      "name": "step_into",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446744071596573076,
      "name": "step_into.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry)
```

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1838",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:path_lookupat",
        "fs/namei.c:walk_component",
        "fs/namei.c:handle_dots"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584051728,
      "name": "step_into",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
    },
    {
      "addr": 18446744071597477585,
      "name": "step_into.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493399336,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226985204,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286955312,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273112044,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581887254,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581824854,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581878566,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "step_into",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581948070,
      "name": "step_into",
      "external": false,
      "loc": "fs/namei.c:1759",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last",
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:walk_component"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
const char * step_into(struct nameidata * nd, int flags, struct dentry * dentry, struct inode * inode, unsigned int seq)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int seq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
