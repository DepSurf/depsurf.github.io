# Function: <code>ext4_xattr_ibody_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581846768,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:1046",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846768,
      "name": "ext4_xattr_ibody_set.isra.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582041936,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:1117",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041936,
      "name": "ext4_xattr_ibody_set.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ext4_xattr_ibody_set(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582131824,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:1123",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131824,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582236608,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2178",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236608,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582385344,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2214",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385344,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582575904,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2230",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575904,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582675680,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2225",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675680,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582849904,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582849904,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582954064,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954064,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583271008,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2213",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271008,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583372176,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2217",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583372176,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583394496,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2217",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394496,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583744320,
      "name": "ext4_xattr_ibody_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2200",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744320,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584301152,
      "name": "ext4_xattr_ibody_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2214",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301152,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584949568,
      "name": "ext4_xattr_ibody_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2233",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949568,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585177632,
      "name": "ext4_xattr_ibody_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2276",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585177632,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585410416,
      "name": "ext4_xattr_ibody_set",
      "external": true,
      "loc": "fs/ext4/xattr.c:2276",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585410416,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494627880,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494627880,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228074148,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228074148,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288437072,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288437072,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274000938,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274000938,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582922800,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922800,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582859952,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582859952,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582911408,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911408,
      "name": "ext4_xattr_ibody_set",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_xattr_ibody_set(handle_t * handle, struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582998480,
      "name": "ext4_xattr_ibody_set",
      "external": false,
      "loc": "fs/ext4/xattr.c:2226",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998480,
      "name": "ext4_xattr_ibody_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int ext4_xattr_ibody_set(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```
</details>
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
<b>Param reordered. </b>
<code>inode, i, is</code> ➡️ <code>handle, inode, i, is</code>
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
