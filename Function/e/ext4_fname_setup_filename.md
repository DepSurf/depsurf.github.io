# Function: <code>ext4_fname_setup_filename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886464,
      "name": "ext4_fname_setup_filename",
      "external": true,
      "loc": "fs/ext4/crypto_fname.c:395",
      "file": "fs/ext4/crypto_fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry",
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886464,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581805811,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2301",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796160,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581895235,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2281",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885664,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582090203,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2317",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081392,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582239803,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2277",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231008,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582429599,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2278",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420800,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582529119,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2291",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_entry"
      ],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582520288,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582697584,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2328",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697584,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799792,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799792,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112224,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2484",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112224,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191232,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2616",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191232,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219152,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2668",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219152,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583562864,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2738",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562864,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336528,
      "name": "ext4_fname_setup_filename",
      "external": true,
      "loc": "fs/ext4/crypto.c:22",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336528,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584985632,
      "name": "ext4_fname_setup_filename",
      "external": true,
      "loc": "fs/ext4/crypto.c:22",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985632,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585213648,
      "name": "ext4_fname_setup_filename",
      "external": true,
      "loc": "fs/ext4/crypto.c:22",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585213648,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446480,
      "name": "ext4_fname_setup_filename",
      "external": true,
      "loc": "fs/ext4/crypto.c:22",
      "file": "fs/ext4/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_delete_entry",
        "fs/ext4/namei.c:__ext4_unlink",
        "fs/ext4/namei.c:ext4_rmdir",
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446480,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494469880,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494469880,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227916536,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288227632,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288227632,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273875218,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273875218,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582768528,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768528,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582705696,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705696,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582749840,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582749840,
      "name": "ext4_fname_setup_filename",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```

```json
{
  "name": "ext4_fname_setup_filename",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843680,
      "name": "ext4_fname_setup_filename",
      "external": false,
      "loc": "fs/ext4/ext4.h:2386",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843680,
      "name": "ext4_fname_setup_filename",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ext4_fname_setup_filename(struct inode * dir, const struct qstr * iname, int lookup, struct ext4_filename * fname)
```
</details>
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
