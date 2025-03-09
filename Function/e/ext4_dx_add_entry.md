# Function: <code>ext4_dx_add_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581618304,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2156",
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
      "addr": 18446744071581618304,
      "name": "ext4_dx_add_entry.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2235
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581810944,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2181",
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
      "addr": 18446744071581810944,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2202
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900304,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2183",
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
      "addr": 18446744071581900304,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2202
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094672,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2127",
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
      "addr": 18446744071582094672,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3668
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582243984,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2122",
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
      "addr": 18446744071582243984,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3668
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433856,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2124",
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
      "addr": 18446744071582433856,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2223
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582533408,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2125",
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
      "addr": 18446744071582533408,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2115
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582703664,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2265",
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
      "addr": 18446744071582703664,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3616
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805888,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 18446744071582805888,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3616
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583118528,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2293",
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
      "addr": 18446744071583118528,
      "name": "ext4_dx_add_entry",
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197872,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2282",
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
      "addr": 18446744071583197872,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2065
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583225280,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2396",
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
      "addr": 18446744071583225280,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2040
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569120,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2401",
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
      "addr": 18446744071583569120,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2046
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105664,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2451",
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
      "addr": 18446744071584105664,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1954
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739440,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2464",
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
      "addr": 18446744071584739440,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1954
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584962992,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2484",
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
      "addr": 18446744071584962992,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1915
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194048,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2485",
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
      "addr": 18446744071585194048,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1915
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494476152,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 18446603336494476152,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3136
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227912632,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 3227912632,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3644
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288236320,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 13835058055288236320,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3176
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273880094,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 18446743936273880094,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2468
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582774624,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 18446744071582774624,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3616
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582711792,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 18446744071582711792,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3616
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763568,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 18446744071582763568,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3616
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
```

```json
{
  "name": "ext4_dx_add_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582849776,
      "name": "ext4_dx_add_entry",
      "external": false,
      "loc": "fs/ext4/namei.c:2273",
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
      "addr": 18446744071582849776,
      "name": "ext4_dx_add_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3616
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
int ext4_dx_add_entry(handle_t * handle, struct ext4_filename * fname, struct inode * dir, struct inode * inode)
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
