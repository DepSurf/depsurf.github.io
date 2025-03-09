# Function: <code>ext4_xattr_inode_update_ref</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582227776,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:979",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227776,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582376448,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:994",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582376448,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582567248,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1022",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567248,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582668688,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1018",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582668688,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582840912,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840912,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945056,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945056,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260240,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:972",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260240,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361168,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:975",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361168,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384480,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:975",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384480,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:976",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728736,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 681
    },
    {
      "addr": 18446744071592271787,
      "name": "ext4_xattr_inode_update_ref.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:991",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285280,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
    },
    {
      "addr": 18446744071594053576,
      "name": "ext4_xattr_inode_update_ref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1007",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932640,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
    },
    {
      "addr": 18446744071596084841,
      "name": "ext4_xattr_inode_update_ref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1035",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585160176,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 633
    },
    {
      "addr": 18446744071596608361,
      "name": "ext4_xattr_inode_update_ref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1035",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392896,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
    },
    {
      "addr": 18446744071597514016,
      "name": "ext4_xattr_inode_update_ref.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494619992,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494619992,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228064500,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228064500,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288425856,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288425856,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 780
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273994320,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273994320,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582913792,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913792,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850944,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850944,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902400,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902400,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
```

```json
{
  "name": "ext4_xattr_inode_update_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989472,
      "name": "ext4_xattr_inode_update_ref",
      "external": false,
      "loc": "fs/ext4/xattr.c:1019",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989472,
      "name": "ext4_xattr_inode_update_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
int ext4_xattr_inode_update_ref(handle_t * handle, struct inode * ea_inode, int ref_change)
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
