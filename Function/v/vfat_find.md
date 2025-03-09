# Function: <code>vfat_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfat_find(struct inode * dir, struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986752,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:691",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_lookup",
        "fs/fat/namei_vfat.c:vfat_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986752,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582199728,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:691",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199728,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582289232,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:702",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289232,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582374096,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:702",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582374096,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524880,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:691",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524880,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582716320,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:691",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582716320,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582820336,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:691",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582820336,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995200,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995200,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101392,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101392,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583426494,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
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
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583540366,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
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
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583563470,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
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
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583922030,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
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
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584501188,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
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
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585167802,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
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
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585396810,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
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
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585631738,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494809296,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494809296,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228228232,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228228232,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288649104,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288649104,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274136940,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274136940,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583070128,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070128,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583007280,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007280,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583058736,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058736,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
```

```json
{
  "name": "vfat_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583147824,
      "name": "vfat_find",
      "external": false,
      "loc": "fs/fat/namei_vfat.c:692",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147824,
      "name": "vfat_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct qstr * qname</code> ➡️ <code>const struct qstr * qname</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int vfat_find(struct inode * dir, const struct qstr * qname, struct fat_slot_info * sinfo)
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
