# Function: <code>make_indexed_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581620544,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:1930",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620544,
      "name": "make_indexed_dir.isra.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1636
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813152,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:1957",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813152,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1575
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902512,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:1961",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902512,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1562
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582098352,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:1905",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098352,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582247664,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:1900",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247664,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1351
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436080,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:1902",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436080,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1130
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535536,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:1903",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535536,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1130
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582707280,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2036",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582707280,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582809504,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582809504,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583120624,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2053",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120624,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583199952,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2043",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583199952,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227328,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2147",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227328,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1536
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583571168,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2151",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571168,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1541
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584107632,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2201",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107632,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1582
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584741424,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2206",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584741424,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1386
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964928,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2221",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964928,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1451
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585195984,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2225",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585195984,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1439
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494479288,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494479288,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227917428,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_add_entry"
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288239504,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288239504,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1784
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273882562,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273882562,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1066
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582778240,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778240,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715408,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715408,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582767184,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767184,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```

```json
{
  "name": "make_indexed_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582853392,
      "name": "make_indexed_dir",
      "external": false,
      "loc": "fs/ext4/namei.c:2037",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582853392,
      "name": "make_indexed_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
```
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
int make_indexed_dir(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode, struct buffer_head * bh)
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
