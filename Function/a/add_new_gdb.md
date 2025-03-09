# Function: <code>add_new_gdb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581729011,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:752",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581922548,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:752",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582012612,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:752",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582120584,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:753",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_add_new_descs"
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
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582269736,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:776",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_add_new_descs"
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
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582458205,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:779",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_add_new_descs"
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
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582557792,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:779",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_add_new_descs"
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:779",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582731520,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071582742893,
      "name": "add_new_gdb.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836704,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071582846136,
      "name": "add_new_gdb.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:788",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152944,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1143
    },
    {
      "addr": 18446744071583158520,
      "name": "add_new_gdb.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:788",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234112,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1234
    },
    {
      "addr": 18446744071591347646,
      "name": "add_new_gdb.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:788",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262000,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1166
    },
    {
      "addr": 18446744071591290480,
      "name": "add_new_gdb.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:796",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605040,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1203
    },
    {
      "addr": 18446744071592268739,
      "name": "add_new_gdb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:818",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144048,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1298
    },
    {
      "addr": 18446744071594050308,
      "name": "add_new_gdb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:821",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778480,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1319
    },
    {
      "addr": 18446744071596083037,
      "name": "add_new_gdb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:821",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001840,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1289
    },
    {
      "addr": 18446744071596606500,
      "name": "add_new_gdb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:818",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234000,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1289
    },
    {
      "addr": 18446744071597512183,
      "name": "add_new_gdb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494510408,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494510408,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227947632,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227947632,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288277616,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288277616,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1436
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
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273906542,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273906542,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805440,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071582814872,
      "name": "add_new_gdb.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742592,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071582752024,
      "name": "add_new_gdb.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582794320,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071582803752,
      "name": "add_new_gdb.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
```

```json
{
  "name": "add_new_gdb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_new_gdb",
      "external": false,
      "loc": "fs/ext4/resize.c:806",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_add_new_descs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880800,
      "name": "add_new_gdb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
    },
    {
      "addr": 18446744071582890328,
      "name": "add_new_gdb.cold",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int add_new_gdb(handle_t * handle, struct inode * inode, ext4_group_t group)
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
