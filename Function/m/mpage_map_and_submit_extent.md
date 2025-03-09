# Function: <code>mpage_map_and_submit_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581580473,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2224",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581767604,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2382",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581856861,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582004815,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2488",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582154821,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2491",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582343482,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2490",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582442501,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2520",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610016,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2532",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610016,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1181
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710928,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710928,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583022160,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2412",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583022160,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097712,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2432",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097712,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122944,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2431",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122944,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2410",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463808,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1259
    },
    {
      "addr": 18446744071592259293,
      "name": "mpage_map_and_submit_extent.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2440",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987264,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071594040691,
      "name": "mpage_map_and_submit_extent.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2457",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618960,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071596073586,
      "name": "mpage_map_and_submit_extent.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2195",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843200,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071596597148,
      "name": "mpage_map_and_submit_extent.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2199",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_do_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076064,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 810
    },
    {
      "addr": 18446744071597502711,
      "name": "mpage_map_and_submit_extent.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494368680,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494368680,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227802972,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227802972,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2084
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288103856,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepages"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273795908,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273795908,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582679664,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582679664,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616832,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616832,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669520,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669520,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```

```json
{
  "name": "mpage_map_and_submit_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753328,
      "name": "mpage_map_and_submit_extent",
      "external": false,
      "loc": "fs/ext4/inode.c:2513",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_writepages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753328,
      "name": "mpage_map_and_submit_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
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
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mpage_map_and_submit_extent(handle_t * handle, struct mpage_da_data * mpd, bool * give_up_on_write)
```
</details>
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
