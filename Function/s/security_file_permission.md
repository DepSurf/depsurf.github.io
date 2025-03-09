# Function: <code>security_file_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239200,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:737",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239200,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582457872,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:759",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457872,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582550336,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:780",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582550336,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582636144,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1385",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636144,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582789968,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1334",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789968,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989600,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:876",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:clone_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989600,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101520,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1397",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101520,
      "name": "security_file_permission",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583286864,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1416",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286864,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583392208,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392208,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583731152,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1626",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731152,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583851472,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1628",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir",
        "fs/remap_range.c:remap_verify_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851472,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882672,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1679",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:kernel_read",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882672,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584241504,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1686",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:kernel_read",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241504,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584855936,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1692",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:kernel_read",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584855936,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585559904,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1733",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:kernel_read",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585559904,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585790848,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:2702",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:kernel_read",
        "fs/readdir.c:iterate_dir",
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585790848,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038912,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:2768",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038912,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495143360,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495143360,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228531088,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228531088,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289062048,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289062048,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274392550,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274392550,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583360944,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360944,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583298048,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298048,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344720,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344720,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int security_file_permission(struct file * file, int mask)
```

```json
{
  "name": "security_file_permission",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439904,
      "name": "security_file_permission",
      "external": true,
      "loc": "security/security.c:1456",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:vfs_fallocate",
        "fs/read_write.c:remap_verify_area",
        "fs/read_write.c:rw_verify_area",
        "fs/readdir.c:iterate_dir",
        "fs/readdir.c:iterate_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439904,
      "name": "security_file_permission",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
