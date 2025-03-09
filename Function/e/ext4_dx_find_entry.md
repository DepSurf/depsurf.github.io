# Function: <code>ext4_dx_find_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581614623,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1501",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581806906,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1511",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581896330,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1513",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089728,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1483",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089728,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582239328,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1488",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582239328,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429088,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1490",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429088,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582528608,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1491",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528608,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698608,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1622",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698608,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582800816,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582800816,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113184,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1629",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113184,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583192192,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1619",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583192192,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583219856,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1706",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583219856,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1707",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563568,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    },
    {
      "addr": 18446744071592266841,
      "name": "ext4_dx_find_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1753",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099888,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071594048310,
      "name": "ext4_dx_find_entry.cold",
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1758",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584733536,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071596081142,
      "name": "ext4_dx_find_entry.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1773",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956864,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071596604303,
      "name": "ext4_dx_find_entry.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1777",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187952,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071597509735,
      "name": "ext4_dx_find_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494470824,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494470824,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227907832,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:__ext4_find_entry"
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288229024,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288229024,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273875930,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273875930,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582769552,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582769552,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582706720,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582706720,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758800,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758800,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```

```json
{
  "name": "ext4_dx_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844704,
      "name": "ext4_dx_find_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:1623",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:__ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844704,
      "name": "ext4_dx_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
```
</details>
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
struct buffer_head * ext4_dx_find_entry(struct inode * dir, struct ext4_filename * fname, struct ext4_dir_entry_2 * * res_dir)
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
