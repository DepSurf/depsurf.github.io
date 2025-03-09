# Function: <code>ext4_xattr_set_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581845808,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:617",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845808,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040832,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:656",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040832,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582130848,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:660",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582130848,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 841
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232640,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1511",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232640,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3954
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381104,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1532",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381104,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4229
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573568,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573568,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2327
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582673344,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1559",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673344,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2329
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582847552,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847552,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2346
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582951712,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951712,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2346
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268576,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1544",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268576,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2417
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369744,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1549",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369744,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2417
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583392080,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1549",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392080,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2408
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1553",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734592,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2321
    },
    {
      "addr": 18446744071592272065,
      "name": "ext4_xattr_set_entry.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1562",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292512,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2354
    },
    {
      "addr": 18446744071594053926,
      "name": "ext4_xattr_set_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1589",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584940896,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2354
    },
    {
      "addr": 18446744071596085234,
      "name": "ext4_xattr_set_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1616",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168320,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2399
    },
    {
      "addr": 18446744071596608649,
      "name": "ext4_xattr_set_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1616",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585401088,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2399
    },
    {
      "addr": 18446744071597514304,
      "name": "ext4_xattr_set_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494625712,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494625712,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2168
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228071892,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228071892,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2256
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288434688,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288434688,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2380
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273999306,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273999306,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1632
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582920448,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920448,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2346
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582857600,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582857600,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2346
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582909056,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909056,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2346
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
int ext4_xattr_set_entry(struct ext4_xattr_info * i, struct ext4_xattr_search * s, handle_t * handle, struct inode * inode, bool is_block)
```

```json
{
  "name": "ext4_xattr_set_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996128,
      "name": "ext4_xattr_set_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:1560",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996128,
      "name": "ext4_xattr_set_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2346
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>handle_t * handle</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode * inode</code>
</li>
<li>
<b>Param added. </b>
<code>bool is_block</code>
</li>
</ul>
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
