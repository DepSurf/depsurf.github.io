# Function: <code>ext4_xattr_ibody_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852528,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:978",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/inline.c:ext4_inline_data_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852528,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582048176,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:1050",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048176,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582137648,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:1056",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set",
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137648,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582243072,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2111",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582243072,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582392032,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2147",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle",
        "fs/ext4/xattr.c:ext4_xattr_ibody_inline_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392032,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582582608,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2178",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582608,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582683952,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2173",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582683952,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582856608,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856608,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582960768,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960768,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275712,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2161",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275712,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376848,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2165",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376848,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583399776,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2165",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399776,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744096,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2172",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744096,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584300880,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2185",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584300880,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949280,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2204",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949280,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585177344,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2247",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585177344,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585410128,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2247",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585410128,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494635936,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494635936,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228081152,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228081152,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288445856,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288445856,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274006576,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274006576,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582929504,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929504,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582866656,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866656,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582918112,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582918112,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ext4_xattr_ibody_find(struct inode * inode, struct ext4_xattr_info * i, struct ext4_xattr_ibody_find * is)
```

```json
{
  "name": "ext4_xattr_ibody_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005168,
      "name": "ext4_xattr_ibody_find",
      "external": true,
      "loc": "fs/ext4/xattr.c:2174",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_inline_data_truncate",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data",
        "fs/ext4/inline.c:ext4_find_inline_data_nolock",
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_set_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005168,
      "name": "ext4_xattr_ibody_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
