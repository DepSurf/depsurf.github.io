# Function: <code>ext4_ext_convert_to_initialized</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581760963,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3392",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
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
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581959631,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3406",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
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
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582049780,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3406",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
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
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581908451,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3407",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
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
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582058661,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3407",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
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
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582246584,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3401",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
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
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582339614,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3463",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3483",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582508928,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2162
    },
    {
      "addr": 18446744071582525018,
      "name": "ext4_ext_convert_to_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609056,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609056,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2167
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582918800,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3369",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582918800,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2082
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990576,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3368",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990576,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2068
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015712,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3374",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015712,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2071
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3412",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352640,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2026
    },
    {
      "addr": 18446744071592252487,
      "name": "ext4_ext_convert_to_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3410",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863024,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2147
    },
    {
      "addr": 18446744071594033494,
      "name": "ext4_ext_convert_to_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3415",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487264,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2147
    },
    {
      "addr": 18446744071596066731,
      "name": "ext4_ext_convert_to_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3415",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584716016,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2120
    },
    {
      "addr": 18446744071596590484,
      "name": "ext4_ext_convert_to_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3391",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949040,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2133
    },
    {
      "addr": 18446744071597496264,
      "name": "ext4_ext_convert_to_initialized.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494259120,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494259120,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227691336,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227691336,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2076
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287966304,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287966304,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2092
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273708244,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273708244,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1846
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577792,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577792,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2167
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514960,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514960,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2167
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567904,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567904,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2167
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
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```

```json
{
  "name": "ext4_ext_convert_to_initialized",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582649136,
      "name": "ext4_ext_convert_to_initialized",
      "external": false,
      "loc": "fs/ext4/extents.c:3529",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582649136,
      "name": "ext4_ext_convert_to_initialized",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2234
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ext4_ext_convert_to_initialized(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, struct ext4_ext_path * * ppath, int flags)
```
</details>
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
